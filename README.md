# Control-de-asistencias-hospital-
CONTROL DE ASISTENCIAS DE UN HOSPITAL Y VACACIONES 

1.- Datos del Empleado:

Nombre completo

(ID) del empleado

Edad

Fecha de nacimiento 

Cedula 

Domicilio

Telefono 

Correo

Fecha de ingreso

Genero:
-Masculino
-Femenino

Puesto:
-medico
-enfermero
-limpieza
-seguridad
-administrativo 

Grado de Estudio:
-Secundaria
-Preparatoria
-Licenciatura
-Doctorado

Tipo de Contratación:
-Basificados
-Homologados
-Regularizados
-Contrato


2.-Turno y Horario 

(ID) del empleado al ingresar tus registros 

Turno:
-Matutino 07:00 - 14:30
-Vespertino 14.00 - 20:30 
-Nocturno 20:00 - 07:30 

Jornada: 
-A:Lunes, Miercoles, Viernes 
-B:Martes, Jueves, Sabado
-C:Domingo

Hora de entrada (00:00)

Entrada (dd/mm/yyyy)



3.-Registro de asitencia diaria:

Asistió(Presente)

Falto(Ausente)

Retraso(Opcional)

Esta de vacaciones

Dia libre



4.-Vacaciones:

-Cada trabajador tiene derecho a ciertos días de vacaciones por año ( por ejemplo: 15 días ) dentro de ello hay dos periodos que el primer periodo inicia de enero a junio y el segumdo periodo es de julio a diciembre 

primer periodo: 

ene - feb

feb - mar

mar - abr

abr - may

may - jun

jun - jul

segundo periodo:

jul - ag

ago - sep

sep - oct

oct - nov

nov - dic

Saber que días ya lo ha usado

Marcar esos dias como "VACACIONES" en el registro

Dentro de dichas vacaciones tenemos dos periodos que son de enero a junio y de julio a dicienbre que abarca 15 dias de descanso 



5.-Control de fechas importantes tener en cuenta :

El calendario laboral( fines de semana, feriado)

Evitar que se registren vacaciones en días no laborales si no corresponden

Validar que las fechas ingresadas tengan sentido (inicio antes del fin)



VACACIONES(BOTONES-CLASS):

Este es un código que selecciona un empleado desde un menú, asigna un periodo de vacaciones y muestra la confirmación y este evita que otro trabajador elija su mismo periodo de vacaciones

Este código sirve para administrar y seleccionar vacaciones a empleados de una forma sencilla para administrar de forma de una interfaz visual.

Class Empleado:

Se define una clase llamada Empleado, las clases son moldes para crear objetos, representamos a cada empleado como un objeto con nombre y sus vacaciones.


Meses:
periodo 1: Ene, Feb, Mar, Abr, May, Jun
periodo 2: Jul, Ag, Sep, Oct, Nov, Dic


Generar:

Periodos del 1 al 15 para cada mes.

Periodos del 16 al 30 para cada mes.
