# Pesquisa-Operacional
Este espaço reúne os projetos práticos e relatórios desenvolvidos durante a disciplina de Pesquisa Operacional, ministrado pelo professor Carlos Eduardo Bastos no 2º semestre de Gestão de Produção Industrial (GPI).

O objetivo deste registro é consolidar o aprendizado por meio de problemas de Modelagem Linear, Programação e Aplicações​, Problemas de Transporte e Transbordo​ e a Teoria das Filas, utilizando ferramentas de mercado como Excel.

# Modelagem Linear
Para decidir entre as alternativas de solução, o decisor deverá utilizar algum procedimento/metodologia para escolher a “melhor solução” que poderá ser aplicada. 
No meio quantitativo, a metodologia aplicada e a Modelagem que e o processo de selecionar as informações que interessam para conseguir fazer a melhor escolha de acordo com a matemática.

📊 Arquivo do próprio excel, sobre esse desenvolvimento :

📌 Vendedor e Marcenaria : [P.O , bonitinho.xlsx](https://github.com/user-attachments/files/35040988/P.O.bonitinho.xlsx)


📌 Modelo pronto e Carpinteiro : 

## Vendedor de meias

📌 Aqui nos temos o problema:

"Um vendedor de meias possui:​ 84 pares de meias de lã​ e 24 pares de meias de algodão. Porém os clientes compram Kits de meias, os Kits são compostos da seguinte forma:
​

Kit A - 2 pares de meias de algodão e 4 pares de meias de lã​.

Kit B - 8 pares de meias de lã e 2 pares de meias algodão​.

A margem de lucro de cada é:​ Kit A = R$6,00​ e o Kit B = R$8,00.
​

Qual deve ser a quantidade vendida de cada Kit para gerar a maior margem de lucro?"


### 🧾 Resolução 
O objetivo é determinar a quantidade a ser vendida de cada Kit para gerar a maior margem de lucro, considerando a quantidade disponível de cada tipo de meia.

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

Restrições:

Meias de lã: 2.A + 2.B <= 24
​

Meias de algodão: 4.A + 8.B <= 84

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

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

Identifique as variáveis de decisão:

M = quantidade a produzir de Mesa​


A = quantidade a produzir de Armário 

Escreva a função objetivo e as restrições.

A modelagem final é:

Max: 4,00.M + 3,00.A

Restrições:

Metros de madeira: 2.M + 3.A <= 12​


Horas para fabricar: 2.M + 1.A <= 8

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="728" height="417" alt="image" src="https://github.com/user-attachments/assets/e382e463-85ff-4a9f-9891-ac84faad282a" />
MUDAR IMAGEM ;)

## Modelo pronto
📌 Aqui nos temos o problema simples:

"Considere o modelo de um problema de programação linear apresentado abaixo. 

Max: 3 . A + 4 . B 

Restrições:

R1: 3 . A + 2 . B <= 15 

R2: 4 . A + 6 . B <= 30 

Determinar a solução ótima através da resolução gráfica. Qual será o lucro total?"

### 🧾 Resolução 
O objetivo é determinar o lucro, de acordo com a resolução no gráfico linear.

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="728" height="417" alt="image" src="https://github.com/user-attachments/assets/e84a2af5-22c5-448c-b522-50aa72e38cac" />
MUDAR IMAGEM ;)

De acordo com o gráfico, a resposta perfeita é: 3 A , 3 B 

Então e possível substituir a função objetiva para ter a quantia de lucro:
Max: 3 . 3 + 4 . 3 = 21 

## Carpinteiro
📌 Aqui nos temos o problema:

"Um carpinteiro dispõe de 90 metros de compensado, 80 de pinho e 50 de cedro. 

O produto A requer 2 metros de compensado, 1 de pinho e 1 de cedro. 

O produto B requer 1, 2 e 1 metros, respectivamente. 


O produto A é vendido por $120,00 e o B por $100,00. 

Quanto de cada produto ele deve fazer para obter um faturamento máximo?"

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

Identifique as variáveis de decisão:

A = Quantidade de Produto A para produzir 


B = Quantidade de Produto B para produzir 

Escreva a função objetivo e as restrições.

A modelagem final é:

Max: 120 . A + 100 . B 

Restrições:

Metros de compensado : 2 . A + 1 . B <= 90 

Metros de pinho : 1 . A + 2 . B <= 80 

Metros de cedro : 1 . A + 1 . B <= 50

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="728" height="417" alt="image" src="https://github.com/user-attachments/assets/d0288a55-a581-417e-82c2-a909c73d85b8" />
MUDAR IMAGEM ;)

Porém, esse gráfico nos dá duas "melhores soluções",

20 A , 30 B ou 40 A , 10 B 

então cabe aos cálculos decidir qual e a solução ótima.

120 . 20 + 100 . 30 = 5.400 

120 . 40 + 100 . 10 = 5. 800 ( corresponde as restrições) 

Logo; 40 A , 10 B e a solução ótima. 
