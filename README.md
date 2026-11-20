# Pesquisa-Operacional
Este espaço reúne os projetos práticos e relatórios desenvolvidos durante a disciplina de Pesquisa Operacional, ministrado pelo professor Carlos Eduardo Bastos no 2º semestre de Gestão de Produção Industrial (GPI).

O objetivo deste registro é consolidar o aprendizado por meio de problemas de Modelagem Linear, Programação e Aplicações​, Problemas de Transporte e Transbordo​ e a Teoria das Filas, utilizando ferramentas de mercado como Excel.

# Modelagem Linear e Gráfico 
Para decidir entre <u> poucas alternativas de solução </u> , o decisor deverá utilizar algum procedimento/metodologia para escolher a “melhor solução” que poderá ser aplicada. 

No meio quantitativo, a metodologia aplicada quando tem poucas alternativas e a Modelagem que e o processo de selecionar as informações que interessam para conseguir fazer a melhor escolha de acordo com a matemática, juntamente da criação de um Gráfico para achar a região viável e então a “melhor solução”.

📊 Arquivo do próprio excel, sobre esse desenvolvimento :

📌 Vendedor e Marcenaria : [P.O.xlsx](https://github.com/user-attachments/files/35112139/P.O.xlsx)


📌 Modelo pronto e Carpinteiro : [aa. xlsx..xlsx](https://github.com/user-attachments/files/35112544/aa.xlsx.xlsx)

## Vendedor de meias

📌 Aqui nos temos o problema:

<sub> "Um vendedor de meias possui:​ 84 pares de meias de lã​ e 24 pares de meias de algodão. Porém os clientes compram Kits de meias, os Kits são compostos da seguinte forma:
​

<sub> Kit A - 2 pares de meias de algodão e 4 pares de meias de lã​.

<sub> Kit B - 8 pares de meias de lã e 2 pares de meias algodão​.

<sub> A margem de lucro de cada é:​ Kit A = R$6,00​ e o Kit B = R$8,00.
​

<sub> Qual deve ser a quantidade vendida de cada Kit para gerar a maior margem de lucro?"


### 🧾 Resolução 
O objetivo é determinar a quantidade a ser vendida de cada Kit para gerar a maior margem de lucro, considerando a quantidade disponível de cada tipo de meia.

<sub> Identifique as variáveis de decisão: 
​

<sub> A = quantidade a ser vendida do Kit A
​

<sub> B = quantidade a ser vendida do Kit B

<sub> Escreva a função objetivo (Representar o lucro por uma função linear, indicando que o objetivo é maximizar​)

<sub> Escreva as restrições (representar por uma função linear a quantidade necessária de cada tipo de meia, para atender os kits, e sua relação com a quantidade disponível de cada uma)
​

A modelagem final é:

Max: 6,00.A + 8,00.B

Restrições:

Meias de lã: 2.A + 2.B <= 24
​

Meias de algodão: 4.A + 8.B <= 84

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="677" height="445" alt="image" src="https://github.com/user-attachments/assets/0de76b45-ffe6-4dd2-affd-f5491218246b" />

## Marcenaria
📌 Aqui nos temos o problema:

<sub> "Uma marcenaria deseja estabelecer uma programação diária de produção. Atualmente, são fabricados apenas dois produtos: ​

<sub> 1 modelo de mesa e ​1 modelo de armário.

<sub> A empresa sabe que cada mesa dá uma margem de contribuição para o lucro de $ 4 e cada armário de $ 3.
​
<sub> A marcenaria tem limitações em dois recursos:​ Madeira utilizada e o​ tempo de mão-de-obra.

<sub> O processo de produção é tal que, para fazer uma ​ mesa, a fábrica gasta 2 m² de madeira e 2 horas de ​mão-de-obra, e para fazer um armário, a fábrica gasta 3 m² de madeira e 1 hora de mão de obra.​

<sub> Sabendo que a disponibilidade diária de recursos é: 12 m² de madeira e 8 Hh de mão de obra, qual deve ser a quantidade fabricada por dia, de cada produto, para gerar a maior margem de lucro?"

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

<sub> Identifique as variáveis de decisão:

<sub> M = quantidade a produzir de Mesa​


<sub> A = quantidade a produzir de Armário 

<sub> Escreva a função objetivo e as restrições.


A modelagem final é:

Max: 4,00.M + 3,00.A

Restrições:

Metros de madeira: 2.M + 3.A <= 12​


Horas para fabricar: 2.M + 1.A <= 8

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="680" height="460" alt="image" src="https://github.com/user-attachments/assets/259bad5d-f4cf-4bed-9451-43404179fa32" />

## Modelo pronto
📌 Aqui nos temos o problema simples:

<sub> "Considere o modelo de um problema de programação linear apresentado abaixo. 

Max: 3 . A + 4 . B 

Restrições:

R1: 3 . A + 2 . B <= 15 

R2: 4 . A + 6 . B <= 30 

<sub> Determinar a solução ótima através da resolução gráfica. Qual será o lucro total?"

### 🧾 Resolução 
O objetivo é determinar o lucro, de acordo com a resolução no gráfico linear.

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="491" height="215" alt="image" src="https://github.com/user-attachments/assets/c14d3f9e-17f0-40f5-b497-1f7a97c66d7c" />

De acordo com o gráfico, a resposta perfeita é: 3 A , 3 B 

Então e possível substituir a função objetiva para ter a quantia de lucro:
Max: 3 . 3 + 4 . 3 = 21 

## Carpinteiro
📌 Aqui nos temos o problema:

<sub> "Um carpinteiro dispõe de 90 metros de compensado, 80 de pinho e 50 de cedro. 

<sub> O produto A requer 2 metros de compensado, 1 de pinho e 1 de cedro. 

<sub> O produto B requer 1, 2 e 1 metros, respectivamente. 


<sub> O produto A é vendido por $120,00 e o B por $100,00. 

<sub> Quanto de cada produto ele deve fazer para obter um faturamento máximo?"

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

<sub> Identifique as variáveis de decisão:

<sub> A = Quantidade de Produto A para produzir 


<sub> B = Quantidade de Produto B para produzir 

<sub> Escreva a função objetivo e as restrições.


A modelagem final é:

Max: 120 . A + 100 . B 

Restrições:

Metros de compensado : 2 . A + 1 . B <= 90 

Metros de pinho : 1 . A + 2 . B <= 80 

Metros de cedro : 1 . A + 1 . B <= 50

📊 Aplicando ela para o Excel, nos fazemos uma tabela de possibilidades e um gráfico linear, onde as linhas se conectam e a “melhor solução” :
<img width="496" height="288" alt="image" src="https://github.com/user-attachments/assets/172ac2df-3efb-41cd-a259-8effe5698c1a" />

Porém, esse gráfico nos dá duas "melhores soluções",

<sub> 20 A , 30 B ou 40 A , 10 B 

<sub> então cabe aos cálculos decidir qual e a solução ótima.

<sub> 120 . 20 + 100 . 30 = 5.400 

<sub> 120 . 40 + 100 . 10 = 5. 800 ( corresponde as restrições) 

Logo; 40 A , 10 B e a solução ótima. 

# Programação Linear
Para decidir entre <u> diversas alternativas de solução </u> , o decisor deverá utilizar algum procedimento/metodologia para escolher a “melhor solução” que poderá ser aplicada. 

No meio quantitativo, a metodologia aplicada quando há diversas alternativas e o processo de Modelagem e a utilização de ferramentas, no nosso caso o Solver, que de acordo com as informações da Modelagem irá oferecer a “melhor solução”.

📊 Arquivo do próprio excel, sobre esse desenvolvimento : 

📌 Alfaiate e Caminhões: [Pesquisa Operacional.xlsx](https://github.com/user-attachments/files/35112917/Pesquisa.Operacional.xlsx)

## Alfaiate
📌 Aqui nos temos o problema: 

<sub> "Um alfaiate tem disponível os seguintes tecidos: 16 metros de algodão, 11 metros de seda e 15 metros de lã. 

<sub> Para fazer um terno são necessários 2 metros de algodão, 1 metro de seda e 1 metro de lã. 

<sub> Para fazer um vestido, são necessários 1 metro de algodão, 2 metros de seda e 3 metros de lã. 

<sub> Se um terno é vendido por $300,00 e um vestido por $500,00, quantas peças de cada tipo o alfaiate deve fazer, de modo a maximizar o seu lucro?"

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

<sub> Identifique as variáveis de decisão:

<sub> X = Quantidade de Terno para produzir


<sub> Y = Quantidade de Vestido para produzir 

<sub> Escreva a função objetivo e as restrições.


A modelagem final é:


MAX (lucro) = 300 . X + 500 . Y	
	
Restrições:

Algodao  =	2 . X + 1 . Y <= 16

Seda =	1 . X + 2 . Y <= 11

La = 	1 . X + 3 . Y <= 15

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada:

<img width="376" height="181" alt="image" src="https://github.com/user-attachments/assets/325b38b5-a433-4922-9611-47be14768a3c" />

E utilizamos o Solver para encontrar a “melhor solução”: 

<img width="357" height="386" alt="image" src="https://github.com/user-attachments/assets/ff903104-84e0-4b8f-8d56-0420aa1be4de" />

Resultado:

<img width="374" height="180" alt="image" src="https://github.com/user-attachments/assets/eebcb439-4bb5-4e70-b971-fcafb986ca40" />

## Caminhões
📌 Aqui nos temos o problema: 
<sub> "Uma companhia de aluguel de caminhões possui dois tipos de veículos: o tipo A com 2 metros cúbicos de espaço refrigerado e 4 metros cúbicos de espaço não refrigerado e o tipo B com 3 metros cúbicos refrigerados e 3 metros cúbicos não refrigerados.

<sub> Uma fábrica precisa transportar no mínimo 90 metros cúbicos de produto refrigerado e 120 metros cúbicos de produto não refrigerado.

<sub> Quantos caminhões de cada tipo ela deve alugar, de modo a minimizar o custo, se o aluguel do caminhão A era $0,30 por km e o do B, $0,40 por km. 

<sub> Elabore o modelo de programação linear e resolva pelo Solver."

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

<sub> Identifique as variáveis de decisão:

<sub> X = Quantidade de Terno para produzir


<sub> Y = Quantidade de Vestido para produzir 

<sub> Escreva a função objetivo e as restrições.


A modelagem final é:


📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada e utilizamos o Solver para encontrar a “melhor solução”: 

<img width="361" height="385" alt="image" src="https://github.com/user-attachments/assets/1a596805-257e-4191-a9b9-0db5b36dd177" />

Resultado:

<img width="436" height="160" alt="image" src="https://github.com/user-attachments/assets/b502e5a9-2cec-46a9-8e7e-80f2ea497e65" />


