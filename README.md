# Jogo JavaScript

Este projeto é um jogo simples em JavaScript onde o usuário tenta adivinhar um número secreto. O jogo apresenta uma interface visual com mensagens de acerto ou erro.

## Estrutura do Projeto

### HTML

O arquivo HTML define a estrutura básica da página do jogo.

#### Head
- **Meta Tags:** Definem o conjunto de caracteres e configuram a visualização para dispositivos móveis.
- **Fontes:** As fontes são pré-conectadas e carregadas do Google Fonts.
- **CSS:** O arquivo CSS externo é ligado para aplicar estilos à página.
- **Título:** Define o título da página como "JS Game".

#### Body
- **Div Contêiner:** É a estrutura principal que contém todos os elementos do jogo.
- **Imagem do Robô:** Mostra uma imagem de um robô mergulhador.
- **Informações:** Contém a imagem de um troféu e textos que indicam se o usuário acertou o número secreto.

### CSS

O arquivo CSS é utilizado para estilizar a página. Ele pode incluir:
- **Estilos de Layout:** Como posicionamento de contêineres e elementos.
- **Estilos de Texto:** Como fontes, tamanhos e cores de texto.
- **Estilos de Imagem:** Como tamanhos e bordas das imagens.

### JavaScript

O arquivo JavaScript é usado para a lógica do jogo.
- **Função de Adivinhação:** Verifica se o número inserido pelo usuário é o número secreto.
- **Atualização da Interface:** Muda os textos e imagens baseados no acerto ou erro do usuário.

## Como Rodar o Projeto

1. Faça o download dos arquivos do projeto.
2. Abra o arquivo `index.html` em um navegador web.

## Créditos

- **Imagens:** Certifique-se de que as imagens usadas (robô e troféu) estão corretamente referenciadas no diretório `./img/`.
- **Fontes:** As fontes são fornecidas pelo Google Fonts.

## Observações

- Para funcionalidade completa, o arquivo `app.js` deve conter a lógica do jogo, e o arquivo `style.css` deve conter os estilos necessários.
- O script JavaScript é carregado de forma assíncrona para garantir que a página é renderizada antes da execução do script.

## Deploy
- https://jsgame-seven.vercel.app
