# Pesquisa-Operacional
Este espaço reúne os projetos práticos e relatórios desenvolvidos durante a disciplina de Pesquisa Operacional, ministrado pelo professor Carlos Eduardo Bastos no 2º semestre de Gestão de Produção Industrial (GPI).

O objetivo deste registro é consolidar o aprendizado por meio de problemas de Modelagem Linear, Programação e Aplicações​, Problemas de Transporte e Transbordo​ e a Teoria das Filas, utilizando ferramentas de mercado como Excel.

# Modelagem Linear
Para decidir entre as alternativas de solução, o decisor deverá utilizar algum procedimento/metodologia para escolher a “melhor solução” que poderá ser aplicada. 
No meio quantitativo, a metodologia aplicada e a Modelagem que e o processo de selecionar as informações que interessam para conseguir fazer a melhor escolha de acordo com a matemática.

📊 Arquivo do próprio excel, sobre esse desenvolvimento :

Vendedor e Marcenaria : [P.O , bonitinho.xlsx](https://github.com/user-attachments/files/35040988/P.O.bonitinho.xlsx)

## Vendedor de meias

📌 Aqui nos temos o problema:

"Um vendedor de meias possui:​ 84 pares de meias de lã​ e 24 pares de meias de algodão. Porém os clientes compram Kits de meias, os Kits são compostos da seguinte forma:
​

Kit A - 2 pares de meias de algodão e 4 pares de meias de lã​.

Kit B - 8 pares de meias de lã e 2 pares de meias algodão​.

A margem de lucro de cada é:​ Kit A = R$6,00​ e o Kit B = R$8,00.
​

Qual deve ser a quantidade vendida de cada Kit para gerar a maior margem de lucro?"


### 🧾 Primeiro fazemos a modelagem:
Nosso objetivo é determinar a quantidade a ser vendida de cada Kit para gerar a maior margem de lucro, considerando a quantidade disponível de cada tipo de meia.

Identifique as variáveis de decisão: 
​

A = quantidade a ser vendida do Kit A
​

B = quantidade a ser vendida do Kit B

Escreva a função objetivo (Representar o lucro por uma função linear, indicando que o objetivo é maximizar​)

Escreva as restrições (representar por uma função linear a quantidade necessária de cada tipo de meia, para atender os kits, e sua relação com a quantidade disponível de cada uma)
​
A modelagem final é:

Max: 6,00.A + 8,00.B

R1: 2.A + 2.B <= 24
​

R2: 4.A + 8.B <= 84

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="728" height="417" alt="image" src="https://github.com/user-attachments/assets/0832e898-a177-4e45-ac58-3eef83110fc9" />
MUDAR IMAGEM ;)

## Marcenaria
📌 Aqui nos temos o problema:

"Uma marcenaria deseja estabelecer uma programação diária de produção. Atualmente, são fabricados apenas dois produtos: ​

1 modelo de mesa e ​1 modelo de armário.

A empresa sabe que cada mesa dá uma margem de contribuição para o lucro de $ 4 e cada armário de $ 3.
​
A marcenaria tem limitações em dois recursos:​ Madeira utilizada e o​ tempo de mão-de-obra.

O processo de produção é tal que, para fazer uma ​ mesa, a fábrica gasta 2 m² de madeira e 2 horas de ​mão-de-obra, e para fazer um armário, a fábrica gasta 3 m² de madeira e 1 hora de mão de obra.​

Sabendo que a disponibilidade diária de recursos é: 12 m² de madeira e 8 Hh de mão de obra, qual deve ser a quantidade fabricada por dia, de cada produto, para gerar a maior margem de lucro?"

### 🧾 Primeiro fazemos a modelagem:
Determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

Identifique as variáveis de decisão:

M = quantidade a produzir de Mesa​


A = quantidade a produzir de Armário 

Escreva a função objetivo e as restrições.

A modelagem final é:

Max: 4,00.M + 3,00.A

R1: 2.M + 3.A <= 12​


R2: 2.M + 1.A <= 8

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="728" height="417" alt="image" src="https://github.com/user-attachments/assets/e382e463-85ff-4a9f-9891-ac84faad282a" />
MUDAR IMAGEM ;)
