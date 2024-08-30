# Trabalho-LIA

trabalho-2024-LIA-Prof.https://github.com/Epaminondaslage

Lâmpada Controlada por Palmas usando Arduino
Este projeto permite que você controle uma lâmpada com o som de uma palma, utilizando um Arduino Uno, Módulo Relé e um Sensor de Som Digital. A lâmpada alterna entre ligada e desligada a cada palma.

# Componentes Utilizados
.Arduino Uno

.Módulo Relé

.Fonte de Alimentação 5V SMPS

.Sensor de Som Digital

.Lâmpada

.Fios Jumper

.Protoboard
# Diagrama de Circuito

![Opera Instantâneo_2024-08-30_094430_projecthub arduino cc](https://github.com/user-attachments/assets/41767499-f346-4089-bf78-fd8601d87e65)


# Conexões

Sensor de Som Digital:

.VCC: Conecte ao pino de 5V do Arduino.

.GND: Conecte ao GND do Arduino.

.OUT: Conecte ao pino digital 7 do Arduino.

Módulo Relé:

.VCC: Conecte ao pino de 5V do Arduino.

.GND: Conecte ao GND do Arduino.

.IN: Conecte ao pino digital 8 do Arduino.

.COM: Conecte ao fio de fase da lâmpada.

.NO (Normalmente Aberto): Conecte à lâmpada.
Lâmpada:

Conecte um fio ao pino COM do módulo relé e o outro à fase da rede elétrica.
O fio neutro da rede elétrica vai direto para a lâmpada.

![Opera Instantâneo_2024-08-30_094805_www youtube com](https://github.com/user-attachments/assets/d9a1d80e-e375-4e18-a544-6bca2b0d4015)

# Como Funciona

O sensor de som digital detecta o som de uma palma.
O Arduino lê a saída do sensor. Se um som for detectado, o Arduino alterna o estado do relé.
O relé controla a energia da lâmpada, ligando ou desligando com base no estado do relé.

# Precauções de Segurança

Certifique-se de utilizar isolamento adequado ao trabalhar com o relé e a lâmpada, pois você estará lidando com tensão da rede elétrica.
Verifique as conexões antes de ligar a alimentação para evitar curtos-circuitos ou riscos elétricos.

# Referência
https://projecthub.arduino.cc/utsabkayal001/clap-switch-using-arduino-281d0d
