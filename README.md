main
Cambie el codigo y cree una nuvea funcion llamada move_food, esta hace que la comida se mueva al azar mediante el jugador avanza.

# Snake

Juego de la víbora desarrollado en Python con Turtle y Free Python Games, basado en el código original de Grant Jenks.

## Objetivo

Controlar la víbora para comer y aumentar su tamaño, evitando chocar con los límites de la ventana o con su propio cuerpo.

## Requisitos

- Python 3.
- Turtle disponible en la instalación de Python.
- Biblioteca Free Python Games.

## Instalación y ejecución

Desde la carpeta del repositorio, crear y activar un ambiente virtual en Windows:

bat
py -m venv .venv
.venv\Scripts\activate
python -m pip install freegames
python snake.py


## Controles

Usar las flechas del teclado para cambiar la dirección de la víbora.

## Modificaciones

### Santiago Román Villalobos Bolaños

- Agregó una lista de cinco colores: verde, azul, morado, naranja y negro.
- Implementó la selección aleatoria de dos colores distintos mediante `sample`.
- Asignó un color a la víbora y otro a la comida al iniciar cada partida.
- Excluyó el rojo de la selección de colores.

Los colores pueden repetirse entre partidas, pero la víbora y la comida tienen colores distintos dentro de una misma partida.

### Compañera de equipo

- Implementó el movimiento aleatorio de la comida, un paso a la vez.
- Limitó su movimiento para evitar que salga de la ventana.

## Comprobación del funcionamiento

- Abrir varias partidas y comprobar que la víbora y la comida tengan colores diferentes.
- Verificar que la comida se mueva y permanezca dentro de los límites.
- Comprobar que la víbora crezca al comer y que las colisiones sigan funcionando.

## Trabajo colaborativo

Se trabajó con un repositorio principal y un fork, sin acceso de colaborador. Los cambios se registraron mediante commits y se integraron mediante pull requests.

## Código de referencia

Grant Jenks, Free Python Games:
https://grantjenks.com/docs/freegames/snake.html
 main
