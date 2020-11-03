# TesisMBorja

*************************************************************************************************************************************
TESIS: UN NUEVO ENFOQUE PARA EL PROBLEMA DE LOCALIZACIÓN Y RUTEO DE VEHÍCULOS EN LA CADENA DE SUMINISTROS DE PRODUCTOS PERECEDEROS
AUTOR: MARÍA JOSÉ BORJA ARTEAGA
PROGRAMA DE INGENIERÍA INDUSTRIAL
FACULTAD DE INGENIERÍAS
UNIVERSIDAD DE CÓRDOBA

*************************************************************************************************************************************
DESCRIPCIÓN
Este archivo tiene como finalidad orientar al lector sobre la documentación relacionada con la tesis presentada, en este sentido se presenta
el nombre de cada archivo, una breve descripción y el link para ubicarlo dentro de la carpeta.
*************************************************************************************************************************************
* TESIS MARÍA BORJA
Es el documento que presenta la investigación realizada con la siguiente estructura : 
1. Generalidades
2. Marco de referencia
3. Metodología
4. Descubrimientos
5. Conclusiones

* MODELO VERSION LINEAL VALIDACION
Este archivo contiene la versión lineal del modelo matemático, éste se puede importar al software GAMS para ejecutar el modelo.

* NSGA-II EXTERNO PYTHON
En este archivo se encuentra la programación del algoritmo NSGA-II documentado.

*NSGRASPxLD EXTERNO INSTANCIAS PYTHON
En este archivo se encuentra la programación del algoritmo NSGRASPxLD documentado.

*CONJUNTO DE INSTANCIAS
La capeta de instancias contiene 12 archivos de excell donde se encuentran las instancias modificadas de Barreto y Prodhon para el problema propuesto

Número 	Nombre		Autor Clientes Instalaciones Etiqueta
1	Coord20-5-1b	Prodhon	20	5	Instancia 1
2	CoordGaspelle	Barreto	21	5	Instancia 2
3	CoordGaspelle4	Barrteo	32	5	Instancia 3
4	CoordGaspelle6	Barreto	36	5	Instancia 4
5	CoordChrist50	Barreto	50	5	Instancia 5
6	Coord50-5-1	Prodhon	50	5	Instancia 6
7	Coord50-5-1b	Prodhon	50	5	Instancia 7
8	Coord20-5-2	Prodhon	50	5	Instancia 8
9	CoordDas88	Barreto	88	8	Instancia 9
10	Coord100-5-1	Prodhon	100	5	Instancia 10
11	Coord100-10-1	Prodhon	100	10	Instancia 11
12	CoordChrist100	Barreto	100	10	Instancia 12

*FRENTE DE PARETO REALES
El documento tiene la programación en python para escoger las soluciones que pertenecen al frente de pareto real por cada instancias
teniendo en cuenta uno archivo de todas las soluciones encontradas

*MÉTRICAS

Este documento tiene la programación en pytohn para calcular las métricas DG y MS, ya que requiere de muchos pasos y procedimiento, en cambio las otras métricas
fueron calculadas en excel.
