# Dojo-D
## Integrantes 
- Thiago Rodriguez
- Belen Soria
- Franco Sodia
- Iván Sacks

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
  Link al proyecto: 
  https://www.tinkercad.com/things/0UM3ZlFqdpF-ivan-sacks-dojo-d-ejdojouno/editel?sharecode=t2-icXHy_uBGoIYf1aFnwEec6A11fBIYcaKNgTn3M8s
