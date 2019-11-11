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

## a) Série
Partindo de um circuito como abaixo:

<img src="./CH1/1_3a.svg" width=250>

Pela lei de Ohm, V = R.I, e R = V/I. A resistência total do circuito, que é a resistência que a fonte V1 "enxerga", é a razão da tensão da fonte pela corrente total (It) do circuito.

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;\frac{V}{I_{T}}" title="\small R_{T} = \frac{V}{I_{T}}" />

Pela lei de Kirchhoff, a soma da queda de tensão nos resistores será igual à tensão da fonte.

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;V&space;=&space;V_{R1}&space;&plus;&space;V_{R2}&space;&plus;&space;V_{R3}" title="\small V = V_{R1} + V_{R2} + V_{R3}" />

Como no circuito série a corrente é a mesma em todos os componentes, podemos reescrever como sendo:

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;V&space;=&space;I_{T}&space;\cdot&space;R_{1}&space;&plus;&space;I_{T}&space;\cdot&space;R_{2}&space;&plus;&space;I_{T}&space;\cdot&space;R_{3}" title="\small V = I_{T} \cdot R_{1} + I_{T} \cdot R_{2} + I_{T} \cdot R_{3}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;V&space;=&space;I_{T}&space;\cdot&space;(&space;R_{1}&space;&plus;&space;R_{2}&space;&plus;&space;R_{3}&space;)" title="\small V = I_{T} \cdot ( R_{1} + R_{2} + R_{3} )" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;\frac{V}{I_{T}}&space;=&space;R_{1}&space;&plus;&space;R_{2}&space;&plus;&space;R_{3}" title="\small \frac{V}{I_{T}} = R_{1} + R_{2} + R_{3}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;R_{1}&space;&plus;&space;R_{2}&space;&plus;&space;R_{3}" title="\small R_{T} = R_{1} + R_{2} + R_{3}" />

## b) Paralelo

Partindo do circuito abaixo:

<img src="./CH1/1_3b.svg" width=450>

Neste caso, a tensão em todos os resistores será igual, que é a tensão da fonte V. A corrente It será a soma das correntes nos resistores:

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;I_{T}&space;=&space;I_{R1}&space;&plus;&space;I_{R2}&space;&plus;&space;I_{R3}" title="\small I_{T} = I_{R1} + I_{R2} + I_{R3}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;I_{T}&space;=&space;\frac{V}{R_{1}}&space;&plus;&space;\frac{V}{R_{2}}&space;&plus;&space;\frac{V}{R_{3}}" title="\small I_{T} = \frac{V}{R_{1}} + \frac{V}{R_{2}} + \frac{V}{R_{3}}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;I_{T}&space;=&space;V&space;\cdot&space;(&space;\frac{1}{R_{1}}&space;&plus;&space;\frac{1}{R_{2}}&space;&plus;&space;\frac{1}{R_{3}}&space;)" title="\small I_{T} = V \cdot ( \frac{1}{R_{1}} + \frac{1}{R_{2}} + \frac{1}{R_{3}} )" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;\frac{I_{T}}{V}&space;=&space;\frac{1}{R_{1}}&space;&plus;&space;\frac{1}{R_{2}}&space;&plus;&space;\frac{1}{R_{3}}" title="\small \frac{I_{T}}{V} = \frac{1}{R_{1}} + \frac{1}{R_{2}} + \frac{1}{R_{3}}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;\frac{V}{I_{T}}&space;=&space;\frac{1}{\frac{1}{R_{1}}&space;&plus;&space;\frac{1}{R_{2}}&space;&plus;&space;\frac{1}{R_{3}}}" title="\small \frac{V}{I_{T}} = \frac{1}{\frac{1}{R_{1}} + \frac{1}{R_{2}} + \frac{1}{R_{3}}}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;R_{T}&space;=&space;\frac{1}{\frac{1}{R_{1}}&space;&plus;&space;\frac{1}{R_{2}}&space;&plus;&space;\frac{1}{R_{3}}}" title="\small R_{T} = \frac{1}{\frac{1}{R_{1}} + \frac{1}{R_{2}} + \frac{1}{R_{3}}}" />

# 1.4
Pelo jeito ele pediu para fazer o que fiz em 1.3 b, então sei lá...

# 1.5

Dados: R=1k com 0,25W de potência máxima.
Ao conectar numa fonte de 15V, a potência dissipada será:

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;P&space;=&space;\frac{V^2}{R}" title="\small P = \frac{V^2}{R}" />
<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;P&space;=&space;\frac{15^2}{1&space;\cdot&space;10^3}&space;=&space;0,225W" title="\small P = \frac{15^2}{1 \cdot 10^3} = 0,225W" />

Se conectar um resistor em série com este resistor, a corrente será menor, consequentemente a potência será menor. Se conectar em paralelo, a tensão e corrente sobre o resistor continuará igual. Desta maneira, não é possível fazer com que a potência dissipada sobre o resistor seja maior que 0,225W, tendo uma única fonte de 15V.

# 1.6

Para a potência e tensão informados, a corrente será de:

<img src="https://latex.codecogs.com/svg.latex?\fn_jvn&space;\small&space;I&space;=&space;\frac{P}{V}&space;=&space;\frac{10^{10}}{115}&space;=&space;86,957&space;\cdot&space;10^6&space;A" title="\small I = \frac{P}{V} = \frac{10^{10}}{115} = 86,957 \cdot 10^6 A" />
a)
