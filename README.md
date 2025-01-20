# jogo-da-memoria-com-emoji


Este é um **Jogo da Memória** simples utilizando **emojis**. O objetivo do jogo é encontrar pares de cartas correspondentes. O jogador deve virar duas cartas por vez e, se as cartas forem iguais, elas permanecerão viradas para cima.

## Funcionalidades

- **Emojis como cartas**: As cartas são representadas por emojis, o que torna o jogo mais divertido e visual.
- **Jogo de memória clássico**: O jogador precisa combinar pares de cartas para vencer o jogo.
- **Tela final**: Ao vencer, o jogo exibe uma tela comemorativa informando que o jogador ganhou.
- **Botão de reset**: Ao clicar no botão "RESET GAME", o jogo reinicia, permitindo que o jogador comece novamente.

## Como usar

1. Clone o repositório para sua máquina:
    ```bash
    git clone https://github.com/seu-usuario/jogo-da-memoria.git
    ```

2. Abra o arquivo `index.html` em seu navegador para jogar.

## Estrutura de arquivos

O projeto possui os seguintes arquivos principais:

- `index.html`: A estrutura HTML da página.
- `src/styles/main.css`: O estilo principal do jogo, incluindo o layout e o design das cartas.
- `src/styles/reset.css`: O estilo de reset para garantir a aparência consistente entre navegadores.
- `src/scripts/engine.js`: A lógica JavaScript que implementa o jogo da memória.

## Tecnologias utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilo da interface, incluindo o layout das cartas, animações e a tela de vitória.
- **JavaScript**: Lógica do jogo da memória, que gerencia a rotação das cartas, a verificação de pares e o controle do estado do jogo.

## Como funciona

### HTML
O HTML define a estrutura básica da página, incluindo o título, a área do jogo e o botão de reset.

### CSS
O CSS aplica estilos ao layout, incluindo o design das cartas e animações para a rotação das cartas. As cartas giram quando o jogador interage com elas.

### JavaScript
O JavaScript adiciona a funcionalidade do jogo da memória. Quando o jogador clica em uma carta, ela vira. O código verifica se duas cartas abertas são iguais. Se forem, elas permanecem viradas. Caso contrário, elas são viradas novamente.

#### Funções principais:
- `handleClick`: Gerencia o clique nas cartas e verifica quando duas cartas foram abertas.
- `checkMatch`: Verifica se as cartas abertas são iguais e atualiza o estado do jogo.
- `screenFinal`: Exibe uma mensagem de vitória quando todos os pares são encontrados.
- `excluirScreen`: Remove a tela de vitória após algum tempo.

## Exemplo de uso

1. Clique em uma carta para virá-la.
2. Clique em outra carta para tentar encontrar o par correspondente.
3. Quando todos os pares forem encontrados, você vencerá o jogo e verá uma mensagem de vitória.

## Contribuição

Sinta-se à vontade para contribuir com melhorias no projeto, correções ou novos recursos! Basta abrir uma **issue** ou enviar um **pull request**.
