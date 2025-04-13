# Propuesta TP DSW

## Grupo
### Integrantes
* 51136 - CANO, Julián
* 46835 - FOIX, Gastón
* 51236 - JUAN BENNAZAR, León
* 51729 - MORETTI, Lucca

### Repositorios
* [frontend app]()
* [backend app]()

## Tema (NOMBRAR APLICACIÓN)
### Descripción

[NOMBRE DE APP] es un sistema para gestionar reservas de canchas de fútbol. Solamente tenés que registrar un usuario con tu mail para empezar a reservar. Elegís la fecha, la hora y la cancha que más te guste [y pagar la seña para confirmar la reserva]. Nosotros te recordamos cuando te toca jugar!

### Modelo
[imagen del modelo](https://drive.google.com/file/d/1B_XXn6uLUYE9IYtGiJ_Q2tqKOh1vT_ZC/view?usp=sharing)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tamaño Cancha<br>2. CRUD Material Cancha<br>3. CRUD Agenda<br>4. CRUD Usuario|
|CRUD dependiente|1. CRUD Cancha {depende de} CRUD Tamaño Cancha y Material Cancha<br>2. CRUD Reserva {depende de} CRUD Cancha, Agenda y Usuario|
|Listado<br>+<br>detalle| 1. Listado de Canchas filtrado por Material y Tamaño => detalle Crud Cancha<br> 2. Listado de Reservas filtrado por fecha: muestra número de Cancha, hora de inicio, hora de finalizado y nombre del Cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una cancha.<br>2. Cancelar una reserva.<br>3. Enviar recordatorio de reserva a cliente por correo electrónico.|

Adicionales para Aprobación Directa:
|Req|Detalle|
|:-|:-|
|CRUD |1. <br>2. <br>3. <br>4. <br>5. <br>6. <br>7. |
|CUU/Epic|1. <br>2. <br>3. |

### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.
