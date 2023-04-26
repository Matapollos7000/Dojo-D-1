# Dojo-D
## Integrantes 
- Thiago Rodriguez
- Belen Soria
- Franco Sodia
- Iván Sacks
- Melina Silva

## Descripción
Nuestro proyecto cumple la función de un semaforo, prendiendo y apagando cada led y cuando llega a la led roja se produce un sonido

## Función principal
Esta funcion se encarga de encender y apagar los leds, y si se enciende la led roja , suena un sonido dos veces en un segundo.

Verde,Rojo y Amarillo son #define que utilizamos para agregar los leds, asociandolo a pines de la placa arduino.

~~~ C (lenguaje en el que esta escrito)
void PrenderApagar(int led , int tiempo)//Prende y apaga las led
{
  if (led != Rojo && led != Rojo2 )
  {
  digitalWrite(led, HIGH);
  delay(tiempo);
  digitalWrite(led, LOW); 
  }
  else// Si es rojo, se ejecuta y suena el buzzer
  {
    digitalWrite(led, HIGH);
    tone(Buzzer, 100, 1000);
    delay(100);
    noTone(Buzzer);
    delay(100);
    tone(Buzzer, 100, 1000);
    delay(tiempo);
    digitalWrite(led, LOW); 
  }
}

~~~
  Links al proyecto: 
  Iván: https://www.tinkercad.com/things/0UM3ZlFqdpF-ivan-sacks-dojo-d-ejdojouno/editel?sharecode=t2-icXHy_uBGoIYf1aFnwEec6A11fBIYcaKNgTn3M8s
  Belen Soria: https://www.tinkercad.com/things/i5YadsTv6GA-1d-dojo-d-soria/editel?sharecode=NJgFzQIbBMTWZXhFoCaBf0GYQ75TVjQc9fx_lACDTSc
  Thiago Rodriguez: https://www.tinkercad.com/things/fSnegusuI81-brave-elzing/editel?sharecode=V6gH1mG6p_U0Ck5-6Gz9RrXBJ6MydZY3HOWQgdQ9Vzk
  Melina Silva: https://www.tinkercad.com/things/cADprBpRUZb-copy-of-dojo-d-ejercicio-02-franco-sofia/editel?sharecode=s49qYkW5lOgLgG1-rdUSvXFMocdVisnxHcHN4Yv2QlY
