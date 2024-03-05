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
El sitio web intenta suprimir términos que podrían no entender los usuarios promedio, pero sin éxito. Como hemos dicho antes el menú desplegable principal contiene términos que no tedría porque conocer un usuario común.

Utiliza un lenguaje amigable, familiar y cercano.



#### 4.	ROTULADO

El rotulado de la página es correcto.

#### 5.	ESTRUCTURA Y NAVEGACIÓN
La estructura de esta página se basa en una barra inicial que agrupa los contenidos en categorías principales y dentro de esas categorías principales en subcategorías.

![Captura del Menú Desplegable](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/imagen%20barra%20dos.JPG?raw=true)


![Captura del Submenú de Otras Patologías](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/Imagen%20otras%20patologias.JPG?raw=true)

![Captura del Submenú de nuestras clínicas](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/imagen%20nuestra%20clinica.JPG?raw=true)

- La estructura de organización y navegación sigue las convenciones o la estructura de las demás paginas con los mismos objetivos.
- Los enlaces son reconocibles como tales ya que cambian de color.

- Estan todos los nodos comunicados.

- En los menus de navegación no se ha controlado el número de elementos y términos.

![Captura del Submenú de nuestras clínicas](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/imagen%20nuestra%20clinica.JPG?raw=true)

- No existen elementos de navegación que orienten al usuario acerca de dónde está y cómo deshacer su navegación: una opción viable serían las migajas. Aunque creo que no se proporciona dicha ayuda a la navegación porque el sitio web es muy amplio, es decir, no es posible perderse a nivel de profundidad. Sin embargo, al ser tan amplio el usuario deberá realizar un proceso mental para decidir entre tantas posibles opciones, lo que puede hacer que pierda el interés de seguir navegando en el sitio web.

- Se ha evitado la redundancia de enlaces.

- El sitio web no ofrece la posibilidad de que los enlaces le den al usuario el chivatazo que le permitiría conocer de que trata la información que contiene el enlace antes de clicarlo.

- Se ha controlado que no haya páginas web "huerfanas".

- El usuario puede disfrutar de todos los contenidos del sitio web sin necesidad de tener que descargar e instalar plugins adicionales.



 
#### 6.	LAYOUT DE LA PÁGINA

- Se evita la sobrecarga informativa, destacando lo más importante del texto. Igual podríamos reducir los textos que aparecen.

![Texto de Ejemplo](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/texto%20de%20ejemplo.JPG?raw=true)

#### 7.	BÚSQUEDA (EN CASO DE SER NECESARIA)

No ofrece herramientas de búsqueda.
#### 8.	ELEMENTOS MULTIMEDIA

El uso de imágenes induce al usuario a confiar más en el sitio web y en la empresa. Pero hay algunas fotografías que no tienen que ver con el producto que se presenta.

![Imagen que no tiene que ver con el producto ofrecido](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/clinica-vision/fotografia%20que%20no%20tiene%20quever.JPG?raw=true)

#### 9.	AYUDA
#### 10. ACCESIBILIDAD

- El tamaño de la fuente es lo suficientemente grande como para no dificultar la legibilidad del texto.

- El tipo de fuente y los efectos tipográficos, ancho de línea y alineación empleados facilitan la lectura.

- Existe un alto contraste entre el color de fuente y fondo.

- Las imagenes no incluyen atributos 'alt' que describan su contenido.

- Es compatible con diferentes navegadores y además con diferentes resoluciones de pantalla.

#### 11. CONTROL Y RETROALIMENTACIÓN



#### PROPUESTAS DE SOLUCIÓN

#### CARACTERÍSTICAS PARTICULARES DE INTERÉS

### TEST HEURÍSTICO 2: [VISIOON 2](https://oftalmologojaen.com/)

#### 1.	GENERALES

Los objetivos de este sitio web, son los mismos que los de los anteriores. Pero la cantidad de información es mucho menor, es decir, se limita a presentar la información esencial. La URL es mucho más fácil de recordar que la de la página anterior. Pero no presenta el nombre de la empresa: 'oftalmologojaen.com'. 

La organización del sitio web es demasiado simple y no está orientada al usuario. Seguramente hayan creido que no era necesario estructurar la información ya que no hay mucha cantidad.

El look&feel no se corresponde con los objetivos, características, contenidos y servicios del sitio web. No incita al usuario a confiar en la empresa.

