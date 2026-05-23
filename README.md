README — Controle de LED com Arduino
Descrição

Este projeto utiliza um Arduino para controlar um LED conectado ao pino digital 2. O programa configura o pino como saída e mantém o LED ligado continuamente.

Funcionamento
O setup() é executado uma única vez ao iniciar o Arduino.
A comunicação serial é iniciada em 115200 baud.
O pino 2 é configurado como saída.
No loop(), o LED é ligado com digitalWrite(ledPin, HIGH).
O delay(1000) mantém uma pausa de 1 segundo.
Como não existe um comando para desligar o LED (LOW), ele permanece ligado continuamente.

Componentes Necessários
1 Arduino (Uno, Nano, ESP32 compatível, etc.)
1 LED
1 resistor de 220Ω
Jumpers
Protoboard (opcional)

Esquema de Ligação
Componente	Conexão
LED (+)	Pino 2
LED (-)	Resistor → GND


Como Executar
Abra a IDE do Arduino.
Copie o código para um novo projeto.
Selecione a placa e a porta correta.
Faça o upload do código para o Arduino.
O LED será ligado automaticamente.
Resultado Esperado

Após iniciar o programa:

O LED conectado ao pino 2 ficará aceso continuamente.

Licença

Projeto livre para estudos e aprendizado em Arduino e sistemas embarcados.


