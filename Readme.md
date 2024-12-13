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
};
```
---

### Ejemplos de funciones:
En general este programa solo hace 3 cosas:
1.  Recorrrer el tablero
2.  Contar las fichas de cada jugador
3.  Comparar las fichas totales y determinar el ganador

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

---

### Javadoc de las funciones
#### Función para recorrer el tablero:
```java
/**
 * Recorre e imprime el tablero.
 * 
 * @param tablero el tablero de juego con las casillas vacias y las fichas
 */
public static void recorrerTablero(String[][] tablero) {
}
```
#### Función para contar fichas de cada equipo:
```java
/**
 * Cuenta y devuevelve el tatal de las fichas de cada jugador
 * 
 * @param tablero el array con el tablero de juego
 * @param fichasB  numero de fichas blancas
 * @param fichasN  numero de fichas negras
 * @return la suma de las fichas de ambos jugadores
 */
public static int contarFichas(String[][] tablero, int fichasB, int fichasN) {
}
```
#### Función para determinar el ganador:
```java
/**
 * Compara la contidad de fichas e imprime el ganador
 * @param totalB total de fichas blancas
 * @param totalN total de fichas negras
 */
public static void determinarGanador(int totalB, int totalN) {
    
}
```