No es coherente el diseño del sitio web, se limita a una sola página principal carece de estructura y los colores que utilizan no siguen las convenciones que siguen sitios del estilo.

No es reconocible el diseño general del sitio web.

El sitio web no se actualiza periodicamente.

![Página Principal](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/visioon2/pagina%20principal.png?raw=true)

#### 2.	IDENTIDAD E INFORMACIÓN 

Se muestra claramente la identidad de la empresa a través de todas las páginas.

El logotipo es suficientemente visible, identificable y significativo.

![Logotipo](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/visioon2/logotipo.png?raw=true)


Se proporciona información sobre los derechos de autor.

![Derechos de Autor](https://github.com/juanblack/SIWEB2024-ClinicaOftalmologica-jcvc0006/blob/main/Imagenes%20Readme/visioon2/politica%20de%20privacidad.png?raw=true)

#### 3.	LENGUAJE Y REDACCIÓN

La web habla el mismo lenguaje que sus usuarios. El lenguaje es más claro y conciso que el de la página anterior.

#### 4.	ROTULADO
#### 5.	ESTRUCTURA Y NAVEGACIÓN 

La estructura y navegación no es la más adecuada ya que a pesar de ser un sitio simple y sin mucha información. La página no aprovecha las propiedades de los hipertextos para organizar dicha información.

#### 6.	LAYOUT DE LA PÁGINA

Se aprovechan las zonas de alta jerarquía informativa de la página para contenidos de mayor relevancia. Se ha evitado la sobrecarga informativa reduciendo la información a estrictamente lo esencial. No se ha controlado la longitud de la página.

#### 7.	BÚSQUEDA (EN CASO DE SER NECESARIA)

No proporciona herramientas de búsqueda.

#### 8.	ELEMENTOS MULTIMEDIA
#### 9.	AYUDA
#### 10. ACCESIBILIDAD
#### 11. CONTROL Y RETROALIMENTACIÓN

#### PROPUESTAS DE SOLUCIÓN

#### CARACTERÍSTICAS PARTICULARES DE INTERÉS

### TEST HEURÍSTICO 3: [GALLEGO](https://oftalmologosgallego.es/)

#### 1.	GENERALES
#### 2.	IDENTIDAD E INFORMACIÓN 
#### 3.	LENGUAJE Y REDACCIÓN
#### 4.	ROTULADO
#### 5.	ESTRUCTURA Y NAVEGACIÓN 
#### 6.	LAYOUT DE LA PÁGINA
#### 7.	BÚSQUEDA (EN CASO DE SER NECESARIA)
#### 8.	ELEMENTOS MULTIMEDIA
#### 9.	AYUDA
#### 10. ACCESIBILIDAD
#### 11. CONTROL Y RETROALIMENTACIÓN


#### PROPUESTAS DE SOLUCIÓN

#### CARACTERÍSTICAS PARTICULARES DE INTERÉS

### TEST HEURÍSTICO 4: [CLÍNICA REMENTERÍA](https://pidecita.clinicarementeria.es/)

#### 1.	GENERALES
#### 2.	IDENTIDAD E INFORMACIÓN 
#### 3.	LENGUAJE Y REDACCIÓN
#### 4.	ROTULADO
#### 5.	ESTRUCTURA Y NAVEGACIÓN 
#### 6.	LAYOUT DE LA PÁGINA
#### 7.	BÚSQUEDA (EN CASO DE SER NECESARIA)
#### 8.	ELEMENTOS MULTIMEDIA
#### 9.	AYUDA
#### 10. ACCESIBILIDAD
#### 11. CONTROL Y RETROALIMENTACIÓN


#### PROPUESTAS DE SOLUCIÓN

#### CARACTERÍSTICAS PARTICULARES DE INTERÉS

## ANTEPROYECTO DEL SITIO WEB

## Título del Proyecto: Clínica Oftalmológica

## Descripción del Proyeto: 

El proyecto consiste en elaborar un sitio web, para una clínica oftalmológica, con los siguientes objetivos: 

## Descripción de la organización o institución: 

## Tipo de Proyecto

## Propósito

## Objetivos

## Palabras clave

## Metodología

## Resultados esperados

## Requisitos Hardware y Software

## Bibliografía

## Documentación
