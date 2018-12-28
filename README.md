# PainelDojoArduinoV2
Painel com display 7 segmentos gigante (10cm), um potenciômetro e um 
Arduino Nano. Usado para realizar desafios de programação.

https://garoa.net.br/wiki/Coding_Dojo_com_Arduino

Os segmentos do display possuem cinco LEDs, precisando de pelo menos 9V 
para acender. É usado um display com catodo comum, o catodo está 
conectado a 12V. O catodo de cada segmento é ligado através de um 
resistor de 150 ohms a um CI ULN28003, controlado por saídas digitais do 
Arduino.

O diagrama no Fritzing foi usado para gerar a imagem no painel, porém a 
pinagem do display utilizado é diferente do componente disponível no 
Fritzing.
