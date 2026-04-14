# Exercício 1 — Pergunta conceitual

## O QUE É IOT?
- IoT ou Internet Das Coisas são objetos que possuem sensores, softwares e uma tecnologia para poder coletar, trocar dados e interagir autonomamente, sem um humano precisar ficar intervindo. E esses objetos estão presentes em diversos lugares do nosso cotidiano, já virou algo enraizado no nosso dia a dia.

## EXEMPLO DE IOT NO COTIDIANO:
- Um dos exemplos que podemos usar é a lampada inteligente que liga com um comando do celular,  Ela é um exemplo de iot por ter acesso a internet que possa conectar ao celular, tambem temos a famosa alexa ela tambem é uma iot bem utilizada

 ![riujgh](https://github.com/user-attachments/assets/3c97f6c0-44eb-4ff4-9d1d-38ee6910dd91) ![shopping](https://github.com/user-attachments/assets/f4319a2c-ea49-480e-890f-35b3612778b4)

# Exercício 2 — Pergunta de aplicação

## COMO PODERIA AUTOMATIZAR?

- Um sistema embarcado pode automatizar a iluminação residencial através dos seguintes componentes: Sensores(Sensor de Luz (LDR) para medir a luminosidade ambiente e sensor de presença (PIR) para detectar movimento.), Atuadores(Relés para ligar/desligar lâmpadas convencionais (AC) ou módulos Dimmer para controlar a intensidade.)

## FUNCIONAMENTO:

- O microcontrolador processa os dados dos sensores. Se o LDR detectar que escureceu E o PIR detectar movimento, o relé fecha o circuito e acende a luz. O sistema pode desligar automaticamente após um tempo sem detecção.

# Exercício 3 - Pergunta de investigação

## MONTAGEM:

- Arduino + Resistor 220 + LED no pino 13.

## CÓDIGO:

- digitalWrite(led, HIGH); delay(T); digitalWrite(led, LOW); delay(T);

### Comportamento (T=1000ms):
- Piscada lenta (1 segundo ligado, 1 segundo desligado).

### Comportamento (T=100ms):
- Piscada rápida, quase contínua, mas visível.

### Comportamento (T=10ms):
- O LED parece estar constantemente aceso com metade da intensidade, pois o olho humano não percebe a velocidade da alternância.

# Exercício 4 - Pergunta de Reflexão: Hardware Open Source

## Vantagens:

- Baixo custo (sem taxas de licença), flexibilidade para modificações, suporte comunitário robusto, facilidade de prototipagem (Arduino, Raspberry Pi).

## Desvantagens:

- Riscos de segurança (código aberto pode expor vulnerabilidades), falta de suporte técnico formal (garantia), problemas de interoperabilidade.

