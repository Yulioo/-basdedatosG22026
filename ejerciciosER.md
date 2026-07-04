# Ejercicios del Modelo E-R


## Ejercicio 1.

Un hospital registra información de sus pacientes:

> De cada Paciente se almacena:
- Numero de paciente que lo identifica
- Nombre
- Fecha de Nacimiento

> De cada Expediente Médico se almacena:
- Número de expediente
- Fecha de Apertura
- Tipo de Sangre

> Reglas del Negocio
1. Cada paciente debe tener exactamente un expediente medico
2. Cada expediente médico pertenece a un unico paciente
3. No puede existir un expediente sin paciente
4. No puede existir un paciente sin expediente

> Que se debe realizar:

- Identificar las entidades
- Identificar atributos
- Dibujar las relaciones
- Determinar la cardinalidad
- Determinar la participación de cada identidad


![Ejercicio1](../basededatos/img/ER/ej1.jpeg)





## Ejercico 2.

Una universidad administra profesores y cursos

> De cada profesor se almacena:

- El número de profesor o id
- Nombre
- Especialidad

> De cada curso se almacena:

- numero de curso
- nombre del curso
- creditos (cuanto vale esa materia)

> Reglas el negocio

1. Un profesor puede impartir varios cursos
2. Un curso solamente puede ser impartido por un profesor
3. Puede existir un profesor que actualmente no importa cursos
4. Todo curso debe estar asignado a un profesor


![Ejercicio2](../basededatos/img/ER/ej2.jpeg)




## Ejercicio 3.

Una escuela administra alumnos y materias

> De cada alumno se almacena:

- Matricula
- Nombre
- Semestre

> De cada materia se almacena:

- Clave de la materia
- Nombre de la materia
- Creditos

> Reglas del negocio

1. Un alumno puede inscribirse en varias materias
2. Una materia puede tener muchos alumnos inscritos
3. Puede existir una materia sin alumnos inscritos
4. Todo alumno debe estar inscrito en al menos una materia
5. De cada inscripcion se desea almacenar:
    - Fecha de inscripcion
    - Calificación Final
Nota: a la relacion nombrarla **INSCRIBE**


![Ejercicio3](../basededatos/img/ER/ej3.jpeg)





## Ejercicio 4.

Una empresa dedicada a la ventas al por mayor necesita registrar lo siguiente:

> Para los clientes:

- Numero de cliente
- Noombre (el cual es una persona moral)

> Pedidos

- Número de pedido
- Fecha de Pedido

> Productos:

- Numero de producto
- nombre
- precio

> Reglas del Negocio

1. Un cliente puede realizar muchos pedidos
2. Cada pedido pertenece a un solo cliente
3. Un pedido contiene varios productos
4. Un producto puede aparecer en muchos pedidos
5. Un pedido debe contener al menos un producto
6. Un producto puede no haber sido vendido
7. El detalle del pedidono existe sin pedido
8. El detalle del pedido no existe sin producto
9. El detalle almacena la cantidad vendida y el precio de venta


![Ejercicio4](../basededatos/img/ER/ej4.jpeg)




## Ejercicio 5.

1. La empresa está organizada en departamentos. Cada departamento tiene un nombre único, un número único y un empleado específico que administra el departamento.Se registra la fecha de inicio en la que ese empleado comenzó a administrar el departamento. Un departamento puede tener varias ubicaciones.

2.Un departamento controla varios proyectos, cada uno de los cuales tiene un nombre único, un número único y una sola ubicación.

3. Almacenamos el nombre de cada empleado, número de Seguro Social, dirección, salario, sexo (género) y fecha de nacimiento. Un empleado está asignado a un solo departamento, pero puede trabajar en varios proyectos, los cuales no necesariamente son controlados por el mismo departamento. Registramos el número actual de horas por semana que un empleado trabaja en cada proyecto. También registramos el supervisor directo de cada empleado (quien es otro empleado).

4. Queremos llevar un registro de los dependientes de cada empleado para fines de seguro. Registramos el nombre de pila de cada dependiente, sexo, fecha de nacimiento y parentesco con el empleado.

![Ejercicio5](../basededatos/img/ER/ej5.jpeg)
