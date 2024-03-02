# Clínica Oftalmológica

## PLANIFICACIÓN: CONTEXTUALIZACIÓN
### OBJETIVOS INICIALES ANTES DE REALIZAR LA ENTREVISTA:	


Hace tiempo mi tío me comunicó que compró un servidor y solicitó los servicios de una empresa para la elaboración de una página web que mostrara información de su clínica de oftalmología.

Cuando vi dicha página, me di cuenta de que podría ofrecer más servicios que solo mostrar la información de la consulta.

**Objetivos Iniciales:** 
- Mejorar el diseño de la mejorando como consecuencia la usabilidad de la misma.
- Implementar una **base de datos que almacene como usuarios a los diferentes clientes y les muestre información particular**, indicando por ejemplo los factores de riesgo que deben evitar según sus enfermedades, información sobre su enfermedad, fechas de su consulta y diagnósticos de las mismas...
- Gracias a la base de datos anterior podremos almacenar datos de los clientes que nos servirán para **gestionar de manera eficiente el fechado de las consultas de los mismos en función del riesgo de sus diferentes enfermedades**.
- A la hora de solicitar cita previa, la pestaña que aparece da lugar a ambigüedades, **quizás el implementar un selector de opciones posibles ayudaría a ser más específico** y a prever de manera sencilla la gravedad de la situación.

### CONCLUSIONES DE LA ENTREVISTA:	
Después de charlar con mi tío, hemos llegado a la conclusión de que mostrar el historial médico de un cliente aunque lo hagamos accediendo mediante usuario y contraseña podría poner en peligro su privacidad. **Por lo que descartamos el mostrar información de su historial médico particular.**

También ha recalcado que: 
-	El sitio web debe **ser sencillo, en un principio,** con el objetivo de atraer clientes potenciales que no tienen mucho conocimiento de la materia.
-	Tiene que tener un **diseño simple, moderno y que inspire confianza** al cliente con el objetivo de retenerlo. Es decir el diseño debe **inspirar confianza al usuario.**
-	Aunque no debe tener demasiados terminos técnicos, tiene que **dar a conocer que la clínica posee herramientas específicas para realizar algunos tipos de operaciones.**

  

### OBJETIVOS MARCADOS EN FUNCIÓN DE LA INFORMACIÓN DE LA ENTREVISTA 

Después de haber estudiado el segundo bloque del temario y de haber comprendido los conceptos del mismo se me han ocurrido **nuevos objetivos que debe tener el sistema hipermedia:**

- **El objetivo principal en el que se centra el sitio web:** es mostrar información sobre la clínica para atraer nuevos clientes.

- **Contar con un sistema de recomendación de contenidos y de muestreo de información adaptativo:** este sistema adaptara la estructura del hiperdocumeto, en función de la navegación del usuario. (Esto conseguira evitar la sobrecarga de información, es decir, que los usuarios rechacen la navegación del mismo debido a su complejidad inicial. Y permite que los usuarios más experimentados que busquen información más específica ). Es decir:
	- Para **usuarios que visiten la página por primera vez** mostrará información más orientativa: 
		- Dirección de la clínica.
		- Número de teléfono de contacto.
		- Correo electrónico.
		- Horario de atención.
		- Información sobre el equipo médico con el que cuenta la clínica: oftalmólogos, optometrístitas, tecnologías y equipos...
		- Servicios que ofrece la clínica: como exámenes de vista, cirugía ocular...
		- Procedimientos y Tratamientos.
		- Información educativa de interés.
		- Seguros aceptados.
		- Testimonios y casos de éxito.
		- Galería de Instalaciones.
		- Política de Privacidad.

	- Para los **usuarios que no son nuevos en la página**: 
		- Se le ofrecerán recomendaciones en función de la navegación que hayan realizado.

	- Para los **usuarios registrados en la base de datos**:
		- Mostrará alertas para notificarle que ha pasado mucho tiempo sin realizarse una revisión. 

- **Tener una base de datos de los clientes**, que almacene: 
	- **Nombre, Apellidos.** 
	- **Correo Electrónico:** También podríamos enviar un correo electrónico cuando el usuario lleve mucho tiempo sin revisarse la vista.
	- **DNI:** Utilizaremos el DNI para ubicar al usuario y **mostrarle  un mensaje de alerta cuando lleve mucho tiempo sin revisarse la vista**.

- **En la base de datos podríamos diferenciar entre usuarios cliente y usuarios trabajadores:** permitiendo al propietario de la clínica o jefes colgar tareas a sus empleados.


![Imagen de prueba](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/Imagen%20Barra.JPG?raw=true)


## PLANIFICACIÓN: EXAMINANDO SITIO WEB

