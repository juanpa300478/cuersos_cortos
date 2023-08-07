# DB colegio ralfael pombo #

## Nombre de la base de datos ##

estudiantes_rafael_pombo

se eligen este nombre de bases de datos, por el hecho que en esta base
de datos se guardara la informacion de todos los estudiantes del colegio
Rafael Pombo. Para las coleccion se elige el siguiente nombre _primer_grado_
este nombre se elige, debido a que los alumnos que se guardaran a esta coleccion
pertenecen al primer grado. Podriamos tener en esta base de datos mas colecciones
como por ejemplo _sexto_grado_, _cuarto_grado_ ext, y asi poder tener una base de 
datos escalable que pueda guardar la informacion de los estudiantes de cada curso
del colegio

## Colecciones ##

### primer_grado ###

- numero_identidad
- primer_nombre
- segundo_nombre
- primer_apellido
- segundo_apellido
- direccion
- telefono
- acudiente
- edad
- pasatiempo

## Diagrama ##

```json
"primer_grado": [
    {
        "numero_identidad": 104678950,
        "primer_nombre": "mario",
        "segundo_nombre": "javier",
        "primer_apellido": "fonseca",
        "segundo_apellido": "ramirez",
        "dirreccion": "calle n 14-8",
        "telefono": "3145678998",
        "acudiente": {
            "numero_identidad": 1045678987,
            "nombre": "juanita",
            "apellido": "montalvo",
            "telefono": "3125678909"      
        },
        "edad": 12,
        "pasatiempos": ["ver peliculas","jugar la lleva",""]
    }
]
```