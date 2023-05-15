# Dojo-D
## Integrantes 
- Thiago Rodriguez
- Belen Soria
- Franco Sofia
- Iván Sacks
- R.I.P Melina Silva Siempre te recordaremos 😔


## Descripción
Nuestro proyecto cumple la función de un semaforo, prendiendo y apagando , titilando 3 veces antes de pasar al otro color , y haciendo ruidos cuando está en amarillo y rojo

## Función principal
Esta funcion se encarga de encender y apagar los leds y llamar a varias funciones como el buzzer o una verificación forzada.

(Breve explicación de la función)

~~~ C (lenguaje en el que esta escrito)
void prenderApagar(int led , int tiempo)
{
  switch(led)
  {
    case Rojo:
    Serial.println("Led Rojo encendido, buzzer activado");
	sonarRojo(led);
    sonarRojo(led);
    titilar(led);
     verificarBoton();
     	break;
    
    case Verde:
    Serial.println("Led verde encendido");
	digitalWrite(led, HIGH);
    delay(Tiempoverde);
    delay(2000);
    titilar(led);
    titilar(led);
    titilar(led); 
     verificarBoton();
   		break;
      
    case Amarillo:
    Serial.println("Led Amarillo encendido, buzzer activado");
	sonarRojo(led);
  	sonarAmarillo(led);
    delay(600);
    sonarAmarillo(led);
    delay(600);
    sonarAmarillo(led);  
    delay(600);
     verificarBoton();
  		break;
  }
~~~

  Links al proyecto:
  Ejercicio 1:
  Iván Sacks: https://www.tinkercad.com/things/0UM3ZlFqdpF-ivan-sacks-dojo-d-ejdojouno/editel?sharecode=t2-icXHy_uBGoIYf1aFnwEec6A11fBIYcaKNgTn3M8s
  
  Belen Soria: https://www.tinkercad.com/things/i5YadsTv6GA-1d-dojo-d-soria/editel?sharecode=NJgFzQIbBMTWZXhFoCaBf0GYQ75TVjQc9fx_lACDTSc
  
  Thiago Rodriguez: https://www.tinkercad.com/things/fSnegusuI81-brave-elzing/editel?sharecode=V6gH1mG6p_U0Ck5-6Gz9RrXBJ6MydZY3HOWQgdQ9Vzk
  
  Franco Sofia:https://www.tinkercad.com/things/cADprBpRUZb-copy-of-dojo-d-ejercicio-02-franco-sofia/editel?sharecode=s49qYkW5lOgLgG1-rdUSvXFMocdVisnxHcHN4Yv2QlY

  Ejercicio 2:
  Iván Sacks: https://www.tinkercad.com/things/kvZvP1zrmdb-ivan-sacks-dojo-d-ej2dojouno/editel?sharecode=FvJYjORmQpISy3dMQHERxsrFIkP-lHxH9M1NDHK18Qk
   
  Belen Soria: https://www.tinkercad.com/things/8tWmp2zrRWh-1d-dojo-d-ej-n2-soria-belen-2023-/editel?sharecode=rj9r6KzD5s8BTPdEhZ9x-ikRTFsV3yeYuETHGC3VyZU
  
  Thiago Rodriguez:https://www.tinkercad.com/things/h5oIiVFxzgR-thiago-rodriguez-divd/editel?sharecode=jJqcy1OoAR5w1sQz9vH64kyxpN5jdOwAbp42giW3hAI
  
  Franco Sofia:https://www.tinkercad.com/things/6s5M8m5FxDc-copy-of-dojo-d-ejercicio-02-franco-sofia/editel?sharecode=FXjhoH82igXUJB7aCQC95aXAd4CDrPa2xdhEm2jtWgo
  
   Ejercicio 3:
   
  Iván Sacks: https://www.tinkercad.com/things/0Lj1zFJznHd-ivan-sacks-dojo-d-ej3dojouno/editel?sharecode=fY1kJMpDqGoj8c3uDOqDfa6-XRFZToHtnDw2Az7gTX8
   
  Belen Soria: 
  
  Thiago Rodriguez:
  
  Franco Sofia:
  
