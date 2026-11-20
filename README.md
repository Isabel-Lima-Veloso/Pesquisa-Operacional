# Pesquisa-Operacional
Este espaço reúne os projetos práticos e relatórios desenvolvidos durante a disciplina de Pesquisa Operacional, ministrado pelo professor Carlos Eduardo Bastos no 2º semestre de Gestão de Produção Industrial (GPI).

O objetivo deste registro é consolidar o aprendizado por meio de problemas de Modelagem Linear, Programação e Aplicações​, Problemas de Transporte e Transbordo​ e a Teoria das Filas, utilizando ferramentas de mercado como Excel.

# Modelagem Linear e Gráfico 
Para decidir entre <u> poucas alternativas de solução </u> , o decisor deverá utilizar algum procedimento/metodologia para escolher a “melhor solução” que poderá ser aplicada. 

No meio quantitativo, a metodologia aplicada quando tem poucas alternativas e a Modelagem que e o processo de selecionar as informações que interessam para conseguir fazer a melhor escolha de acordo com a matemática, juntamente da criação de um Gráfico para achar a região viável e então a “melhor solução”.

📊 Arquivo do próprio excel, sobre esse desenvolvimento :

📌 Problemas com resoluções : [P.O.xlsx](https://github.com/user-attachments/files/35112139/P.O.xlsx) [aa. xlsx..xlsx](https://github.com/user-attachments/files/35112544/aa.xlsx.xlsx)

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

📌 Problemas com resoluções : [Pesquisa Operacional.xlsx](https://github.com/user-attachments/files/35112917/Pesquisa.Operacional.xlsx)

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

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA":

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

<sub> X = Quantidade de Caminhão A para alugar


<sub> Y = Quantidade de Caminhão B para alugar

<sub> Escreva a função objetivo e as restrições.

A modelagem final é:
	
MIN (custo) = 0,30 . A + 0,40 + B	
	
Restrições:	

Espaco Não.Refrigerado =	4 . A + 3 . B >= 120

Espaco Refrigerado =	2 . A + 3 . B >= 90

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA", e utilizamos o Solver para encontrar a “melhor solução”: 

<img width="361" height="385" alt="image" src="https://github.com/user-attachments/assets/1a596805-257e-4191-a9b9-0db5b36dd177" />

Resultado:

<img width="436" height="160" alt="image" src="https://github.com/user-attachments/assets/b502e5a9-2cec-46a9-8e7e-80f2ea497e65" />

# Programação de designação 
Suponha que existam “n” recursos/agentes disponíveis para realizar “n” atividades/tarefas e que os agentes tenham habilidades ou capacidades diferentes e mensuráveis para cada uma das tarefas. O objetivo aqui e determinar para cada agente o que fazer, de forma a otimizar a capacidade total do grupo, os custos ou o retorno financeiro associados.

📊 Arquivo do próprio excel, sobre esse desenvolvimento : 

📌 Problemas com resoluções : [Problema de Distribuicao.xlsx](https://github.com/user-attachments/files/35127937/Problema.de.Distribuicao.xlsx)

## Problema simples

📌 Aqui nos temos o problema: 
<sub> "Uma empresa possui 4 gerentes disponíveis para liderar 4 projetos. Estima-se que cada gerente conseguiria trazer um retorno financeiro diferente para cada projeto, em função de seus conhecimentos e habilidades, conforme a tabela a seguir (valores em $1.000).​

<sub> Qual gerente deve liderar qual projeto para obter o maior retorno financeiro para a empresa? Qual será o retorno total obtido?"

| Gerentes | Projeto 1 | Projeto 2 | Projeto 3 | Projeto 4 |
|----------|----------:|----------:|----------:|----------:|
| Paula    | 13 | 12 | 17 | 32 |
| Rafaela  | 9  | 7  | 10 | 19 |
| Mônica   | 11 | 9  | 10 | 26 |
| Gabriela | 7  | 8  | 9  | 24 |

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA":

<img width="1194" height="262" alt="image" src="https://github.com/user-attachments/assets/b058e5ac-7dc3-4571-9cad-289c5b82ecd8" />

E utilizamos o Solver para encontrar a “melhor solução”: 

COLOCAR IMAGEM !!!!

Resultado:

<img width="1194" height="259" alt="image" src="https://github.com/user-attachments/assets/aecb3a85-88b0-49c9-a693-76ec7f54ae64" />

## Problema de designação desequilibrado
Trata da distribuição de tarefas a agentes. É um caso especial do Problema de Transporte com oferta e demanda unitárias.​

Suponha que existam “n” agentes disponíveis para realizar “m” atividades, ou seja, há diferença entre o número de agentes e o número de atividades a realizar. 
​
Nesse caso, para otimizar, será necessário que usemos desigualdade nas restrições.
​
Se houver mais atividades do que agentes, um agente realizará mais de uma atividade. Assim as restrições de agentes serão maior ou igual (>=).
​
Se houver mais agentes do que atividades, as restrições de agentes serão menor ou igual (<=), pois haverá agente ocioso.

📌 Aqui nos temos o problema: 

<sub> "Existem 3 máquinas para processar 4 ordens de produção. Todas as máquinas podem processar qualquer ordem, mas com diferentes custos e tempos de execução, conforme tabelas abaixo.

| Custos ($) | OP 1 | OP2 | OP3 | OP4 | 
|------------:|------:|-----:|-----:|-----:| 
| M1 | 15 | 61 | 33 | 94 | 
| M2 | 21 | 58 | 40 | 86 | 
| M3 | 19 | 68 | 27 | 90 | 


| Tempos (min.) | OP 1 | OP2 | OP3 | OP4 | 
|---------------:|------:|-----:|-----:|-----:| 
| M1 | 32 | 57 | 17 | 56 | 
| M2 | 27 | 50 | 22 | 48 | 
| M3 | 18 | 45 | 13 | 60 |

<sub> Sabendo que as máquinas podem trabalhar ao mesmo tempo e todas as ordens de produção devem ser realizadas em até 120 minutos, como as OPs devem ser distribuídas nas máquinas de modo a minimizar o custo total? "

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA":

<img width="839" height="205" alt="image" src="https://github.com/user-attachments/assets/24da0c6f-924a-4512-b165-3c71096bb5b8" />

E utilizamos o Solver para encontrar a “melhor solução”: 

COLOCAR IMAGEM !!!!

Resultado:

<img width="841" height="209" alt="image" src="https://github.com/user-attachments/assets/74e99d61-3fd6-45bb-9981-541d3163b9df" />

# Método de Transporte 
Um problema bastante comum que muitas vezes pode ser modelado como um problema de programação linear é o problema de transporte. ​Este problema envolve o transporte de alguma carga de diversas fontes a diversos pontos de destino. ​

Dados o custo da distribuição entre cada fonte e destino, as produções das fontes e as capacidades dos destinos, pretende-se minimizar o custo total do transporte.

📊 Arquivo do próprio excel, sobre esse desenvolvimento : 

📌 Problemas com resoluções : [P.O, Metodo de Transporte com problema 2.xlsx](https://github.com/user-attachments/files/35129007/P.O.Metodo.de.Transporte.com.problema.2.xlsx)  [P.O, Metodo de transporte 1,3.xlsx](https://github.com/user-attachments/files/35129005/P.O.Metodo.de.transporte.1.3.xlsx)

## Problema moodelo
📌 Aqui nos temos o problema:

<sub> "Com a informação que a Capacidade e a Demanda e igual a 40 toneladas, e com base na imagem abaixo:

<img width="494" height="299" alt="image" src="https://github.com/user-attachments/assets/1426c753-6969-4c7b-b12a-ed2d82535fc4" />

<sub> E com base na tabela:

| Custo | Destino 1 | Destino 2 | Destino 3 |
|---------------:|------:|-----:|-----:|
| Fonte 1 | 10 | 3 | 5 |
| Fonte 2 | 12 | 7 | 9 | 

<sub> Ache a solução perfeita com maior lucro, minimizando custos."

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA":

<img width="634" height="237" alt="image" src="https://github.com/user-attachments/assets/3a2a512c-b8f3-4a40-b1e5-92c54f0e5578" />

E utilizamos o Solver para encontrar a “melhor solução”: 

COLOCAR IMAGEM !!!!

Resultado:

<img width="636" height="241" alt="image" src="https://github.com/user-attachments/assets/470485a3-6db9-464c-8668-004f0969befa" />

## Prefeitura

📌 Aqui nos temos o problema:

<sub> "A prefeitura de uma cidade está fazendo obras em três bairros. O material para essas obras é transportado de três depósitos 01, 02 e 03 de onde são retiradas 57, 76 e 93 toneladas de material, respectivamente. As obras são destinadas para os bairros D1, D2 e D3, que necessitam diariamente de 41, 80 e 105 toneladas, respectivamente. Os custos unitários para o transporte desse material estão na tabela a seguir. Determinar quanto cada depósito deve enviar para cada bairro de forma a minimizar o custo de transporte. "

| Custo | Destino 1 | Destino 2 | Destino 3 |
|---------------:|------:|-----:|-----:|
| Depósito 1 | 7 | 8 | 4 |
| Depósito 2 | 5 | 6 | 3 |
| Depósito 3 | 6 | 5 | 4 |

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA":

<img width="841" height="260" alt="image" src="https://github.com/user-attachments/assets/415afebf-7c88-44b0-9910-dfacd069d3eb" />

E utilizamos o Solver para encontrar a “melhor solução”: 

COLOCAR IMAGEM !!!!

Resultado:

<img width="844" height="259" alt="image" src="https://github.com/user-attachments/assets/00a45b4e-3ec6-4ed1-8b68-b8ccadf6320e" />

## Grande empresa

📌 Aqui nos temos o problema:

<sub> "Uma grande empresa industrial possui cinco filiais e três CDs. Os custos, a capacidade de produção e a demanda dos CDs encontram-se nas tabelas a seguir. A diretoria deseja saber como abastecer os CDs de modo a minimizar o custo total de transporte."

| Fábricas | CD1 | CD2 | CD3 |
|---------------:|------:|-----:|-----:|
| Fábrica 1 | 90 | 62 | 76 |
| Fábrica 2 | 82 | 58 | 70 |
| Fábrica 3 | 92 | 64 | 80 |
| Fábrica 4 | 84 | 56 | -X- |
| Fábrica 5 | 86 | 58 | -X- |

| Fábricas | Quantia | 
|---------------:|------:|
| Fábrica 1 | 2000 |
| Fábrica 2 | 3000 |
| Fábrica 3 | 2000 |
| Fábrica 4 | 3000 |
| Fábrica 5 | 5000 |

| Demanda | Quantia | 
|---------------:|------:|
| CD1 | 5000 |
| CD2 | 3000 |
| CD3| 2=4000 |

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA":

<img width="1021" height="282" alt="image" src="https://github.com/user-attachments/assets/ede0dcec-0f10-4420-b17d-cb911209a26d" />

E utilizamos o Solver para encontrar a “melhor solução”: 

COLOCAR IMAGEM !!!!

Resultado:

<img width="1018" height="281" alt="image" src="https://github.com/user-attachments/assets/844eca23-e168-419e-98f7-6d5e1ff06de1" />

## Problema de Distribuição no transporte
Na questão do transporte é necessário transbordo (a quantidade transportada de cada unidade de transbordo aos mercados consumidores deve ser igual à quantidade que chega à mesma vindo dos centros de produção)

📌 Aqui nos temos o problema:

<sub> "Considere uma empresa de bebidas com 2 centros de produção - Araraquara e S. José dos Campos, com um suprimento de 800 e 1 000 unidades, respectivamente, e 3 mercados consumidores – S. Paulo, Belo Horizonte e Rio de Janeiro, com demandas respectivas de 500, 400 e 900 unidades. ​

<sub> A empresa dispõe de 2 depósitos para abastecer tais mercados, localizados em Campinas e Barra Mansa. Suponha que os mercados sejam abastecidos somente a partir de tais depósitos. ​

<sub> Os custos unitários de transporte de cada centro de produção para cada depósito, e de cada depósito para cada mercado consumidor é dado pelas tabelas que seguem.

<sub> Custo do centro de suprimento para os depósitos

| Depósitos | Campinas | Barra Mansa |
|---------------:|------:|-----:|
| Araraquara | 1 | 3 |
| S. José dos Campos | 1 | 2 |


<sub> Custo dos depósitos até os mercados

| Depósitos | São Paulo | B. Horizonte | R. Janeiro |
|---------------:|------:|-----:|-----:|
| Campinas | 1 | 3 | 3 |
| Barra Mansa | 3 | 4 | 1 |

### 🧾 Resolução 
O objetivo é determinar a quantidade a produzir de cada produto para gerar a maior margem de lucro, considerando a quantidade disponível de cada recurso.

📊 Aplicando ela para o Excel, nos fazemos uma planilha estruturada usando formulas de "SOMARPRODUTO" e "SOMA":

<img width="839" height="247" alt="image" src="https://github.com/user-attachments/assets/8179b0a2-b7f5-45e8-a023-9f5d845a1916" />

E utilizamos o Solver para encontrar a “melhor solução”: 

COLOCAR IMAGEM !!!!

Resultado:

<img width="840" height="244" alt="image" src="https://github.com/user-attachments/assets/b244bc53-6937-4c68-a5f4-c0cc72785cab" />
