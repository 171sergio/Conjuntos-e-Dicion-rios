A atividade consiste em criar um grid infinito em processing, com as seguintes características:
O grid inicialmente tem todas as células brancas.
Ao clicar em uma célula, ela deve ser alterada para uma cor conforme o número de cliques (preto, verde, vermelho, azul, amarelo e branco) e de maneira circular.
Como o grid é infinito ele não pode ser representado por um array bidimensional (matrix). Nesse caso usaremos um dicionário, onde a chave é uma string (˜linha,coluna˜) e o valor é a cor, contudo não se armazena a cor branca.
O usuário pode movimentar o grid arrestando o mouse (pan) e pode dar zoom no grid com a roda do mouse.
