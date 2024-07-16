![image](https://github.com/user-attachments/assets/c331ea0d-a53a-4777-a0bd-a3c495347a2f)# arduino-firstproject

# **[Arduino Primeiro Projeto: Acendendo um Led](README.md)**

------

### Introdução

Nesse repositório será documentado os passos iniciais para acender e apagar um LED utilizando uma placa Arduino. Um projeto simples, mas essencial para iniciar com arduiono.

Para iniciar não estaremos utilizando um Arduino físico, e sim uma ferramenta online que podemos fazer a simulação das conexões e também escrever o código.

### Pré-Requisitos Digital

Conta no https://www.tinkercad.com/

### Pré-Requisitos Físico

## Diferença entre Portas Digitais e Portas Analógicas

Portas Analógicas - utiliza apenas 0 ou 1, ou seja, ligado ou desligado. Recebeu ou não recebeu. O Led esta ligado ou ele esta desligado

Portas Analógicas - utiliza de 0 a 1023

Para esse projeto usaremos as portas digitais.




### 1. 

Precisamos associar uma porta do arduino ao LED, ou seja, conectar o led a porta
para que possamos comandar o envio de energia, podendo então fazer ela piscar e ate controlar o tempo entre cada piscada.

Usaremos a porta digital número 2
Iniciando nosso código


int LED 2;

void setup()
{
  
}

void loop()
{

}

![captura](https://github.com/user-attachments/assets/e8f0d53e-1462-43a3-be06-343140fa11ac)



### 2. 

Catodo/Catódica = Vai no negativo / GND

Anodo = Vaino positivo / porta digital

O Arduino trabalha em 5, e o led em 3 3.5

cuidar para nao cuidar o led

usar outro componente eletronico, resistor
Selecionar o resistor correto
Como fazer o calculo correto

Devemos fazer a ligação de cabos como essa






