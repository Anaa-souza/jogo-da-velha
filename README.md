##   🎮 Jogo da Velha (Atividade Avanze)

Este projeto é uma versão visual simples de um jogo da velha, construída em HTML e CSS.
Ele exibe um tabuleiro 3x3 com imagens representando os símbolos X e O.

##  📂 Estrutura do Projeto
.
├── index.html       # Estrutura da página ├── style.css    # Estilos do layout e das imagens └── img/   # Pasta com as imagens X e O

##  📝 Sobre os Arquivos
index.html

Define a página principal.

Contém:

Um título (<h1>Atividade do Avanze (o gelado)</h1>)

Um container (.container) que organiza 9 elementos (.fotos), simulando as casas do jogo da velha.

Cada casa exibe uma imagem (X ou O).

style.css

Define o layout responsivo usando Flexbox:

.container: organiza os itens em linhas, centraliza e dá espaçamento.

.fotos: representa cada casa do tabuleiro, com borda, espaçamento interno e imagem ajustada.

h1: centralizado e estilizado com fonte limpa.

As imagens são redimensionadas automaticamente para não distorcer.


##  🎨 Visual Esperado

Um título centralizado.

Abaixo dele, uma grade 3x3 com imagens de X e O distribuídas.

##  🔮 Possíveis Melhorias

Adicionar interatividade com JavaScript para permitir jogar de verdade.

Marcar automaticamente a vitória (linhas, colunas ou diagonais).

Melhorar a responsividade em dispositivos móveis.
