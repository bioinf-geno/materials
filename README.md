# Anuncios  

**20 julio -**  Les dejo las clases 7 y 8 [aquí](https://github.com/bioinf-geno/materials/raw/master/clase07_population_genetics.pdf) y [aquí](https://github.com/bioinf-geno/materials/raw/master/clase08_análisis_de_expresión_génica.pdf). Además, Consuelo nos va a presentar la próxima semana el artículo [***A comprehensive evaluation of normalization methods for Illumina high-throughput RNA sequencing data analysis***](http://bib.oxfordjournals.org/content/14/6/671.full).  
**13 julio -**  Ya tenemos los dos artículos que Daniel va a presentarnos el próximo lunes 18. El primero es [Convergent adaptation of human lactase persistence in Africa and Europe](https://github.com/bioinf-geno/materials/raw/master/tishkoff2006.pdf) y el segundo es [A highly abundant bacteriophage discovered in the unknown sequences of human faecal metagenomes](https://github.com/bioinf-geno/materials/raw/master/ncomms5498.pdf). Vengan preparados para discutir los artículos en detalle!  
**9 mayo -**  Estudiantes! La [segunda prueba](https://github.com/bioinf-geno/materials/blob/master/prueba02.md) de nuestro curso está lista para que Uds. comiencen a resolverla.  
**4 mayo -** Estimados estudiantes,  
El próximo 16 de mayo Daniel va a presentar el artículo [Schmitt, M.W., Kennedy, S.R., Salk, J.J., Fox, E.J., Hiatt, J.B. and Loeb, L.A., 2012. ***Detection of ultra-rare mutations by next-generation sequencing***. Proceedings of the National Academy of Sciences, 109(36), pp.14508-14513](https://github.com/bioinf-geno/materials/raw/master/schmitt_2012.pdf). Nuestra tarea es llegar preparados para discutir el artículo por lo que les recomiendo leer el texto principal al igual que el material suplementario.

**2 mayo -** Laboratorio de ensamblaje de genomas, evaluación y anotación  
En este práctico Uds. van a recibir un set de datos genómicos correspondientes a un genoma bacteriano. Deben "limpiar" las reads, ensamblarlas, comparar los resultados de ese ensamble, y finalmente anotar y visualizar. El producto de este laboratorio es un capítulo más en el GitBook que están preparando como proyecto de clase.  
Etapas en el práctico:  
- Descargar reads  [aquí](https://www.dropbox.com/s/qmtja3ollqbqcml/reads.zip?dl=0) (1.4 GB)
- Realizar control de calidad --> cortar extremos 3´ de baja calidad, eliminar reads con N´s, eliminar reads cuyo puntaje de calidad promedio sea menor a cierto umbral, etc.  Les recomiendo para esto la herramienta [PrinSeq](http://prinseq.sourceforge.net).  
- Una vez que las reads están "limpias", pueden proceder con el ensamblaje. Aquí conviene probar al menos dos herramientas. Les recomiendo [SPAdes](http://spades.bioinf.spbau.ru) y [MaSurCa](http://www.genome.umd.edu/masurca.html)  
- El siguiente paso es comparar los ensamblajes producidos por ambos programas. Una herramienta muyusada para esto es [QUAST](http://quast.bioinf.spbau.ru)  
- Finalmente, la anotación genómica es lo que le va a dar sentido a esto al definir dónde están los genes, qué funciones codifican y cómo. En este caso les recomiendo anotar con [Prokka](https://github.com/tseemann/prokka) y con [eggNog](http://eggnogdb.embl.de/#/app/home).  

**2 mayo -** [Diapos clase 06](https://github.com/bioinf-geno/materials/raw/master/clase06a_phylo.pdf)  
**24 abril -** Estimados estudiantes,
Mañana aprovecharemos a ponernos al día y a revisar su avance con respecto a los laboratorios. El martes voy a presentar un artículo sobre [Single-Cell Genomics](https://github.com/bioinf-geno/materials/raw/master/Gawad_2016.pdf) bien interesante sobre esta tecnología emergente. 
Nos vemos!  
**19 abril -** [Diapos clase 05](https://github.com/bioinf-geno/materials/raw/master/clase05_comparative_genomics.pdf)  
**11 abril -** [Diapos clase 04](https://github.com/bioinf-geno/materials/raw/master/clase04_genomics_assembly.pdf)  
**10 abril -** Estudiantes! Consuelo realizará una presentación este martes sobre un tema súper relevante en genómica, i.e., el uso de librerías de representación reducida en genomas de organismos no modelo. El paper es: [RAD-Seq: Nathan A. Baird et al., “Rapid SNP Discovery and Genetic Mapping Using Sequenced RAD Markers,” PLoS ONE 3, no. 10 (October 13, 2008): e3376, doi:10.1371/journal.pone.0003376.](http://journals.plos.org/plosone/article/asset?id=10.1371%2Fjournal.pone.0003376.PDF)  
**5 abril -**  Estudiantes! La primera prueba de nuestro curso está lista para que Uds. comiencen a resolverla.  
[Prueba 01](https://github.com/bioinf-geno/materials/blob/master/prueba01.md)  
**3 abril -**  Estimados estudiantes, en el próximo laboratorio vamos a explorar herramientas para alineamientos múltiples en R. El laboratorio consiste en usar funciones en R para descargar genes de interés, usar el paquete msa para alinear estas secuencias, y finalmente usar el paquete DECIPHER para diseñar partidores. Esta vez el laboratorio no será tan estructurado como una guía paso a paso para que Uds. desarrollen la capacidad de resolver un problema concreto en R independientemente. Por supuesto, cualquier consulta que tengan no duden en contactarme.  
Los paquetes son:  
- [seqinR] (http://seqinr.r-forge.r-project.org/seqinr_2_0-7.pdf) - Para buscar e importar secuencias en R  
- [msa](http://www.bioconductor.org/packages/release/bioc/html/msa.html) - Para realizar un alineamiento múltiple. Ver ejemplo [aquí] (https://a-little-book-of-r-for-bioinformatics.readthedocs.org/en/latest/src/chapter5.html)  
- [DECIPHER](https://www.bioconductor.org/packages/release/bioc/vignettes/DECIPHER/inst/doc/DesignPrimers.pdf) - Para diseñar primers compatibles con un grupo de secuencias.  

#####Recuerden revisar los vínculos para descargar e instalar los paquetes apropiados  

**29 marzo -** [Diapos clase 03](https://github.com/bioinf-geno/materials/raw/master/clase03_genomics_aln.pdf)  
**28 marzo -** [Diapos lab 01](https://github.com/bioinf-geno/materials/raw/master/lab01.pdf)  
En este lab vamos a comenzar a trabajar en R/Bioconductor para el manejo de secuecnias de DNA  
**20 marzo -** [Diapos clase 02](https://github.com/bioinf-geno/materials/raw/master/lib.pdf)  
**19 marzo -** Daniel ya escogió un artículo para este martes y además vamos a tener otro para discutir entre todos. Daniel va a hacer una presentación de 30 minutos aproximadamente y después nos centraremos en la discusión del artículo. Yo voy a liderar la discusión esta vez y después vamos cambiando.  
- El artículo para la presentación está [aquí](https://github.com/bioinf-geno/materials/raw/master/seth-smith2013.pdf)  
- El artículo para la discusión está [aquí](https://github.com/bioinf-geno/materials/raw/master/nurk2013.pdf)  

Saludos

Eduardo  
**15 marzo -** Aparte de la clase, hoy también vamos a armar el calendario de presentaciones de artículos científicos. La idea es que escojamos artículos compilados por el biólogo computacional Lior Pachter ([Bits of DNA](https://liorpachter.wordpress.com/seq/)) relacionados con análisis funcionales basados en secuenciamiento masivo (High-Throughput Sequencing)  
**15 marzo -** [diapos clase 01](https://github.com/bioinf-geno/materials/raw/master/01_seq_technologies.pdf)  
**14 marzo -** **Revisa los vínculos más abajo para traer tu computador listo para la clase**

Para introducirte en R sigue los siguientes tutoriales (~25 minutos). Al completar estos tutoriales vas a estar en una mejor posición para comenzar con los prácticos más intensos.

- [Descarga R](https://www.r-project.org)
- [Instalando R](http://www.datacarpentry.org/R-genomics/00-before-we-start.html)
- [Introducción a R](http://www.datacarpentry.org/R-genomics/01-intro-to-R.html)

# Programa Bioinformática Genómica
Carrera : **Ingeniería en Bioinformática**

Asignatura : Bioinformática genómica (INB320)

Horas : 2 horas: lunes 10:20 – 12:00 horas.

2 horas: martes 12:10 – 13:50 horas.

Profesor responsable : Eduardo Castro (<eduardo.castro@unab.cl>; <castronallar@gmail.com>)

Horario de consultas : lunes 17:40 – 19:20 horas.

**COMPETENCIAS ALCANZADAS AL FINALIZAR EL CURSO**

El objetivo del curso es conocer los fundamentos teóricos detrás de la genómica computacional y su aplicación. El curso está diseñado de tal forma que el estudiante se exponga a 1) investigación de punta en el área, 2) algoritmos e implementaciones de software, y 3) que desarrolle experiencia directa.

Al término del curso, el estudiante exitoso habrá desarrollado la capacidad de analizar datos genómicos por si mismo, entender las opciones algorítmicas que se ajustan mejor a distintas situaciones experimentales, apreciar el estado del arte en esta disciplina.

**EVALUACIONES**

-   **Pruebas escritas** – 10% cada una; total 3 en el semestre = 30% de la nota de presentación al examen

-   **Presentaciones** – 25% de la nota de presentación al examen

-   **Proyecto de clase (programación en R)** – 30% de la nota de presentación al examen

-   **Discusión de artículos** – 15% de la nota de presentación al examen

-   **Examen** – 30% del total del curso

**CONTENIDOS Y CRONOGRAMA DE LA ASIGNATURA**

-   Técnicas de secuenciamiento de DNA: Sanger, HTS

-   Estrategias para la construcción de genotecas o librerías de DNA

-   Alineamiento local vs global: Needleman-Wunsch, Smith-Waterman. Alineamiento múltiple

-   Ensamblaje de genomas, evaluación, predicción de genes, anotación

-   Genómica comparativa, pangenomas, búsqueda de genes de interés, polimorfismos de sustitución simple, recombinación

-   Reconstrucción filogenética: modelos de sustitución, selección de modelos (AIC, BIC, LRT) criterios de optimalidad, modelos comparativos

-   Genómica de poblaciones, aplicaciones en eucariontes y procariontes. Filogeografía

-   Análisis de expresión génica (RNASeq; Microarrays)

-   Metagenómica y metatranscriptómica

 ![t1](https://raw.githubusercontent.com/bioinf-geno/materials/master/t1.png)
 ![t2](https://raw.githubusercontent.com/bioinf-geno/materials/master/t2.png)

\*Cualquier eventual modificación de la información entregada en este documento será informada oportunamente a los alumnos.

**PRUEBA RECUPERATIVA**

No existen pruebas recuperativas. Si el alumno no rindió alguna solemne de cátedra o laboratorio, deberá dar examen y la nota obtenida reemplazará la nota de la solemne faltante. El el caso excepcional en que un estudiante falte a dos pruebas solemnes, la segunda nota será reemplazada por una prueba oral. Todas las ausencias a pruebas y controles tienen que ser justificadas. La justificación deberá ser presentada al coordinador del curso (**plazo máximo 72 horas**. como se describe en el reglamento estudiantil) para su aprobación. En el caso de una justificación médica, el estudiante deberá al menos presentar un certificado médico y el comprobante del bono.

**NOTA DE PRESENTACION Y EXAMEN**

NOTA DE PRESENTACION A EXAMEN (NP) = ver sección evaluaciones

NOTA FINAL = NP(70%) + EXAMEN (30%)

Todo alumno cuya nota de presentación (NP) sea igual o superior a **5,0** puede eximirse de rendir examen, siempre y cuando **no** tenga notas inferiores a 4,0 en las pruebas y las otras evaluaciones.

**METODOLOGÍA DE ACTIVIDADES ACADÉMICAS**

Clases teórico prácticas, enseñanza basada en proyectos.

**NORMAS DE DISCIPLINA Y PROCEDIMIENTOS EN LABORATORIOS**

Durante todas las actividades, los alumnos deben cumplir las siguientes condiciones:

*1. Puntualidad:* La puntualidad es de máxima importancia en esta clase. Si el estudiante está atrasado por más de 10 minutos, se le recomienda no entrar a la sala de clases. Recuerde que todas las ausencias a evaluaciones tienen que ser justificadas.

*2. Disciplina*: Las normas de orden y disciplina deben ser mantenidas durante todas las actividades. Esto significa que no pueden hacer uso de telefonía celular u otra forma de comunicación digital mientras se encuentren dentro de la sala de clases. En cuanto a las normas de respeto y sana convivencia, se exigirá un lenguaje adecuado y un comportamiento acorde a un estudiante universitario.

*3. Participación*: Se espera participación activa en las clases (Ej.: hacer preguntas, discutir los temas, etc.)

*4. Evaluación*: Cada estudiante es responsable de traer consigo, lápiz pasta, goma, lápiz grafito, corrector, regla, calculadora (no se aceptará el uso de celulares con este fin), de manera que no se aceptarán préstamos entre los alumnos mientras se realice la evaluación.

**RECURSOS**

-   [Software Carpentry](http://software-carpentry.org)
-   [Little Book of R for Bioinformatics!](https://a-little-book-of-r-for-bioinformatics.readthedocs.org/en/latest/)
-   [An Introduction to Applied Bioinformatics](http://readiab.org/book/latest/)
-   [Bioconductor Workflows](https://www.bioconductor.org/help/workflows/)
-   [Bioconductor course materials](https://www.bioconductor.org/help/course-materials/)  
-   [Applied Statistics for Bioinformatics using R](https://cran.r-project.org/doc/contrib/Krijnen-IntroBioInfStatistics.pdf)  
- [Bernd Klaus - Teaching Materials](http://www-huber.embl.de/users/klaus/teaching.html%23machine-learning-predoc-course-2014)  
-  [Hadley Wickham's ggplot2 / Data Visualization Course Materials](http://had.co.nz/vanderbilt-vis/)
