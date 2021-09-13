# Challenge-4-JAVA

Proyectos

En la empresa que usted labora, se desea tener un control de los proyectos y personal que labora en la organización, por lo que usted implementará una base de datos que contendrá la información de los empledos, clientes y proyectos de la siguiente manera:

Diagrama entidad relacion

Reto 4

3.1 Crear los siguientes Contenidos (exactamente):

EMPLEADO
código 1, Carlos Perez, cc, 123456, cperez@test.com, 310 555 5555, 4500000
código 2, Andrea Herrera, ce, 654789, aherrera@test.com, 315 666 6666, 4600000
código 3, Pedro Contreras, Passport. 45123, pcontreras@test.com, 310 444 4444, 4300000

Código 4, Paola Perez, cc, 654123, pperez@test.com, 314 456 1234, 4200000
código 5, Carolina Herrera, cc, 789456, cherrera@test.com, 456 4478, 4300000

 

CLIENTE:

Código 1, Tigo, 900806921, Juan Cárdenas, comunicaciones

Código 2, Ecopetrol, 900806922, Manuela González, gaseoductos

 

PROYECTO:

Código 1, 1, “Puesta en marcha de aplicación móvil de todos los clientes tigo”, 5, 600000000,2021/01/01,2021/02/01,2021/08/01

Código 2, 2, “Desarrollo de seguridad de oleoductos”,4,900000000, 2020/09/15,2020/09/20,2021/03/01

Código 3, 2, “Gestor documental sede Bogotá”, 4,850000000, 2020/12/15,2020/01/01,2021/09/01

 

ASIGNACION:

Código 1, 1, “Gerente”,1,2021/01/05, 2021/08/05

Código 2, 2, “Gerente”,2, 2020/09/25,2021/03/05

Código 3, 1, “Gerente”,3, 2020/12/15, 2021/10/01


5. Código SQL para realizar las siguientes consultas:

5.1 Mostrar la información del objetivo del proyecto junto al apellido de su vendedor ordenadas alfabéticamente por objetivo del proyecto con los títulos 'Objetivo' y 'Apellidos Vendedor'.

5.2. Mostar el valor total de los proyectos asignados a Andrea Herrera como Gerente, con titulo 'Valor total asignado a Andrea'.

5.3 Mostrar el valor toral de las ventas de Paola Perez con el titulo Ventas de Paola.

NOTA: Generar un archivo script sql para las consultas. Antes de cada consulta escribir SELECT 'Consulta #';  donde # es el número de la consulta.


Ejemplo:

Select 'Consulta 1';
Select titulo from ....;
Select 'Consulta 2';
Select .....;
Select 'Consulta 3';
Select .....;

ENTREGA

Para la entrega es necesario:

1. Subir cada uno de los archivos .sql en orden de ejecución. Es decir, primero se suben las tablas que no tienen Referencias (Llaves foráneas) y luego las demás. 
2. Luego de subir los scripts de sql de creación e inserción de datos, se debe subir el de actualizaciones y por último el de consultas. 
3. Luego se evalúa, igual que con los retos anteriores. Si todo esta correcto, tanto las inserciones y las consultas, se obtendrá una nota de 5/5. Si hay un error la evaluación será 0. Por lo que será necesario que revisen hasta que las salidas sean las correctas

