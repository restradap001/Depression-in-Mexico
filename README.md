# Depression-in-Mexico

## Introducción

Más de 300 millones de personas sufren depresión a nivel mundial siendo ésta la principal causa de ausentismo laboral en todo el mundo. Según la Organización Mundial de la Salud (OMS), en el mundo una de cada trece personas sufre depresión o algún trastorno mental relacionado. Los trastornos mentales en México constituyen un importante problema de salud pública. En relación con los años de vida perdidos por incapacidad, el trastorno depresivo ocupa el primer lugar en mujeres y el quinto en hombres.

Los síntomas que presentan las personas que la padecen están relacionados con su comportamiento diario incluyendo la forma en la que se expresan. Estudios en psicología sugieren que el uso de palabras específicas en nuestro vocabulario revelan indicadores sobre nuestro estado emocional. Diferentes trabajos relacionados con la detección y análisis de depresión revelan que las palabras que usan las personas deprimidas permiten distinguirlas de entre el resto de las personas.

Actualmente, las redes sociales son una parte integral en nuestras vidas diarias, a través de ellas los usuarios comparten información sobre sus intereses, opiniones, planes futuros e incluso sobre su estado emocional, por ejemplo, sus alegrías y tristezas. Es por ello que estas plataformas brindan una oportunidad para transformar los servicios de detección temprana de diferentes trastornos mentales, entre ellas la depresión.

De esta forma el material extraído de redes sociales, que contiene los síntomas de estados depresivos presentes en la enorme cantidad de publicaciones realizadas en redes sociales, sirve de insumo a tareas de análisis de textos; que corresponde a la determinación de atributos y representaciones que permitan la detección de depresión en textos.

## Estado del Arte

Twitter es un medio dinámico en el cual sus usuarios comparten mensajes frecuentemente durante el transcurso de sus actividades diarias. Esta característica ha convertido a este medio en uno de los más usados para la detección de personas que sufren depresión.

No obstane, esta no es una tarea sencilla. En primer lugar, los tuits son mensajes muy cortos que normalmente no proveen información de contexto y en segundo lugar, los indicadores de depresión suelen manifestarse de manera muy sutil, por lo tanto, su detección no es obvia para el lector. A pesar de estas características, trabajos recientes han reportando resultados muy alentadores en la detección de usuarios que sufren depresión y de otros trastornos mentales.

La mayoría de los métodos previos, orientados a la detección automática de depresión en redes sociales, han seguido un enfoque supervisado que los hace depender de datos etiquetados para su construcción. Estos métodos han explorado distintas representaciones y técnicas de clasificación, desde técnicas tradicionales hasta basadas en aprendizaje profundo. Desafortunadamente, el proceso de recolectar y etiquetar datos para el entrenamiento es muy complejo y costoso.

En general, las aproximaciones de los trabajos que han abordado esta problemática están compuestas por demasiados pasos, y tienden a complicar el proceso de clasificación y en consecuencia es difícil determinar qué tan bien funciona cada atributo seleccionado dentro de las representaciones propuestas.

Prácticamente la totalidad de esos estudios emplean recursos basados en listados de palabras, la mitad emplea algún tipo de rastreo del comportamiento y sólo uno hacer clasificaciones por publicación (considerando el tamaño de la instancia como cada publicación del sujeto). Los trabajos referidos en esta sección, no toman en cuenta aspectos como las faltas de ortografía o slang/calo que emplean los individuos al escribir sus textos

Tampoco se contempla en estos trabajos la búsqueda de respuestas (parciales o totales) a cuestionarios de diagnóstico clásico de depresión,los cuales incluyen preguntas como: ¿Tiene problemas para dormir? ¿Duerme demasiado? ¿Poco apetito? ¿Tiene problemas de concentración?

Existen trabajos como el de Villegas, Funez, Ucelay, Cagnina y Errecalde (2017), en el que se emplean representaciones con BoW con pesos booleano, tf y tf-idf y también se contemplan n-gramas de 3 caracteres para la construcción de su matriz término-documento (document-term matrix -dtm-). Su baseline en F1 measure con representación de BOW es de 0.24.

Por su parte, Almeida et al. (2017), toma en cuenta varios diccionarios conformados por listados de palabras relacionadas con depresión: sentimientos, nombres de medicamentos o enfermedades mentales para su trabajo. Se mezclaron el uso de atributos sintácticos, semánticos y de comportamiento.

En la investigación de Malam et al. (2017) se establecen características de tipo semántico y estadísticas. Las características de tipo semántico contemplan entre otros aspectos: Uso de referencias a sí mismo, términos de generalización, análisis de sentimiento, análisis de emociones, síntomas de depresión o palabras en pasado. Dentro de los atributos calculados de tipo estadístico se encuentran: las variaciones en el número de publicaciones, medias de publicaciones, palabras, comentarios o palabras por comentario. Se obtiene un resultado de F1 measure de: 0.47.

## Referencias

Villegas, M. P., Funez, D. G., Ucelay, M. J. G., Cagnina, L. C. y Errecalde, M. L. (2017). LIDIC - UNSL’s Participation at eRisk 2017: Pilot Task on Early Detec- tion of Depression. En CLEF.

Almeida, H., Briand, A. y Meurs, M.-J. (2017). Detecting early risk of depression from social media user-generated content. Working Notes of CLEF.

Malam, I. A., Arziki, M., Bellazrak, M. N., Benamara, F., Kaidi, A. E., Es-Saghir, B., . . . y Ramiandrisoa, F. (2017). IRIT at e-Risk. En CLEF.
