# Circuitos
## 4-bit-Adder
### Entradas: São 8 entradas, sendo 4 bits de A, os quais são A0, A1, A2 e A3. Os outros 4 restantes são B0, B1, B2 e B3. O valor de bits que cada entrada suporta é 2 elevado ao número dela mesma. Sendo asssim, ao somar todas, o máximo será 30.
### Saídas: É o resultado da soma de todas as entradas.
### Explicação: Primeiro há um half adder e ele envia a soma para o 1-8 BIT, já o carry é passado para o carry in do próximo full adder, pois é uma casa para cima. Seguindo a lógica, a soma desse se liga ao final e o carry out se liga ao carry in do próximo full adder da próxima casa. Após seguir essa sequência o último carry out se liga ao final para juntar a soma no 1-8 BIT.
## Half Subtractor
### Entradas: São 2 entradas: A é o minuendo, B é o subtraendo.
### Saídas: É o resultado da subtração de A e B. Diff é o resultado da subtração e borrow seria o número emprestado.
### Explicação:  As portas presentes são o XOR, NOT e AND. Cada entrada se conecta com as portas XOR e AND (a conexão de A com AND é anulada com o NOT). 