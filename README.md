Bruno Rocca
Diogo Nunes
Rodrigo Trajano
Victor Kelven

##IQA: Índice de Qualidade da água
###Introdução
Foi proposto criar um programa que conseguisse calcular o índice de qualidade da água a partir de 9 parâmetros, sendo eles:  Coliformes Fecais, Potencial Hidrogeniônico (pH), Demanda Bioquímica de Oxigênio (DBO), Nitrato Total, Fosfato Total, Turbidez, Sólidos Totais e Variação de Temperatura.
###Como funciona:
Para cada parâmetro foi utilizado uma fórmula diferente para a obtenção da qualidade só levando em consideração um parâmetro ainda ,determina-se a qualidade desse parâmetro em um valor de 0 a 100.
Após obter a qualidade dos 9 parâmetros, o programa faz um produtório que visa obter a qualidade geral da agua, obtendo a média. Cada parâmetro possui um peso diferente no produtório, que serão explícitos a seguir junto com as fórmulas utilizadas. Foi utilizado a estação de tratamento de Água Morro Redondo em Belo Horizonte como base para argumentos que foram necessários em alguns parâmetros.

###Fórmulas Utilizadas:
Para cada parâmetro foi utilizada uma formula diferente para a obtenção da qualidade:
#####Coliformes Fecais:
Também são chamados de Coliformes Termotolerantes. A fórmula utilizada foi a seguinte:
![](http://oi68.tinypic.com/2rdbzeo.jpg)
O peso deste parâmetro é de 0,15.

#####Potencial Hidrogênionico:
Mais conhecido por sua sigla pH. A fórmula utilizada foi a seguinte:
![](http://oi68.tinypic.com/11sijjr.jpg)
O peso deste parâmetro é de 0,12.

#####Demanda Bioquímica de Oxigênio:
Mais conhecido por sua sigla DBO. A fórmula utilizada foi a seguinte:
![](http://oi68.tinypic.com/20l08l2.jpg)
O peso deste parâmetro é de 0,10.

#####Nitrato Total:
A fórmula química de Nitrato é NO<sub>3</sub> . Foi utilizado a seguinte fórmula:
![](http://oi65.tinypic.com/2mo2ws2.jpg)
O peso deste parâmetro é de 0,10.

#####Fosfato Total:
A fórmula química de Fostato é PO<sub>4</sub>. Foi utilizado a seguinte fórmula:
![](http://oi65.tinypic.com/33az1h4.jpg)
O peso deste parâmetro é de 0,10.

#####Turbidez:
Foi utilizado a seguinte fórmula para calcular o parâmetro qualidade da Turbidez:
![](http://oi63.tinypic.com/332b08z.jpg)
O peso deste parâmetro é de 0,08.

#####Sólidos Totais:
Foi utilizado a seguinte fórmula para calcular o parâmetro qualidade dos Sólidos Totais:
![](http://oi65.tinypic.com/1y7peo.jpg)
O peso deste parâmetro é de 0,08.

#####Variação de Temperatura:
A variação de temperatura tem muita importância para lugares como os EUA, porém no Brasil consideramos a variação de temperatura das águas como praticamente nula, então quando se trata deste parâmetro, fazemos dele uma constante, então a qualidade é 93. O peso é de 0,10.
A formula para chegar na constante foi a seguinte:
![](http://oi66.tinypic.com/2iiakgj.jpg)

#####Oxigênio Dissolvido:
A entrada referente a este parâmetro é em mg/L de Oxigênio Dissolvido, e neste parâmetro foi necessário utilizar a estação de tratamento Água Morro Redondo, pois necessitava-se de argumentos como por exemplo altitude. A fórmula utilizada foi a seguinte:
![](http://oi63.tinypic.com/2dgkm0i.jpg)
O peso deste parâmetro é de 0,17.

###Produtório Ponderado
Para calcular a média das qualidades obtidas de cada parâmetro foi utilizado um produtório ponderado, que será demonstrado a seguir:
![](http://oi67.tinypic.com/28whwxt.jpg)
sendo **IQA** o resultado da qualidade da água final, **i** sendo referente ao número do parâmetro,  **q** a qualidade do parâmetro e **w** o peso do parâmetro.
Define-se o nível de IQA da água através dessa tabela:
![](http://oi65.tinypic.com/33to0oj.jpg)

