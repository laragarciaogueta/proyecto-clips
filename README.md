# PROYECTO CLIPS - REVERSI

En este proyecto implementamos el juego de REVERSI utilizando el sistema de porgramación CLIPS. 

El juego se desarolla en un tablero de tamaño 8x8, donde dos jugadores (fichas negras y blancas) se turnan para colocar sus fichas. El objetivo es capturar las fichas del oponente atrapándolas entre dos fichas propias en liena recta (horizontal, vertical o diagonal).

El jugador con más fichas en el tablero al final del juego será el ganador.

Nuestro proceso ha iniciado con la creación de plantillas, reglas para inicializar el juego, para validar movimientos, para imprimir el tablero, para el turno del jugador humano y para el turno de la máquina.
Además, [[POR HACER CON PROXIMOS PASOS]]

# ESTADO ACTUAL DEL PROYECTO
Nuestro proceso ha iniciado con la creación de plantillas, reglas para inicializar el juego, para validar movimientos, para imprimir el tablero, para el turno del jugador humano y para el turno de la máquina.
Además, [[POR HACER CON PROXIMOS PASOS]]

- Representación del tablero mediante hechos "casilla"
- Control del juego mediante fases "juego"
- Inicialización del tablero con las 4 fichas centrales
- Regla para detectar movimiento válidos --> Validación de jugadas legales e ilegales
- Visualización del tablero por consola
- Cambio de turno entre jugadores
- 
## IDEAS PARA HACER:
- imprimir tablero al principio, antes del turno humano para ver posibles, y después de cada movimiento para ver el resultado. También al final para mostrar el resultado final.
- para añadir: otro simbolo para indicar movimientos posibles si es el turno del humano.
- Al ganar/perder: printear en grande (texto caracteres ascii) YOU WIN/LOSE


## PENSAMIENTO MAQUINA
- Primer pensamiento de la máquina: elegir movimiento que capture más fichas. 
- Más adelante, quizás usando la prioridad, podemos hacer que las esquinas tengan valor altisimo y las adyacentes a las esquinas tengan valor bajisimo, para que la máquina intente coger las esquinas y evitar que el humano las coja.

