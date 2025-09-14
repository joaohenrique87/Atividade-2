🩺 Análise de Fatores de Custo do Plano de Saúde
Este projeto realiza uma análise investigativa para determinar os fatores mais relevantes que influenciam o custo do plano de saúde de um indivíduo. A análise é baseada em um conjunto de dados demográficos e de saúde.

📄 O Dataset
O estudo utilizou um dataset com informações de 

1338 indivíduos. As variáveis consideradas para cada pessoa foram:

Idade 

Sexo 

IMC (Índice de Massa Corporal) 

Número de filhos 

Hábito de fumar (sim/não) 

Região de residência nos EUA 

🤔 Pergunta Central da Análise
O objetivo principal deste projeto é responder à seguinte questão:

Quais questões são mais relevantes na hora de ser calculado o custo do plano de saúde? 

📝 Hipóteses
Para guiar a análise, foram formuladas três hipóteses principais:


H 
1
​
 : Pessoas que fumam pagam mais caro pelo plano de saúde. 


H 
2
​
 : Quanto maior o IMC do cliente, maior será o valor do plano de saúde. 


H 
3
​
 : Quanto maior a idade, maior o valor do plano. 

📊 Experimento e Resultados
Cada hipótese foi testada por meio de uma análise estatística.

H1: A Influência do Hábito de Fumar
A análise revelou uma diferença drástica nos custos para fumantes em comparação com não fumantes.

A média de valor do plano para 

fumantes foi de $32.050,32.

A média de valor do plano para não fumantes foi de $8.434,26 [cite: -1].

Um Teste T (T-Test) foi aplicado e resultou em um valor-p de 

p < 2.2e-16, o que indica uma evidência estatística muito forte da relação entre fumar e o custo do plano.

H2: A Relação com o IMC
A relação entre o Índice de Massa Corporal e o custo foi avaliada usando a correlação de Pearson.

O resultado da correlação foi de 

0.198.

Sendo um valor positivo, ele confirma que as variáveis são 

diretamente proporcionais, ou seja, um IMC maior tende a estar associado a um custo maior.

H3: A Relação com a Idade
Assim como o IMC, a idade também demonstrou uma correlação positiva com o valor do plano.

A correlação de Pearson entre idade e custo foi de 

0.299.

Este valor indica que a idade tem uma relação diretamente proporcional com o custo e é um fator 

mais relevante que o IMC para o cálculo do valor.

💡 Conclusão
A análise confirmou todas as três hipóteses levantadas.

De fato, pessoas 

fumantes, com IMC mais alto e mais velhas pagam um plano de saúde mais caro.

A ordem de influência dos fatores analisados é a seguinte:


Hábito de Fumar (fator mais inferente) 


Idade 


IMC 

Portanto, ser fumante é a característica individual que mais impacta no aumento do custo de um plano de saúde, seguida pela idade e pelo IMC.
