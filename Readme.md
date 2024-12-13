# Examen 1ª Evaluación

---

Explica a continación cada apartado del examen

Con cada apartado realiza un commit diferente

Clonar el repositorio
![clonar.png](imagenes/clonar.png)
Diagrama de flujo

![Damas.drawio.png](imagenes/Damas.drawio.png)

¿Cómo sería el tablero?
String[][] tablero = {
{"B", "N", "",  "", "", "", "", ""},  
{"",  "B",  "",  "", "", "", "", ""},  
{"",  "",  "",  "B", "N", "", "", ""},  
{"",  "",  "",  "", "", "", "", ""},  
{"",  "",  "",  "", "", "B", "", ""},  
{"",  "",  "N", "", "", "", "", ""},  
{"",  "",  "",  "N", "", "", "N", ""},  
{"",  "N",  "",  "", "", "", "", "B"}   
}


Ejemplos de funciones:

public stativ void recorrerTablero (String[]tablero)
public static int contarFichas(String[]tablero, int fichasB, int fichasN)
public static void determinarGanador (int totalB, int totalN)