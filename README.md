# Detección de la depresión en jóvenes mexicanos mediante Procesamiento del Lenguaje Natural

## Autores

- Alfonso Valenciana Díaz
- Mauricio Ivan Martínez Carmona
- Ricardo Ariel Estrada Pérez

## Introducción

Los trastornos mentales constituyen un importante problema de salud publica, en particular, la depresión es la principal causa de ausentismo laboral en todo el mundo; los síntomas que presentan las personas que la padecen están relacionados con su comportamiento diario incluyendo la forma en la que se expresan.

Distintos estudios han demostrado que es posible diagnosticar a una persona con depresión de acuerdo a su vocabulario, ya que este revela indicadores acerca de su estado emocional.

Las redes sociales son una parte integral en nuestras vidas diarias, a través de estas compartimos información sobre nuestros intereses, opiniones, planes futuros e incluso acerca de nuestro estado emocional. Twitter es un medio dinámico en el cual usuarios comparten mensajes frecuentemente durante el transcurso de sus actividades diarias.

**El uso del machine learning...**

Si bien el diagnóstico de las enfermedades mentales es complejo, las técnicas modernas de machine learning se muestran como herramientas de gran utilidad a la ciencia psiquiátrica para facilitar esta tarea. En años recientes han proliferado artículos y publicaciones relativas a investigaciones en las que se han utilizado técnicas de machine learning en busca de una metodología diagnóstica efectiva.

