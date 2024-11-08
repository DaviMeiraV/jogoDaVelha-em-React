Jogo da Velha em React

Este é um projeto de um jogo da velha (tic-tac-toe) desenvolvido em React. Ele utiliza componentes funcionais e hooks para gerenciar o estado do jogo e oferece uma interface amigável para a interação dos usuários.

Como Funciona

O jogo da velha permite que dois jogadores joguem alternadamente, utilizando 'X' e 'O'. O primeiro jogador a completar três quadrados em linha (horizontal, vertical ou diagonal) vence o jogo. Além disso, é possível voltar para jogadas anteriores através da lista de movimentos exibida na interface.

Estrutura do Projeto

Game: Componente principal que gerencia o histórico de movimentos e a lógica para voltar a jogadas anteriores.

Board: Componente que representa o tabuleiro do jogo. Ele recebe as informações sobre o estado atual do jogo e renderiza os quadrados.

Square: Componente que representa cada quadrado do tabuleiro e responde aos cliques dos jogadores.

calculateWinner: Função que verifica se há um vencedor com base nos valores do tabuleiro.

Estilo

O estilo do jogo está definido no arquivo index.css, garantindo uma interface visual agradável, com botões estilizados e uma exibição clara do tabuleiro e do status do jogo.

Funcionalidades

Dois Jogadores: O jogo alterna entre os jogadores 'X' e 'O'.

Histórico de Movimentos: A aplicação mantém um histórico de todos os movimentos, permitindo que os jogadores voltem para qualquer ponto do jogo.

Detecção de Vencedor: A lógica do jogo identifica quando um jogador vence e exibe uma mensagem de vitória.

Tecnologias Utilizadas

React: Biblioteca JavaScript para criar a interface do usuário.

CSS: Para estilização dos componentes e layout do jogo.

Próximos Passos

Melhorar a UI/UX: Adicionar animações ou efeitos visuais para tornar a experiência mais interativa.

Adicionar Jogador Contra IA: Implementar uma inteligência artificial para jogar contra um único jogador.

Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests no repositório para melhorias ou correções.
