# SDGSI028
Trabalho
Projeto de um sistema distribuído.

Ideia inicial: Jogo de tabuleiro classico

A ideia é criar um jogo de tabuleiro, aonde os participantes tem um caminho para percorrer e quem chegar ao fim da linha primeiro vence. A intereção se dará entre 2 ou mais usuarios.
As regras do jogo sao simples, cada jogador terá a sua vez de jogar, e ao rolar os dados irá determinar quantas casas do tabuleiro ele irá andar, e de acordo com aquela casa, terá um bonus, um prejuizo, ou simplemente irá permanecer.
Funcionamento: O servidor ficará aberto à conexão para os usuários até o inicio de uma partida. Assim que dois ou mais jogadores estiver conectado, terá uma contagem de 10 segundos para iniciar a partida, e a cada novo jogador que entrar essa contagem irá reiniciar, até o limite de 4 jogadores.

Linguagem de implementação: O jogo será implementado em Java.

Componentes: 2 ou mais jogadores, 1 interface para rodar o jogo (terminal), 1 servidor para as pessoas acessarem.

Lista de testes a serem implementados:

Ponta a ponta: para mostrar que todas as jogadas que um jogador faz pode ser visto pelos outros.
Concorrência: demonstrando que múltiplos clientes podem acessar o serviço ao mesmo tempo, sem comportamentos estranhos.
