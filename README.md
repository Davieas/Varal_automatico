# Varal automatico
Projeto de um Varal Automatizado Com Arduino

Um projeto Simples e basico, para fins educativos e para apresentação ao publico, no Sacaiff, evento do Instituto Federal Fluminense de Padua



Materiais para o circuito:

1 Fonte 9V para alimentaçao do arduino e ponte H,
2 Motores do tipo DC de 5v,
1 Modulo L298N (Ponte H), para controle dos motores,
2 Sensores de fim de curso,
12 Fios tipo jumper,
1 Sensor de Chuva. 

Para montar o circuito e indicado saber o funcionamento do Modulo L298N, ou ler o datasheet do modulo:

DataSheet do modulo: https://files.comunidades.net/mutcom/Driver_Motor_ponteH__L298N.pdf 

 Montagem do Circuito completa, pinos e etc.









 Funcionamento Do Codigo

O codigo basicamente consiste em se caso o Sensor de Chuva estiver detectando o valor menor doque 800, ele ira retrair o varal, caso contrario ira continuar em sua posiçao inicial (No sol).
