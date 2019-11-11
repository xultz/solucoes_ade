# 1.1

R<sub>1</sub>=5k, R<sub>2</sub>=10k

a) Em série:

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;R_{1}&space;&plus;&space;R_{2}" title="R_{T} = R_{1} + R_{2}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;10&space;\cdot&space;10^3&space;&plus;&space;5&space;\cdot&space;10^3&space;=&space;15&space;\cdot&space;10^3&space;=&space;15k\Omega" title="R_{T} = 10 \cdot 10^3 + 5 \cdot 10^3 = 15 \cdot 10^3 = 15k\Omega" />

b) Em paralelo:

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;\frac&space;{R_{1}&space;\cdot&space;R_{2}}{R_{1}&space;&plus;&space;R_{2}}" title="R_{T} = \frac {R_{1} \cdot R_{2}}{R_{1} + R_{2}}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;\frac&space;{10&space;\cdot&space;10^3&space;\cdot&space;5&space;\cdot&space;10^3}{10&space;\cdot&space;10^3&space;&plus;&space;5&space;\cdot&space;10^3}&space;=&space;\frac{50&space;\cdot&space;10^6}{15&space;\cdot&space;10^3}&space;=&space;3,33&space;\cdot&space;10^3&space;=&space;3,33k&space;\Omega" title="\small R_{T} = \frac {10 \cdot 10^3 \cdot 5 \cdot 10^3}{10 \cdot 10^3 + 5 \cdot 10^3} = \frac{50 \cdot 10^6}{15 \cdot 10^3} = 3,33 \cdot 10^3 = 3,33k \Omega" />

# 1.2

<img src="./CH1/1_3.svg" width=250>
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;P&space;=&space;V&space;\cdot&space;I" title="\small P = V \cdot I" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;I&space;=&space;\frac{V}{R}&space;=&space;\frac{12}{1}&space;=&space;12A" title="\small I = \frac{V}{R} = \frac{12}{1} = 12A" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;P&space;=&space;V&space;\cdot&space;I&space;=&space;12&space;\cdot&space;12&space;=&space;144W" title="\small P = V \cdot I = 12 \cdot 12 = 144W" />

# 1.3
Eu não entendi muito bem o que o enunciado da questão pede, eu entendi que é prá deduzir as equações que permitem calcular o valor de resistência total para circuitos série e paralelo. Se for isso, então vamos lá:

## Série
Partindo de um circuito como abaixo:

<img src="./CH1/1_3a.svg" width=250>

Pela lei de Ohm, V = R.I, e R = V/I. A resistência total do circuito, que é a resistência que a fonte V1 "enxerga", é a razão tensão da fonte pela corrente total (It) do circuito.

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;\frac{V}{I_{T}}" title="\small R_{T} = \frac{V}{I_{T}}" />

Pela lei de Kirchhoff, a soma da queda de tensão nos resistores será igual à tensão da fonte.

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;V&space;=&space;V_{R1}&space;&plus;&space;V_{R2}&space;&plus;&space;V_{R3}" title="\small V = V_{R1} + V_{R2} + V_{R3}" />

Como no circuito série a corrente é a mesma em todos os componentes, podemos reescrever como sendo:

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;V&space;=&space;I_{T}&space;\cdot&space;R_{1}&space;&plus;&space;I_{T}&space;\cdot&space;R_{2}&space;&plus;&space;I_{T}&space;\cdot&space;R_{3}" title="\small V = I_{T} \cdot R_{1} + I_{T} \cdot R_{2} + I_{T} \cdot R_{3}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;V&space;=&space;I_{T}&space;\cdot&space;(&space;R_{1}&space;&plus;&space;R_{2}&space;&plus;&space;R_{3}&space;)" title="\small V = I_{T} \cdot ( R_{1} + R_{2} + R_{3} )" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;\frac{V}{I_{T}}&space;=&space;R_{1}&space;&plus;&space;R_{2}&space;&plus;&space;R_{3}" title="\small \frac{V}{I_{T}} = R_{1} + R_{2} + R_{3}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;R_{1}&space;&plus;&space;R_{2}&space;&plus;&space;R_{3}" title="\small R_{T} = R_{1} + R_{2} + R_{3}" />
