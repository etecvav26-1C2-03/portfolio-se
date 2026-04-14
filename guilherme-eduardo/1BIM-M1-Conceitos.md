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

# Exercício 4 - Pergunta de Reflexão

## Hardware Open Source:

### Vantagens:

- Baixo custo (sem taxas de licença), flexibilidade para modificações, suporte comunitário robusto, facilidade de prototipagem (Arduino, Raspberry Pi).
- Independência de Fornecedor (Vendor Lock-in): Você não fica refém de uma única empresa. Se um fabricante parar de produzir uma placa, o design está disponível para outros fabricarem.

### Desvantagens:

- Riscos de segurança (código aberto pode expor vulnerabilidades), falta de suporte técnico formal (garantia), problemas de interoperabilidade.
- Escalabilidade Industrial: Nem todo hardware open source é certificado para ambientes industriais severos (ruído elétrico, calor extremo).

# Exercício 5 - Pergunta Conceitual

## Função do Microcontrolador:

- A função do microcontrolador é ser o cérebro do sistema embarcado. Ele lê as entradas (sensores), processa as informações baseando-se no software embarcado (firmware) e aciona as saídas (atuadores) de forma automática e específica para a tarefa desejada.

### Gestão de Energia:

- Ele controla o consumo, podendo entrar em modo "sleep" (dormir) para economizar bateria e "acordar" apenas quando um sensor detecta algo.

### Conversão de Sinais:

- Ele possui conversores Analógico-Digitais (ADC). Isso permite que ele entenda sinais do mundo real (como o calor de um sensor de temperatura) e os transforme em números binários (0 e 1).

# Exercício 6 — Pergunta de Aplicação

## Projeto Simples (Sensores e Atuadores)

#### Projeto: 
- Sistema de Monitoramento de Vaga de Estacionamento.

#### Problema: 
- Dificuldade em achar vagas em estacionamentos cobertos.

#### Sensores: 
- Sensor ultrassônico (HC-SR04) no teto para medir se há um carro embaixo.

#### Atuadores:
- LED bicolor (Verde/Vermelho) no teto para indicar status da vaga.

#### Funcionamento:
- Se o sensor detectar objeto a menos de 1m, o LED fica Vermelho (ocupado). Senão, Verde (livre).

# Exercício 7 - Pergunta de Investigação

## Botão e LED

#### Montagem:
- Arduino + Botão (com resistor de pull-down) + LED.
#### Funcionamento:
- O código lê o pino digital do botão. Se digitalRead(botao) == HIGH (pressionado), ele executa digitalWrite(led, HIGH). O LED permanece aceso enquanto o dedo estiver no botão; ao soltar, a leitura torna-se LOW e o LED apaga.

##### Resistor de Pull-Down (10k):
- É essencial conectar um resistor entre o pino do botão e o GND (terra). Isso garante que, quando o botão não estiver pressionado, o pino receba sinal "0" (LOW) absoluto, evitando "ruídos elétricos" que fariam o LED piscar sozinho.
##### Conexão do LED: 
- O LED deve ter um resistor limitador (ex: 220) em série para não queimar com a corrente do microcontrolador.

# Exercício 8 - Pergunta de Reflexão

## Movimento Maker:

- O movimento maker contribui para o aprendizado através da metodologia "mão na massa" (learning by doing). Ele desmistifica a tecnologia, permitindo que iniciantes construam, errem e corrijam projetos reais, promovendo pensamento crítico, resolução de problemas e criatividade em eletrônica e programação.

