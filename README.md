# Introducción a las Ciencias Ómicas


PROPÓSITO DE LA UNIDAD DE APRENDIZAJE:

Aplica los conocimientos en microbiología, biología molecular, bioquímica y bioinformática aprovechando los recientes avances en la secuenciación masiva de biomoléculas e identificación de metabolitos y con un enfoque holístico.
.

INSTRUCTOR:

**Dr. Juan Alfredo Hernández García, PhD.**
Laboratorio de Biología Molecular de Bactterias y Levaduras
Departamento de Microbiología
Escuela Nacional de Ciencias Biológicas
Intituto Politécnico Nacional

[https://github.com/Microfred](https://github.com/Microfred)
[Youtube](https://www.youtube.com/channel/UC57RtU6eRvWAV9GRi7lZ7pw)


## Objetivos

El **objetivo general es** brindar a los y las alumnas las herramientas computacionales de software libre, mejores prácticas y metodologías de reproducibilidad de la ciencia para efectuar, documentar y publicar proyectos bioinformáticos de análisis genómicos.

Los **objetivos particulares** son:

1.	Introducir a los y las alumnas en los principios de investigación reproducible y metodologías para organizar proyectos bioinformáticos
2.	Introducir a los alumnos a bash (R y git)
3.	Presentar a los alumnos los tipos de datos genéticos producidos por la secuenciación masiva (Next Generation Sequencing)
4.	Introducir a los y las alumnas al análisis de datos genómicos y genomas reducidos
5.	Revisar  a  nivel teórico y  práctico los  métodos  bioinformáticos  clásicos  de  análisis secuencias genómicas


## Dinámica del curso

### ¿Cómo serán las clases?

* Teóricas y prácticas en medida de lo posible
* Exposición + ejercicos y ejemplos en clase
* Todos los materiales de la clase los iremos subiendo/actualizando a GitHub conforme avance el semestre
* Dejaremos **lecturas** a casa antes o después de algunos temas. Es una muy buena idea sí leerlas.
* Ocuparemos Google Classroom para enviar tareas y hacer anuncios del curso. Para este momento ya debiste de haber recibido una invitación a tu correo.

* **¿Necesito una computadora?**

Sí, el curso que intento dar es teórico-práctico, por lo que se requiere traigan una laptop con Mac o GNU/Linux (**no** Windows, sorry, lo intenté varios semestres y es una pesadilla para todxs) o en su defecto traer una tablat  e instalar [termux!](https://play.google.com/store/apps/details?id=com.termux&hl=es_MX):

  -  [Docker](https://www.docker.com/) instalado y **FUNCIONANDO** (ocuparemos Docker dentro de un mes)


* **¿Necesito instalar algo más? Sí**
     1. Un editor de texto decente. Listo para la 2da clase. Recomendaciones:
         * Mac o Linux: [Atom](https://atom.io/)
         * Linux: [Gedit](http://sourceforge.net/projects/gedit/) u otro que te guste.
         
     2. Un editor de Markdown    
         * Mac: [MacDown](http://macdown.uranusjr.com/)
         * Mac o Linux: [Haroopad](http://pad.haroopress.com/) o [Typora](https://typora.io/)
         
     3. [R y RStudio](https://www.rstudio.com/products/rstudio/download/), vereémos si nos da tiempo de ver este tema.

     

 **Si van a tomar notas, que sean ahí o en un editor de Markdown, _¡nooooo en Word!_**.




### El curso está en el repositorio

El repositorio está dividido en un folder por Unidad. Dentro de cada folder subiremos los apuntes y código utilizado en cada clase conforme los vayamos viendo en el semestre, así como los enlaces a las tareas.

Las notas de este repositorio están escritas en formato **Markdown** y, como notarás, el repositorio se encuentra hospedado en **GitHub**.

Cubriremos ambas herramientas en el curso, pero en resumen:

* Markdown es un procesador texto-a-HTML que de forma sencilla permite formatear texto `así`. Esto es útil para resaltar los los comandos y los resultados de la terminal del resto del texto en los documentos de clase (y en foros de ayuda).

* GitHub es un repositorio web especializado en software (pero se puede subir cualquier texto, como este). La parte de arriba enlista los archivos y carpetas dentro del repositorio. La nota de texto a su derecha es el comentario que yo realicé al subir o modificar (*commit*) el archivo de mi computadora a GitHub. En la parte de abajo puedes leer el contenido de dichos archivos en formato html. Y si los bajas los verás en formato Markdown.

En este mismo repositorio de github están las versiones de cursos que hemos dado los años pasados. Cada curso está en una "rama" del repositorio (más adelante veremos qué es esto).



### Mecanismo de calificación

El curso se dividirá en secciones que se calificarán por separado:

**Unidades 1-3:**

* 70% Tareas. Aproximadamente una tarea por sesión. Todas las tareas tienen el mismo valor. Habrá tareas opcionales, que se suman a la calificación esta sección
* 20% Examen
* 10% Asistencia y participación 

**Unidad 4-5:**

* 10% Tareas. Todas las tareas tienen el mismo valor. Habrá tareas opcionales, que se suman a la calificación esta sección.
* 90% Proyecto de la Unidad 5.

**Unidad 6-8:**

100% Tareas. Aproximadamente una tarea por sesión. Todas las tareas tienen el mismo valor.

**Proyecto final OBLIGATORIO**

Será una presentación breve de 10-15 minutos de un tema que tú eligas, obviamente realcionado a las ciencias ómicas, el cual deberá contener:

* Introducción
* Obtjetivos
* Materiales y Métodos
* Resultados
* Discusión
* Conclusiónes
* bibliografía


**Copiar o plagiar (tareas, exámenes, trabajo final, lo que sea) es motivo suficiente para reprobarte sin lugar a discusión. (NOS VEMOS EN EL ETS)**

![](truestory.png)


## CONTENIDO DEL CURSO:

* I.	Conceptos generales e introducción a al programación
* II.	Genómica y Microbioma 
* III.	Transcriptómica
* IV.	Proteómica
* V.	Metabolómica e interactómica




#### Unidad 1 [Introducción a la programación](https://github.com/Microfred/IntroBioinfo)


* Historia y evolución de la genómica
* Aplicaciones de la genómica
* Transcripción y traducción
* Regulación de la transcripción
* Regulación de la traducción
* Regulación postraduccional
* Genómica y sus derivados
* Código en computación
* Cómo buscar ayuda (permanentemente)
* Introducción a la consola y línea de comando de bash y R
* Funciones básicas de navegación y manejo de archivos con bash



**Sesión 2: Introducción a los scripts y grep**

* Funciones básicas de exploración de archivos con bash
* Comándos básicos en BASH
* Regular expressions y búsqueda de patrones (grep)
* Redirección con bash

**Sesión 3: Continuación de bash**

* Introducción a los scripts
* Loops (Bucles) con bash
* R y RStudio
* Funciones básicas de R más importantes para bioinformática


#### Unidad 2. Genómica y pangenómica

**Sesión 1 Generación y QC de datos NGS**

* Técnicas de secuenciación
* Errores de secuenciación
* Formatos fastq, bam, vcf
* Análisis básicos de calidad

**Sesión 2 Alineamiento de lecturas de secuenciación** 

* Limpieza de datos crudos
* Alineamiento contra un genoma de referencia

**Sesión 3 Pangenómica y Filogenómica**

* Evolución
* Métodos de análisis en la reconstrucción filogenética
* Pangenómica

#### Unidad 3. Metagenómica y metabarcoding

**Sesión 1 Generación y QC de datos NGS**

* Técnicas de secuenciación
* Errores de secuenciación
* Formatos fastq, bam, vcf
* Análisis básicos de calidad

**Sesión 2 Ensamble y Anotación de genomas**

* Métodos de esnsamble (Overlaping-Graphos de Bujin)
* Anotación de *de novo*
* Anotación referenciada
* Búsqueda de ortólogos

**Sesión 3 Pangenómica**

* Genes ortólogos, parálogos, homología
* genoma núcleo, genoma accesorio, genes únicos
* 


#### Unidad 4. Transcriptómica

+ (VIdeo!)[]


#### Unidad 5. Protéomica e Interactómica
(VIdeo!)[https://www.youtube.com/live/MHWfV3drR_0?si=eYeK4rJ-VGwgAjCF]

#### 	Unidad 6. Modelamiento de proteínas y Docking

#### Trabajo en casa en proyectos finales y tareas
 Se dará seguimiento online al proyecto de las unidades 1-5 con las herramientas de la Unidad 2 y se dejarán tareas para mantener la práctica de las unidades anteriores

#### Unidad 6 [Introducción a la genómica y secuenciación de siguiente generación](Unidad6/Unidad6_IntroGenomica_NexGenSeq.md)



#### Unidad 7 [Análisis de transcriptomas](Unidad7/Unidad7_Analisis_de_Transcriptomas.md)

**Sesión 1 Expresión diferencial**

* Diseño experimental
* Análisis de expresión diferencial

**Sesión 2 Análisis funcional**

* Clustering
* Enriquecimiento funcional


**Sesión 3 RNA-seq**

* Generación de datos RNAseq
* Modelamiento de datos
* Software

### Unidad 8 [Aplicaciones de NGS](Unidad8/Unidad8_Aplicaciones_de_NGS.md)
**Sesión 1 Metagenómica**
* Secuenciación de amplicones
* Barcoding
* Metabarcoding

**Sesión 2 Ensamblaje de representación reducida de genomas**

* Metodologías de representación reducida de genomas (RAD, GBS, etc)
* Ensamblaje de novo vs. sobre una referencia
* Principales algoritmos y software (Stacks, pyRAD, Tassel)
* Uso de replicados para informar el ensamblaje
* Primera inspección de los datos

#### Unidad 9 Análisis genómicos reproducibles en la nube

**Sesión 1**
* Terra
* pipelining en la nube

**Sesión 2**

* Mejores prácticas de GATK
* workflow GVCF
* Jupyter
* WDL

**Sesión 3**
* Variantes somáticas con Mutect2
* Variantes en número de copias con GermlineCNVCaller
