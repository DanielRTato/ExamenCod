# Examen 1ª Evaluación

---

Explica a continación cada apartado del examen

Con cada apartado realiza un commit diferente

---

### Clonar el repositorio
![clonar.png](imagenes/clonar.png)

---

### Diagrama de flujo

![Damas.drawio.png](imagenes/Damas.drawio.png)

---

### ¿Cómo sería el tablero?
```java
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
```
---

### Ejemplos de funciones:

#### Función para recorrer el tablero:
```java
public static void recorrerTablero(String[][] tablero) {
}
```

#### Función para contar fichas de cada equipo:
```java
public static int contarFichas(String[][] tablero, int fichasB, int fichasN) {
}
```

#### Función para determinar el ganador:
```java
public static void determinarGanador(int totalB, int totalN) {
    
}
```