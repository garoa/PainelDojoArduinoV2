# PainelDojoArduinoV2
Painel com display 7 segmentos gigante (10cm), um potenciômetro e um 
Arduino Nano. Usado para realizar desafios de programação.

https://garoa.net.br/wiki/Coding_Dojo_com_Arduino

Os segmentos do display possuem cinco LEDs, precisando de pelo menos 9V 
para acender. É usado um display com catodo comum, o catodo está 
conectado a 12V. O catodo de cada segmento é ligado através de um 
resistor de 150 ohms a um CI ULN28003, controlado por saídas digitais do 
Arduino.

O diagrama no Fritzing (PainelDojo.fzz) foi usado para gerar a imagem no 
painel (PainelDojo.pdf), porém a pinagem do display utilizado é diferente 
do componente disponível no Fritzing. A pinagem do display está em 
D4X6_A_.pdf.

O diretório Laser Cutter tem o projeto dos cortes. Os furos não estão
100% corretos, foi usada uma lima para acertar alguns furos.

IMPORTANTE:
 
A alimentação do Arduino é pela USB, a alimentação do display é pela fonte externa.
O Arduino Nano não permite alimentação simultânea externa e pela USB

https://forum.arduino.cc/index.php?topic=462073.msg3906529#msg3906529

