# Torta na cara 🥧
Este projeto é uma brincadeira interativa onde dois jogadores competem para apertar um botão primeiro. Quem perder recebe uma torta na cara. O sistema usa Arduino para identificar o primeiro botão pressionado, acender LEDs e tocar um buzzer para indicar o vencedor.

# Como Funciona

Dois jogadores têm botões grandes estilo fliperama.

Quem apertar o botão primeiro ganha e tem o LED aceso ao seu lado.

Um buzzer toca para indicar o vencedor.

O botão do perdedor fica desabilitado para evitar empate.

# Componentes Utilizados

Arduino Uno 

2x Botões grandes estilo fliperama

1x LED RGB

2x LEDs

Buzzer para sinal sonoro

Resistores, jumpers e protoboard

# Código

O código em C++ para Arduino gerencia a leitura dos botões, o acionamento dos LEDs e do buzzer, além de bloquear o segundo botão após o primeiro ser pressionado.
