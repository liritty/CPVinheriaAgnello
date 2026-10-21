## Equipe Ctrl + 5
Eduardo Ambra Giordano de Castro, Flávia Sirahata Hasegava e Lirity Ribeiro de Paiva.

# Projeto Vinheria Agnello
Site desenvolvido para o case da empresa fictícia Vinheria Agnello na disciplina de Front-end Design da FIAP.

## Sobre
O projeto resolve o problema do empresário fictício Sr. Giulio e sua filha Bianca, que seria criar um website da Vinheria Agnello que possui apenas uma loja física, na qual se destacam por prestar consultorias de vinhos e espumantes nacionais e internacionais para todos os tipos de cliente. Sua empresa deseja expandir seus negócios para o meio digital.

## Repositório
- GitHub: https://github.com/liritty/CPVinheriaAgnello.git
- GitHub Pages: https://liritty.github.io/CPVinheriaAgnello/

## Conteúdos
- [Home](#-home) - Lirity 
Página inicial que da a abertura do site.
- [Sobre](#-sobre) - Flávia
Conta um pouco da trajetória da empresa.
- [Galeria](#-galeria) - Flávia
Mostruário dos vinhos e espumantes.
- [Equipe](#-equipe) - Lirity
Apresentação da equipe da Vinheria Agnello.
- [Contato](#-contato) - Eduardo
Formulário para entrar em contato com a empresa.

## Tecnologias
- [HTML]
- [CSS]

## ADIÇÃO: Efeitos Visuais
Todos os efeitos estão em `src/css/efeitos.css`, importado por `<link>` em todas as páginas e organizado por página.

### Pseudo-classes
- `:hover` — botões, cards da equipe, imagens da galeria e links do menu.
- `:active` — botão "Veja mais" da Home.
- `:focus` e `:focus-within` — campos e rótulos do formulário de contato.
- `:nth-child()` — cores dos títulos do Sobre e entrada escalonada dos cards da equipe.
- `:not()` — aplica a animação de entrada em todas as páginas, exceto na Home.

### Pseudo-elementos
- `::after` — sublinhado dourado do menu.
- `::first-letter` — letra capitular nos parágrafos do Sobre.
- `::selection` — cor personalizada ao selecionar textos.
- `::placeholder` — cor suave nos campos do formulário.

### Animações (`@keyframes`)
- `aparecer` — o conteúdo sobe suavemente ao entrar.
- `da-esquerda` e `da-direita` — "Vinheria" e "Agnello" entram pelos lados na Home.

### Transições e transformações
- `translateY()` e `translateX()` — entrada dos elementos e elevação dos botões.
- `scale()` — zoom nas imagens da galeria e no avatar da equipe.
- `scaleX()` — crescimento do sublinhado do menu.
- `rotateY()` — giro 3D dos cards da equipe.
- Transições suaves nos botões, cards, menu, galeria e formulário.

## Estrutura do projeto
```bash
CPVinheriaAgnello/
│
├── index.html            # Home
├── README.md
└── src/
    ├── assets/
    │   └── imgs/
    ├── css/
    │   ├── style.css     # Estilização geral das páginas
    │   └── efeitos.css   # Efeitos visuais (pseudo-classes, animações, transições)
    └── pages/
        ├── sobre.html
        ├── galeria.html
        ├── equipe.html
        └── contato.html
```
