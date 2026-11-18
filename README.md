# Pesquisa-Operacional
Este espaço reúne os projetos práticos e relatórios desenvolvidos durante a disciplina de Pesquisa Operacional, ministrado pelo professor Carlos Eduardo Bastos no 2º semestre de Gestão de Produção Industrial (GPI).

O objetivo deste registro é consolidar o aprendizado por meio de problemas de Modelagem Linear, Programação e Aplicações​, Problemas de Transporte e Transbordo​ e a Teoria das Filas, utilizando ferramentas de mercado como Excel.

# Modelagem Linear
Para decidir entre as alternativas de solução, o decisor deverá utilizar algum procedimento/metodologia para escolher a “melhor solução” que poderá ser aplicada. 
No meio quantitativo, a metodologia aplicada e a Modelagem que e o processo de selecionar as informações que interessam para conseguir fazer a melhor escolha de acordo com a matemática.

##Vendedor de meias
Aqui nos temos o problema:
"Um vendedor de meias possui:​ 84 pares de meias de lã​ e 24 pares de meias de algodão. Porém os clientes compram Kits de meias, os Kits são compostos da seguinte forma:
​

Kit A - 2 pares de meias de algodão e 4 pares de meias de lã​.

Kit B - 8 pares de meias de lã e 2 pares de meias algodão​.

A margem de lucro de cada é:​
Kit A = R$6,00​ e o Kit B = R$8,00
​
Qual deve ser a quantidade vendida de cada Kit para gerar a maior margem de lucro?"


Primeiro fazemos a modelagem:
Nosso objetivo é determinar a quantidade a ser vendida de cada Kit para gerar a maior margem de lucro, considerando a quantidade disponível de cada tipo de meia.
Identifique as variáveis de decisão: 
​
A = quantidade a ser vendida do Kit A
​
B = quantidade a ser vendida do Kit B

Escreva a função objetivo (Representar o lucro por uma função linear, indicando que o objetivo é maximizar​)

Escreva as restrições (representar por uma função linear a quantidade necessária de cada tipo de meia, para atender os kits, e sua relação com a quantidade disponível de cada uma)​
A modelagem final é:
Max: 6,00.A + 8,00.B

R1: 2.A + 2.B <= 24
​
R2: 4.A + 8.B <= 84
