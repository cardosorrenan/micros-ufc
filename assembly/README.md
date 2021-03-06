### Exercícios

1. Desenvolva um programa que calcule a soma de duas variáveis de memória de 16 bitsarmazenado o resultado em uma terceira variável, também de 16 bits.

> . / exercicio1.asm

2. Desenvolva um programa que conte a quantidade de bits “1” existentes em uma variável dememória de 8 bits guardando o resultado em outra variável de memória também de 8 bits.

> . / exercicio2.asm

3. Desenvolva um programa que calcule a soma dos 4 bits mais significativos e dos 4 bits menossignificativos de uma variável de memória de 8 bits.  O resultado da soma deve ser armazenadoem outra variável de memória  de 8 bits.

> . / exercicio3.asm

### Geração de Ondas

Desenvolva um projeto no MPLABX para gerar, em três pinos de E/S distintos  do PIC18F4550,  as formas de onda apresentadas na figura a seguir. A constante T é definida pela fórmula: T={ 100.N μs segundos, se N>0 e 100 μs segundos, se N=0, sendo N o último dígito de seu número de matrícula.

<p align="center">
    <img src="https://github.com/cardosorrenan/micros-ufc/blob/master/assembly/img/ger_onda.png" width="450">
</p>

> . / gerarOndas.asm

### Cronômetro Regressivo

Tomando como base o hardware da figura a seguir, desenvolva um cronômetro regressivo de minutos. Esse cronômetro deve iniciar parado e com um valor inicial de contagem de 60 minutos, sendo esta configurável em incrementos de 10 minutos a cada acionamento de um dos botões. Ao iniciar a contagem, pelo acionamento de outro botão, esta não poderá mais ser ajustada e nem parada. Ao término da contagem, um buzzer de alarme deve ser acionado emitindo um beep de duração de 250 milisegundos a cada 1 segundo. Nessa ocasião o alarme será interrompido ao se pressionar qualquer uma das teclas, levando o cronômetro ao seu estado inicial: contagem parada, alarme desativado e contagem inicial de 60 minutos.

<p align="center">
    <img src="https://github.com/cardosorrenan/micros-ufc/blob/master/assembly/img/cronos.png" width="450">
</p>

> . / cronometroRegressivo / cronometroRegressivo.asm