Uno de los más destacados se publicó en 2020[[11]](#referencias). En dicho estudio, un equipo de investigadores japoneses, de la Universidad de Tokio, sorprendieron con un interesante trabajo publicado en Translational Psychiatry, hecho en adultos japoneses con un diagnóstico del espectro autista y esquizofrenia, personas con alto riesgo de acabar desarrollando esquizofrenia, sujetos que habían tenido algún tipo de episodio psicótico, pero que aún no habían desarrollado esquizofrenia, y personas sin enfermedades mentales que formaban parte del grupo control. En total, se incluyó a 206 participantes. El sistema de machine learning utilizado en este trabaj pudo diferenciar entre seis tipos de diagnósticos: no pacientes, pacientes con un trastorno del espectro autista, pacientes con esquizofrenia o factores de riesgo de esquizofrenia.

Otro estudio publicado en Psychiatry Research[[12]](#referencias) ha demostrado que es posible identificar qué pacientes serían depresivos a través de imágenes obtenidas por resonancia magnética, y su posterior análisis mediante máquinas sujetas al aprendizaje automático.

Gracias a líneas de investigación en machine learning como estas, el futuro parece indicar que estas técnicas estáran cada vez más presentes en la psiquiatría y la neurología. 

## Planteamiento del problema

De acuerdo con [[1]](#referencias) y [[2]](#referencias), la depresión (trastorno depresivo mayor o depresión clínica) es un trastorno del estado de ánimo común, provoca síntomas graves que afectan la forma de sentir, pensar y realizar las actividades cotidianas de personas de todas edades y puede ser causado por una combinación de factores genéticos, biológicos, ambientales y psicológicos.

Un problema en las ciencias de la salud es el desarrollar instrumentos que permitan diagnosticar con mayor precisión la depresión y de esta forma, proveer tratamiento médico y/o terapia psicológica oportuna a los afectados por este trastorno.

## Objetivo General

Crear un instrumento de alta precisión que permita diagnosticar la depresión en jovenes mexicanos mediante Procesamiento de Lenguaje Natural.

## Objetivos Específicos

- Utilizar Python como lenguaje de programación.
- Hacer uso de librerias de Python para la ciencia de datos.
- Recolectar 16,000 publicaciones de Twitter por cada estado de la Republica Mexicana.
- Emplear K-Means como metodo de agrupamiento.
- Aplicar tecnicas de Procesamiento de Lenguaje Natural.

## Justificación

Según la Organización Mundial de la Salud, la depresión es la principal causa mundial de discapacidad y contribuye de forma muy importante a la carga mundial general de morbilidad. Se estima que afecta a más de 300 millones de personas en el mundo, de las cuales cada año se suicidan cerca de 800 mil personas; siendo las mujeres más propensas a padecer de este trastorno [[3]](#referencias).

En particular, la depresión es difícil de diagnosticar debido a múltiples factores, de los cuales Jiang considera que “el factor más fundamental y desafiante puede ser que la depresión es una enfermedad altamente heterogénea y su patogénesis real no se ha dilucidado claramente” [[4]](#referencias), es decir, su origen, evolución y síntomas son diferentes en cada individuo, lo que resulta en el uso de instrumentos psicométricos que solamente ayudan a diagnosticar de forma parcial y subjetiva a los pacientes como se menciona en [[5]](#referencias).

Entre los instrumentos más utilizados por los especialistas de la salud se encuentra el Inventario para la Depresión de Beck (BDI-II), el cual es un instrumento conformado por 21 objetos que permite detectar la presencia de síntomas depresivos y cuantificar su gravedad con base en la puntuación total obtenida, además de que puede ser aplicado sin la supervisión de un especialista [[6]](#referencias).

La mayoría de los métodos orientados a la detección automática de la depresión en redes sociales han seguido un enfoque supervisado que depende de información etiquetada previamente para su construcción y emplean procedimientos compuestos por multiples pasos que pueden dificultar el proceso de clasificación, lo que resulta en un proceso sumamente complejo y costoso,, como se muestra en [[10]](#referencias).

## Estado del Arte

En [[7]](#referencias) se emplean representaciones BoW con pesos boleeanos, tf, tf-idf y n-gramas de 3 caracteres para la construcción de una matriz termino-documento, lo que resulta en un 0.24 de F1 Score.

En [[8]](#referencias) se construyen distintos diccionarios compuestos por palabras relacionadas con depresión, además de una mezcla de atributos sintacticos, semanticos y de comportamiento.

En [[9]](#referencias), por un lado se establecen caracteristicas de tipo semantico y estadisticas, lo que resulta en un 0.47 de F1 Score.

## Referencias

1. National Institute of Mental Health, “Depression”, February 2018. [Online]. 
Available: https://www.nimh.nih.gov/health/topics/depression/index.shtml (accessed Apr. 21, 2021).
2. Centers for Disease Control and Prevention, “Mental Health Conditions: Depression and Anxiety”, January 2020. [Online]. 
Available: https://www.cdc.gov/tobacco/campaign/tips/diseases/depression-anxiety.html (accessed Apr. 21, 2021).
3. World Health Organization, “Depression”, January 2020. [Online]. 
Available: https://www.who.int/es/news-room/fact-sheets/detail/depression (accessed Apr. 21, 2021).
4. K. Jiang, “Why is Diagnosing MDD Challenging?.” in Shanghai Archives of Psychiatry, Dec. 2016. [Online]. 
Available: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5434292/ (accessed May. 6, 2021).
5. Harvard Health Publishing, “Major Depression: What Is It?”, December 2018. [Online]. 
Available: https://www.health.harvard.edu/a_to_z/major-depression-a-to-z (accessed May. 6, 2021).
6. Grupo de trabajo de la Guía de Práctica Clínica sobre el Manejo de la Depresión en el Adulto, Guía de Práctica Clínica sobre el Manejo de la Depresión en el Adulto. (2014). [Online]. 
Available: https://portal.guiasalud.es/wp-content/uploads/2020/10/gpc_534_depresion_adulto_avaliat_compl_caduc.pdf (accessed May. 6, 2021).
7. M. P. Villegas, D. G. Funez, M. J. Garciarena-Ucelay, L. C. Cagnina and M. L. Errecalde, "Pilot task on Early Detection of Depression," presented at the CLEF, Dublin, Ireland, 2017.
8. H. Almeida, A. Briand and M. J. Meurs, "Detecting Early Risk of Depression from Social Media User-generated Content," presented at the CLEF, Dublin, Ireland, 2017.
9. F. Ramiandrisoa, J. Mothe, F. Benamara and V. Moriceau, "IRIT at e-Risk 2018," presented at the CLEF, Dublin, Ireland, 2018.
10. Coello, 2019. "Clasificación translingüe para la detección de depresi ́on en usuarios de Twitter". Available: https://inaoe.repositorioinstitucional.mx/jspui/bitstream/1009/1952/1/CoelloGDL.pdf
11. Yassin, 2020, "Machine-learning classification using neuroimaging data in schizophrenia, autism, ultra-high risk and first-episode psychosis". Available: https://www.nature.com/articles/s41398-020-00965-5 
12. Psyquiatric Research, August 2021, Available: https://www.sciencedirect.com/journal/psychiatry-research-neuroimaging
