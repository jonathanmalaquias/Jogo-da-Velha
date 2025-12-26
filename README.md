JOGO DA VELHA, Game of the oldwoman :D

######################      🇧🇷 Português     ##################################
Primeiro projeto solo em Python: um jogo da velha simples, focado em dicionários e conjuntos (Sets).
 É possível jogar várias partidas e acumular vitórias. O jogo permite que os jogadores sobrescrevam 
espaços já ocupados, gerando competitividade — um "erro lógico" que foi reaproveitado como uma nova
 mecânica para um jogo antigo e repetitivo.

Embora funcional, o projeto apresenta limitações técnicas que serviram de aprendizado para projetos
 futuros:

O jogo usa funções que chamam umas às outras para manter a passagem de turno; aprendi que isso 
consome memória RAM desnecessária (recursividade).

O programa aceita qualquer entrada de texto além das coordenadas (A, B, C e 1, 2, 3), mas elas não
 geram resultado, fazendo o jogador que digitou errado "perder" o turno.

O uso frequente de global facilitou o acesso às variáveis, mas passar essas variáveis como argumentos
 dentro das funções deixará o código mais seguro, organizado e limpo para simulações complexas.

Enfim, há muito o que aprender! :)



###########################   🇺🇸 English    #######################################
First solo Python project: a simple Tic-Tac-Toe game focused on dictionaries and sets. It supports
 multiple rounds with a win counter. The game allows players to overwrite already occupied spaces to
 increase competitiveness — a "logical error" that was repurposed as a new mechanic for an old and 
repetitive game.

Although functional, the project has technical limitations that served as valuable lessons for future
 projects:

The game uses functions that call each other to manage turns; I learned that this consumes unnecessary
 RAM (recursion).

The program accepts any text input beyond the coordinates (A, B, C and 1, 2, 3), but invalid inputs
 result in no action, causing the player to effectively "lose" their turn.

The frequent use of global made it easier to access variables, but passing these variables as arguments
 within functions will make the code more secure, organized, and clean for complex simulations.

Anyway, there is still much to learn! :)