### TEST HEURÍSTICO 1: [VISIOON](https://visioon.es/clinica-oftalmologica-jaen/)

#### 1.	GENERALES

Los objetivos concretos y bien definidos del sitio web son: por un lado, informar sobre la clínica y por otro lado conseguir que esos usuarios se conviertan en futuros clientes de la misma. 

La URL no es fácil de recordar ya que el sitio web pertenece a un sitio web mas grande y la URL del mismo depende de la del padre: https://visioon.es/clinica-oftalmologica-jaen/.


En general la estructura del sitio web está orientada en el usuario. Pero tiene algunos fallos: 
-	En la barra principal parecen términos que un usuario sin conocimientos de medicina no podría entender. Por lo que es información innecesaria o mal estructurada. Puede hacer que el usuario pierda el interés de seguir navegando por el sitio.



![Captura del Menú Desplegable](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/imagen%20barra%20dos.JPG?raw=true)


![Captura del Submenú de Otras Patologías](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/Imagen%20otras%20patologias.JPG?raw=true)

![Captura del Submenú de nuestras clínicas](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/imagen%20nuestra%20clinica.JPG?raw=true)



 
Es evidente que han situado dichas patologías en la barra principal porque son las más comunes. Pero pienso que para un usuario que no había visitado el sitio web con anterioridad sería de mayor utilidad la información sobre la clínica que sobre el tratamiento de patologías concretas.

El sitio web no indica la fecha de actualización del mismo. Pienso que es porque no se actualiza con mucha frecuencia.

El sitio web es reconocible y su look&feel corresponde con el objetivo de atraer nuevos clientes ya que induce al usuario a pensar que es una clínica moderna y fiable, solo con el aspecto de la página web. También es reconocible ya que aporta una apariencia más trabajada que la de sus competidores y más funcionalidades e información adicional.

#### 2.	IDENTIDAD E INFORMACIÓN 
El logotipo es reconocible, significativo y suficientemente visible. Destaca frente a los logotipos de sus competidores.
 
![Logotipo](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/imagen%20logo.JPG?raw=true)

Proporciona información sobre el web master, sobre la protección de datos de carácter personal de los clientes y de los derechos de autor de los contenidos del sitio web en el pie de página.

![Derechos de Autor](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/imagen%20copyright.JPG?raw=true)
 

#### 3.	LENGUAJE Y REDACCIÓN
El sitio web intenta suprimir términos que podrían no entender los usuarios promedio. Utiliza un lenguaje amigable, familiar y cercano.
#### 4.	ROTULADO

#### 5.	ESTRUCTURA Y NAVEGACIÓN
La estructura de esta página se basa en una barra inicial que agrupa los contenidos en categorías principales y dentro de esas categorías principales en subcategorías.
 
#### 6.	LAYOUT DE LA PÁGINA
#### 7.	BÚSQUEDA (EN CASO DE SER NECESARIA)
#### 8.	ELEMENTOS MULTIMEDIA
#### 9.	AYUDA
#### 10. ACCESIBILIDAD
#### 11. CONTROL Y RETROALIMENTACIÓN

#### 12. HEURÍSTICOS ESPECÍFICOS
#### 12.1 INFORMA SOBRE LOS TRATAMIENTOS DE LOS QUE DISPONE LA CLÍNICA
#### 12.2 MUESTRA EL TELEFONO, MAIL, HORARIO DE LA CLÍNICA.
#### 12.3 MUESTRA LOS SEGUROS QUE TRABAJAN CON LA CLÍNICA.
#### 12.4 PRESENTA UNA DESCRIPCIÓN DEL PERSONAL DE LA CLÍNICA.
#### 12.5 MUESTRA LAS DIFERENTES OPINIONES DE LOS CLIENTES.
#### 12.6 EXISTE LA POSIBILIDAD DE ACCEDER A LAS REDES SOCIALES DE LA CLÍNICA.
#### 12.7 PRESENTA INFORMACIÓN SOBRE EL EQUIPO MÉDICO QUE CUENTA LA CLÍNICA.
#### 12.8 PRESENTA INFORMACIÓN EDUCATIVA DE INTERÉS.
#### 12.9 PRESENTA UNA GALERÍA CON FOTOS DE LAS INSTALACIONES DE LA CLÍNICA.
#### 12.10 PRESENTA COMPROBANTES DE CALIDAD DE LA CLÍNICA O GALARCIONES DE LA MISMA.
#### 12.11 PRESENTA UN FORMULARIO PARA QUE LA CLÍNICA OBTENGA LOS DATOS DE LOS USUARIOS.


### PROPUESTAS DE SOLUCIÓN


### CARACTERÍSTICAS PARTICULARES DE INTERÉS
