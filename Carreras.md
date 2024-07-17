# Carreras

## Listado de Entidades

### carreras **(ED)**

-carrera_id **(PK)**
-nombre
-tipo_arrera **(FK)**
-fecha
-tiempo
-mejor_tiempo
-altitud
-pais **(FK)**
-lugar
-foto

### tipos_de_carreras **(EC)**

-tipo_carrera **(PK)**
-descripcion
-distancia

### Paises **(EC)**

-pais_id **(PK)**
-nombre

## Relaciones

1. Una **carrera** _pertenece_a un **tipo de carrera**. (\_1 a M_)
2. Una **carrera** se*corre_en un **pais**. (\_1 a M*)
