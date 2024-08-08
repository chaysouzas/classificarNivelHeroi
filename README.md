# Classificador de Nível de Herói,
Desafio proposto no curso Lógica de Programação - DIO

O código define variáveis para armazenar o nome de um herói, sua quantidade de experiência (XP), e seu nível. A função `classificarNivelHeroi()` é responsável por determinar o nível do herói com base no valor de XP. 



A função usa uma estrutura condicional `if-else if-else` para verificar em qual intervalo a quantidade de XP se encaixa:



- Se o XP for 1000 ou menos, o nível será "Ferro".

- Se estiver entre 1001 e 2000, o nível será "Bronze".

- Se estiver entre 2001 e 5000, o nível será "Prata".

- Se estiver entre 5001 e 7000, o nível será "Ouro".

- Se estiver entre 7001 e 8000, o nível será "Platina".

- Se estiver entre 8001 e 9000, o nível será "Ascendente".

- Se estiver entre 9001 e 10000, o nível será "Imortal".

- Qualquer valor acima de 10000 será classificado como "Radiante".



Após determinar o nível, a função exibe uma mensagem no console exibindo o nome do herói, sua quantidade de XP, e o nível correspondente. 

No exemplo a função é chamada, classificando e exibindo as informações do herói "Juninho" com 80 XP, resultando no nível "Ferro".
