# Vinharia Agnello

Projeto acadêmico desenvolvido para os Check-Points 01 e 02
da disciplina de Front-End.

A Vinharia Agnello é uma empresa familiar que busca ampliar sua
presença no ambiente digital, mantendo o atendimento personalizado
e a orientação especializada na escolha de vinhos.

O site apresenta a empresa, seus produtos e sugestões de harmonização.

## Integrantes

- Gabriel Morone

## Páginas do site

- **Início:** apresentação da vinharia, diferenciais, cuidados com
  armazenamento e vídeo sobre vinhos.
- **Nossa história:** trajetória da empresa e transformação digital.
- **Produtos:** categorias de vinhos e catálogo com preços fictícios.
- **Harmonização:** sugestões para combinar vinhos com alimentos
  e diferentes ocasiões.
- **Contato:** apresentação do atendimento e contato por e-mail.

## Estrutura do projeto

- `index.html`: página inicial.
- `src/pages/historia.html`: história da empresa.
- `src/pages/produtos.html`: categorias e catálogo de vinhos.
- `src/pages/harmonizacao.html`: dicas de harmonização.
- `src/pages/contato.html`: informações de contato.
- `src/css/style.css`: importação dos arquivos de estilos.
- `src/css/base.css`: estilos originais do Check-Point 01.
- `src/css/efeitos.css`: efeitos visuais do Check-Point 02.
- `src/assets/imgs/`: imagens utilizadas nas páginas.
- `README.md`: documentação do projeto.

## Tecnologias utilizadas

- HTML5
- CSS3
- Git e GitHub
- GitHub Pages

## Efeitos Visuais

Os efeitos foram aplicados às páginas existentes, preservando
a estrutura e as cores principais do site.

### Pseudo-classes

- `:hover`: altera a aparência de menus, links, botões, cards,
  imagens e linhas da tabela ao passar o mouse.
- `:focus-visible`: destaca links e botões durante a navegação
  pelo teclado.
- `:active`: reduz levemente os botões durante o acionamento.
- `:nth-child(even)`: alterna a cor de fundo das linhas da tabela
  de produtos, facilitando a leitura.
- `:not(.botao)`: aplica estilos aos links de texto sem modificar
  os links que utilizam a classe de botão.
- `:first-child`: seleciona a primeira seção de cada página
  para receber a animação de entrada.

### Pseudo-elementos

- `::before`: cria uma barra decorativa abaixo dos títulos
  das seções.
- `::after`: cria uma linha animada abaixo dos links do menu.
- `::selection`: personaliza as cores do texto selecionado.

### Animação com @keyframes

A animação `entrada-suave` apresenta a primeira seção de cada
página com aumento gradual de opacidade e deslocamento vertical.

O efeito dura 650 milissegundos e acontece uma vez a cada
carregamento da página.

### Transições

Foram adicionadas transições suaves para mudanças de cor,
sombra e transformação em elementos como:

- Links do menu.
- Links de texto.
- Botões.
- Cards de categorias, harmonizações e ocasiões.
- Imagens.
- Linhas da tabela de produtos.

### Transformações

- `translateY()`: cria um pequeno deslocamento vertical em
  botões, cards e na animação de entrada.
- `scale()`: amplia discretamente as imagens e reduz os botões
  durante o acionamento.
- `scaleX()`: revela a linha decorativa dos links do menu.

### Acessibilidade e leveza

- Destaque de foco para navegação pelo teclado.
- Animação de entrada sem repetição contínua.
- Respeito à preferência `prefers-reduced-motion`, desativando
  animações, transições e movimentos decorativos.
- Efeitos de hover em cards e imagens limitados a dispositivos
  com ponteiro preciso e suporte a hover.
- Efeitos implementados apenas com CSS, sem JavaScript.

## Organização dos estilos

Todas as páginas carregam o arquivo `style.css`.

Ele importa primeiro `base.css`, que contém os estilos originais,
e depois `efeitos.css`, que contém os novos efeitos.

Essa organização mantém a importação de `efeitos.css` no final
de `style.css`, respeitando a regra do CSS de que declarações
`@import` devem aparecer antes dos blocos de estilos.

## Como executar

1. Clone o repositório:
   `git clone https://github.com/gabrielmorone75/checkpoint-front.git`
2. Abra a pasta do projeto no VS Code.
3. Abra o arquivo `index.html` no navegador.

Também é possível utilizar a extensão Live Server no VS Code.

## Como conferir os efeitos

- Passe o mouse pelos links do menu e pelos botões.
- Use a tecla Tab para observar o destaque de foco.
- Passe o mouse sobre as imagens e os cards.
- Acesse Produtos para conferir as linhas alternadas da tabela.
- Recarregue uma página para observar a animação de entrada.
- Selecione um trecho de texto para conferir as cores de seleção.

## Uso de inteligência artificial

O projeto contou com apoio do ChatGPT na organização do conteúdo,
nas explicações de desenvolvimento, na criação das imagens
ilustrativas e na elaboração dos efeitos CSS.

A ferramenta foi utilizada como apoio ao aprendizado.

## Links

- [Repositório no GitHub](https://github.com/gabrielmorone75/checkpoint-front)
- [Site no GitHub Pages](https://gabrielmorone75.github.io/checkpoint-front/)

## Observação

Os produtos e preços apresentados são fictícios e utilizados
exclusivamente para fins acadêmicos.