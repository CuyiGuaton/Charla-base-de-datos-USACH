<!-- $theme: gaia -->
<!-- $size: 16:9 -->


# ==Base de datos== para tu proyecto

- ¿Qué es una base de datos?
- Ventajas de un BD
- Base de datos por sobre hojas de calculo
- Implementación
	1. Pico

---
<!-- *template: invert -->
# ¿Qué es una base de datos?

Es un almacén en el que se guardan grandes cantidades de información de manera estructurada y con la menor redundancia posible.
<p align="center">
	<img src="images/relational-database-model1.png"  height="400">
</p>

---

# Ventajas de una BD
       
       
       
       
       
- Evita la **redundancia** de datos
- Permite hacer consultas complejas para el **análisis del contenido**
- Permite establecer reglas a la hora de **trabajar en equipo**

---


## Ejemplo de tabla única

Nombre Paciente| Tipo | Síntomas | Medico | Rut | E.C. | Sueldo
-------------- | ---- | ------ | ----- | ----| ------| --------
Sasha | Felino | Vomito, cansancio | Álvaro Pérez | 16.336.789-7 | Soltero | $500.000
Luna | Felino | Un poco vaga | Álvaro Pérez | 16.336.789-7 | Soltero | $500.000
Toby | Canino | No come | Juan Piedra | 15.533.559-5 | Soltero | $700.000

---

##  Ejemplo con más de una tabla

Nombre Paciente| Tipo | Síntomas | Medico
-------------- | ---- | ------ | -------
Sasha | Felino | Vomito, cansancio | Álvaro Pérez
Luna | Felino | Un poco vaga | Álvaro Pérez
Toby | Canino | No come | Juan Piedra

<br>

Medico | Rut | E.C. | Sueldo
---- | ------ | -------- | -------
Álvaro Pérez | 16.336.789-7 | Soltero | $500.000
Juan Piedra | 15.533.559-5 | Soltero | $700.000

---



---
[https://www.gcfaprendelibre.org/tecnologia/curso/access_2010/trabajar_con_bases_de_datos/1.do]


---