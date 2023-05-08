# Projeto de Monitoramento de Ambiente com Arduino

Esse projeto utiliza um Arduino para monitorar a temperatura, umidade e luminosidade do ambiente. As informações coletadas são exibidas em um display LCD e um buzzer é utilizado para alertar quando os valores estão fora do intervalo ideal.

## Componentes

- Arduino Uno
- Sensor de temperatura (LM35)
- Sensor de umidade (HR202)
- Sensor de luminosidade (LDR)
- Display LCD 16x2
- Buzzer
- Resistores
- LEDs
- Jumpers
- Breadboard

## Montagem

1. Conecte o sensor de temperatura (LM35) na entrada analógica A1 do Arduino.
2. Conecte o sensor de umidade (HR202) na entrada analógica A2 do Arduino.
3. Conecte o sensor de luminosidade (LDR) na entrada analógica A0 do Arduino.
4. Conecte o display LCD 16x2 aos pinos digitais 2, 3, 4, 5, 6, 7 e 9 do Arduino.
5. Conecte o buzzer ao pino digital 8 do Arduino.
6. Conecte os LEDs aos pinos digitais 10, 11 e 12 do Arduino.
7. Conecte os resistores adequados aos sensores e LEDs, conforme necessário.

## Funcionamento

O projeto realiza as seguintes ações:

1. Lê os valores dos sensores de temperatura, umidade e luminosidade.
2. Converte os valores lidos para as unidades adequadas (graus Celsius, porcentagem de umidade relativa e nível de luminosidade).
3. Compara os valores convertidos com os intervalos ideais.
4. Aciona os LEDs e o buzzer, caso os valores estejam fora dos intervalos ideais.
5. Exibe as informações no display LCD.

## Código

O código em C++ é utilizado para programar o Arduino e realizar as ações mencionadas. Cole o código fornecido no ambiente de desenvolvimento do Arduino (IDE) e faça o upload para o microcontrolador.
