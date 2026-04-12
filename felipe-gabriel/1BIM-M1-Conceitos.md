# Exercício 1 
## Pergunta conceitual
## Explique com suas palavras o que é Internet das Coisas (IoT) e cite um exemplo do cotidiano.

- A internet das coisas (IOT) são objetos com sensores e softwares, permitindo que eles coletem e troquem dados. Fazendo com que objetos do cotidiano sejam automatizados e com um minimo de intervenção humana, assim os tornando objetos do cotidiano inteligentes, em resumo seriam objetos físicos dotados de sensores e conexão WI-FI
### Um exemplo do cotidiano.
- No caso de um aspirador robô, a IoT transforma um simples aparelho de limpeza autônomo em um dispositivo inteligente, conectado ao ecossistema da casa. 

# Exercício 2
## Pergunta de aplicação
## Descreva como um sistema embarcado poderia ser usado para automatizar a iluminação de uma casa.

- O sistema embarcado é um sistema operacional que é composto de softwares e hardwares, ele é feito para ser utilizado dentro de um outro equipamento podendo ser utilizado em um sensor de movimento, para que sempre que alguem passar na frente do sensor e entrar no local uma lâmpada acenderá automaticamente.
### Exemplo
- Utilizando o sensor de movimento ele identificará se alguem passou, e com o comando "if" escrevemos uma condição para ele ligar ou desligar as luzes quando o sensor ativar.

# Exercício 3
##  Pergunta de investigação
## Utilize o simulador Wokwi ou Tinkercad para montar um circuito com um LED. Teste diferentes tempos de delay e registre o comportamento observado.

- Simulador utilizado: Tinkercad.
-  Ao mudar o tempo de delay e aumenta-lo o circuito de led demorou mais tempo para executar os comandos. Agora com o delay menor, o tempo entre os comandos diminuiu, fazendo com que fossem executados mais rapidamente.

### Trecho do Código 
// C++ code
//
void setup()
{
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
}

void loop()
{
  digitalWrite(4, HIGH);
  digitalWrite(3, LOW);
  delay(1000);
  digitalWrite(3, HIGH);
  digitalWrite(4, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}


---



# Exercício 6 
## Pergunta de aplicação
## Proponha um projeto simples utilizando sensores e atuadores para resolver um problema real.

### Problema de conveniência 

- Um projeto de automatização por horário fixo de ligar e apagar luz, serviria como conveniência e ser utilizado como próprio alarme ou horário de apagar quando você souber que vai sair de casa já naquele horário, sendo possivelmente programável os horários fixo no void setup(C++) e utilizados no void loop, funcionaria por meio de um atuador que ligaria a luz quando recebesse uma carga do Arduino que teria um relógio interno para esse meio, e com possíveis melhoras como sensor de movimento para apagar quando você sair do quarto ou ligar quando você entrasse no cômodo.


# Exercício 7
## Pergunta de investigação
## No simulador, adicione um botão ao circuito do LED. Programe para que o LED acenda apenas quando o botão for pressionado. Descreva o funcionamento.

## Componentes utilizados:
* Arduino Uno (Microcontrolador principal)
* LED (Luz)
* Resistor 220Ω (Limitação de corrente elétrica)
* Protoboard (montagem do circuito)
* Cabos Jumper (Conexões elétricas)

- primeiro definiria as entradas(input) dos sensores como o próprio botão e as saídas (output) como as LEDS(luzes) no void setup(), e após no void loop, lendo o valor da entrada com digitalRead e guardando numa variável e depois checando utilizando o IF com '' if (variavel == HIGH) '' para ver se está HIGH ou LOW a variável definida no digitalRead, (seria o clique do botão) assim sendo quando pressionado o botão a luz sendo ligada dentro do IF, e quando não pressionado ficaria no ELSE com a luz apagada

# Exercício 8
## Pergunta de reflexão
## Como o movimento maker contribui para o aprendizado em tecnologia?

- o movimento maker e um próprio incentivo para começar as coisas e a famosa "tentativa e erro'' a prática, incentivando a criar, consertar e modificar com as próprias mãos errando e aprendendo por si mesmo, sendo uma aprendizagem aditiva muito mais forte do que apenas lendo documentações ou teorias, estimulando sua própria criatividade e permitindo experimentar por si mesmo, além de ajudar na próprio melhora além de intelectual também habilidade prática e adquirindo experiencia com destreza manual por si, sendo as habilidades mais relevantes no mercado de hoje

# Exercício 9 
## Pergunta de aplicação
## Explique como sensores e atuadores trabalham juntos em um sistema de irrigação automatizado.

- No Void Setup, definindo as entradas(input) que seriam os sensores e as saídas (output) que seria as saídas, um sistema de irrigação funciona por meio de um sensor que mede a umidade do solo, que manda a informação para o Arduino e no Void Loop baseado no valor da variável que seria definida por meio da utilização de digitalRead abrir um IF definido para a abertura ou fechada da válvula que seria o atuador caso a umidade esteja abaixo de certo nível e um ELSE que manteria ela fechada enquanto não estiver a baixo de tal, sendo essa irrigação automática muito mais conveniente e não sendo fixa em horários assim podendo utilizar fenômenos/variáveis como a chuva como ajuda, assim sendo muito mais eficiente

# Exercício 10
## Pergunta de investigação
## Explore um projeto pronto no Wokwi ou Tinkercad. Modifique algum parâmetro (tempo, sensor, etc.) e descreva o que mudou.

- em um projeto de controle de 5 leds com Potenciômetro podemos modificar parâmetros como os valores do IF podendo ligar ou desligar mais de 1 led  com diferentes números entre 0-1023 (capacidade do potenciômetro) assim podendo definir a quantidade de LEDs ligados ao depender do giro do potenciômetro, sendo maiores os valores maior o giro para ligar os LEDs e menor os valores menos giros necessários para o ligamento das mesmas, também podemos modificar o delay dos blinks podendo aumentar deixando mais lento a velocidade dos piscar ou diminuindo deixando quase instantâneo, e com essas ações demonstradas podemos ver o movimento maker aprendendo modificando projetos já feitos.
