# Exercício 1 — Pergunta conceitual

## O QUE É IOT?

- IoT ou Internet Das Coisas são objetos que possuem sensores, softwares e uma tecnologia para poder coletar, trocar dados e interagir autonomamente, sem um humano precisar ficar intervindo. E esses objetos estão presentes em diversos lugares do nosso cotidiano, já virou algo enraizado no nosso dia a dia.

## EXEMPLO DE IOT NO COTIDIANO:

- Um dos exemplos que podemos usar é a lampada inteligente que liga com um comando do celular,  Ela é um exemplo de iot por ter acesso a internet que possa conectar ao celular, tambem temos a famosa alexa ela tambem é uma iot bem utilizada já que facilita a vida de todos que queiram usar(justamente por possuir "inteligencia"?

### IMAGENS DE IOT:
<p><img width="794" height="1000" alt="lampada-inteligente" src="https://github.com/user-attachments/assets/8417b8dd-e7c9-45f0-bd71-370123c261eb" />
"></p>

<p><img width="670" height="670" alt="alexa" src="https://github.com/user-attachments/assets/9d5d8fb8-2f01-4236-8cbb-8c44884fa8db" />
</p>


# Exercício 2 — Pergunta de aplicação

## COMO PODERIA AUTOMATIZAR?
Um sistema embarcado pode automatizar a iluminação usando sensores e atuadores. Sensores como LDR detectam a luminosidade do ambiente. Sensores PIR identificam a presença de pessoas no local. O microcontrolador processa essas informações em tempo real. Com base nos dados, ele toma decisões automaticamente.  

## FUNCIONAMENTO:
Quando o ambiente está escuro e há movimento, o sistema acende a luz. O relé é responsável por ligar ou desligar a lâmpada. Se não houver presença por um tempo, a luz é apagada automaticamente. Isso economiza energia e aumenta a praticidade. O sistema funciona sem necessidade de controle manual constante.  


# Exercício 3 — Pergunta de investigação

## MONTAGEM:
Foi utilizado um Arduino com um LED e resistor conectado ao pino 13.  
O circuito foi montado no simulador Wokwi.  
O código alterna o LED entre ligado e desligado.  
O tempo de delay foi modificado para observar diferenças.  
Isso permitiu analisar o comportamento do LED.  

## RESULTADOS:
Com delay de 1000ms, o LED pisca lentamente.  
Com 100ms, a piscada fica rápida e perceptível.  
Com 10ms, o LED parece ficar sempre ligado.  
Isso ocorre por causa da limitação da visão humana.  
O teste mostra como o tempo influencia na percepção visual.  


# Exercício 4 — Pergunta de reflexão

## VANTAGENS:
Hardware open source tem baixo custo e não exige licença.  
Permite modificações e personalização conforme o projeto.  
Possui grande suporte da comunidade.  
Facilita aprendizado e prototipagem rápida.  
Evita dependência de um único fabricante.  

## DESVANTAGENS:
Pode apresentar falhas de segurança.  
Nem sempre possui suporte técnico oficial.  
Pode haver incompatibilidade entre dispositivos.  
Nem todos são ideais para uso industrial.  
A confiabilidade pode variar dependendo do projeto.  


# Exercício 5 — Pergunta conceitual

## FUNÇÃO DO MICROCONTROLADOR:
O microcontrolador é o cérebro do sistema embarcado.  
Ele recebe dados de sensores e processa essas informações.  
Executa instruções programadas no firmware.  
Controla dispositivos de saída, como LEDs e motores.  
Tudo acontece de forma automática e rápida.  

## OUTRAS FUNÇÕES:
Pode economizar energia usando modo sleep.  
Possui conversores analógico-digitais (ADC).  
Transforma sinais físicos em dados digitais.  
Permite integração entre hardware e software.  
É essencial para o funcionamento do sistema.  


# Exercício 6 — Pergunta de aplicação

## PROJETO:
Sistema de monitoramento de vagas de estacionamento.  
O objetivo é facilitar a identificação de vagas livres.  
Muito útil em estacionamentos fechados.  
Ajuda a economizar tempo dos motoristas.  
Também melhora a organização do espaço.  

## FUNCIONAMENTO:
Um sensor ultrassônico detecta a presença de um carro.  
Se houver objeto próximo, a vaga está ocupada.  
Um LED vermelho indica ocupado.  
Um LED verde indica vaga livre.  
O sistema funciona automaticamente em tempo real.  


# Exercício 7 — Pergunta de investigação

## MONTAGEM:
Foi adicionado um botão ao circuito com LED.  
Utilizou-se um resistor de pull-down para estabilidade.  
O Arduino lê o estado do botão constantemente.  
O LED foi conectado com resistor limitador.  
O circuito foi testado no simulador.  

## FUNCIONAMENTO:
Quando o botão é pressionado, o LED acende.  
Isso ocorre porque o sinal HIGH é enviado ao pino.  
Quando solto, o LED apaga com sinal LOW.  
O resistor evita sinais instáveis no circuito.  
O sistema responde imediatamente ao toque.  


# Exercício 8 — Pergunta de reflexão

## MOVIMENTO MAKER:
O movimento maker incentiva o aprendizado prático.  
Baseia-se no conceito de “aprender fazendo”.  
Estimula criatividade e resolução de problemas.  
Permite experimentar, errar e melhorar projetos.  
Torna o aprendizado mais dinâmico.  

## IMPACTO:
Ajuda iniciantes a entender tecnologia na prática.  
Facilita o uso de ferramentas como Arduino.  
Desenvolve pensamento crítico.  
Incentiva inovação e autonomia.  
É muito importante na educação tecnológica atual.  


# Exercício 9 — Pergunta de aplicação

## SISTEMA DE IRRIGAÇÃO:
Sensores e atuadores trabalham juntos automaticamente.  
O sensor mede a umidade do solo.  
O microcontrolador analisa esses dados.  
Se o solo estiver seco, ele ativa o sistema.  
Isso garante irrigação eficiente.  

## FUNCIONAMENTO:
Quando a umidade está baixa, a bomba é ligada.  
A água é distribuída até atingir nível ideal.  
Depois disso, o sistema desliga automaticamente.  
Isso evita desperdício de água.  
O processo ocorre sem intervenção humana.  


# Exercício 10 — Pergunta de investigação

## MODIFICAÇÃO:
Foi utilizado um projeto pronto no Wokwi.  
O sistema usava sensor ultrassônico com LED.  
O limite de distância foi alterado.  
Mudou de 200cm para 50cm.  
Isso tornou o sistema mais restritivo.  

## RESULTADO:
O LED só acende quando o objeto está bem próximo.  
Antes, ele ativava com maior distância.  
A mudança aumentou a precisão do sistema.  
Isso mostra como parâmetros influenciam o comportamento.  
Pequenas alterações podem gerar grandes diferenças.
