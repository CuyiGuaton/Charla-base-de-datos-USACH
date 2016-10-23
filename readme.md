# Base de dato para tu proyecto científico

## Qué es una BD

Es un banco de información en el que se guardan grandes cantidades de información de manera estructurada y con la menor redundancia posible. Esto nos permite acceder a información que necesitamos de manera rápida y cómoda.

Es una buena opción  cuando se debe  registrar y modificar datos con regularidad y después obtener subconjuntos de estos datos.

# Porqué usar una base de datos en tu proyecto

- Una base de datos te va a evitar la **redundancia** generada al mezclar todos los datos que tengas en una sola hoja de calculo.

- **Búsquedas complejas** Una base de datos te va a permitir hacer consultas entre varias tablas distintas permitiendo obtener la información que requieres para el análisis del contenido.

- **Trabajo en equipo** Permite a establecer reglas a la hora de actualizar los datos, evitando que se produzcan inconsistencias entre los nuevos y los viejos datos.



Se usa cuando se debe manejar datos que no se pueden manejar de manera eficaz en una sola tabla, por ejemplo, si se desea almacenar los datos de una consulta veterinaria, es mejor tener tablas separada con los datos de los médicos y de animales que atiende, debido a que si desea ver los síntomas en los que llego un animal la primera vez que llego no va a interesar que ver la dirección y el estado civil del medico que lo atendió.

- Ejemplo de tabla única

Nombre Paciente| Tipo | Síntomas | Medico | Rut | E.C. | Sueldo
-------------- | ---- | ------ | ----- | ----| ------| --------
Sasha | Felino | Vomito, cansancio, pelo caído | Álvaro Pérez | 16.336.789-7 | Soltero | $500.000
Luna | Felino | Un poco vaga | Álvaro Pérez | 16.336.789-7 | Soltero | $500.000
Toby | Canino | No come | Juan Piedra | 15.533.559-5 | Soltero | $700.000

- Ejemplo con más de una tabla

Nombre Paciente| Tipo | Síntomas | Medico
-------------- | ---- | ------ | -------
Sasha | Felino | Vomito, cansancio, pelo caído | Álvaro Pérez
Luna | Felino | Un poco vaga | Álvaro Pérez
Toby | Canino | No come | Juan Piedra

Medico | Rut | E.C. | Sueldo
---- | ------ | -------- | -------
Álvaro Pérez | 16.336.789-7 | Soltero | $500.000
Juan Piedra | 15.533.559-5 | Soltero | $700.000

Como se puede apreciar, cuando se usa más de una tabla se pudo obtener los datos que realmente se necesitan en el instante y además como las dos tablas tienen el mismo campo (Medico) entonces es posible establecer una relación entre ambas tablas (poder hacer búsquedas cruzadas).


## Base de datos por sobre una hoja de calculo.
