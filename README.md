# Checkpoint 1: Sensor de Monitoramento de Luminosidade no Arduíno  

### Integrantes do Grupo  
Albert Katri - RM556544  
Alexandre Assis do Nascimento - RM558927  
Gabriel Ferreira Flora Cavalheiro - RM556476  
Gustavo Ramalho Gaudêncio - RM554582  
Hugo Okwudiri - RM557035

### Sobre o projeto
É um sistema de monitoramento de luminosidade que vai ser implementado como uma solução para a Vinheria Agnello.  
A proposta seria de projetar um sensor para ser instalado no local onde os vinhos são armazenados para então monitorar a quantidade de luminosidade do ambiente,  tendo em mente que a qualidade do vinho é diretamente influenciada por três fatores principais, e um deles é justamente a luminosidade.

### Componentes usados:
* 1 LDR  
* 3 LED  
* 1 BUZZER  

### Como funciona o sensor?
Na primeira etapa do projeto, o sensor foi produzido no TinkerCAD, e na segunda parte do projeto o sensor será produzido utilizando Arduíno físico, em sala de aula.  
Utilizamos três LEDs que seriam acendidos e sinalizando, assim, o nível de luminosidade do ambiente. Para estabelecer esta dinâmica entre os leds e a luminosidade, criamos a seguinte lógica de programação:  
* se o valor de 880 for maior que a luminosidade, o led VERDE vai acender  
  * se a luz verde acender, significa que está tudo bem  
* se a luminosidade for igual ou maior que 880 e menor que 970, a luz amarela vai acender  
  * se a luz amarela acender, significa que a gente tem que estar em alerta com a quantidade de luminosidade que o sensor está recebendo  
* e caso não for nenhum desses casos, ou seja, maior que 970, a luz vermelha vai acender  
  * se a luz vermelha acender, significa que tem algum problema acontecendo, e tem muita luminosidade entrando no sensor e deve ser resolvido

Além disso, o sensor Buzzer vai trabalhar em conjunto com o LDR e os LEDs. Ele vai nos avisar quando a luminosidade estiver mais alta.
Haverão dois casos onde o Buzzer irá emitir um alerta sonoro:
* Quando o LED amarelo acender;
* Quando o LED vermelho acender.  
O único caso onde o Buzzer não vai emitir um alerta sonoro é enquanto o LED verde estiver aceso. Isto vai indicar que o nível de luminosidade está adequado.

### Sobre o LDR
O LDR, ou fotoresistor, vai possuir ter um sistema de captação de luz, que pode ser regulado manualmente. Com isso, é possível escolher o quanto de luminosidade vamos querer ao arrastar para um lado e para o outro.  
Usando o LDR você consegue colocar o quanto de luz você quer que esteja recebendo.

### Links
#### Link do projeto no TinkerCAD: https://www.tinkercad.com/things/4LXFW8zhjvh-edge-computing-checkpoint-1-sensor-de-luminosidade
#### Link do vídeo: https://drive.google.com/file/d/1iZpRyMsUv_2XJeVa405i4YTaf_66Yqa2/view?usp=sharing
