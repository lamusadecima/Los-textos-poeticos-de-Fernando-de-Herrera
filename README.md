# Los-textos-poeticos-de-Fernando-de-Herrera

Este repositorio contiene los anexos de mi obra <i>Los textos poéticos de Fernando de Herrera: aproximaciones desde la Estilística de corpus y la Estilometría</i>, fruto de mi tesis doctoral. Estos son los siguientes:

- Anexo I. Poemas en B, H y P

- Anexo II. Corpus de la poesía herreriana con su ortografía original en texto plano Unicode UTF-8

- Anexo III. Corpus de la poesía de Herrera y de Pacheco modernizado en Unicode UTF-8

- Anexo IV. Corpus de la poesía de Herrera y de Pacheco etiquetado morfosintácticamente

- Anexo V. Scripts en R

- Anexo VI. Palabras de H que no aparecen en P desglosadas

- Anexo VII. 20 bigramas morfosintácticos más frecuentes en el corpus completo

- Anexo VIII. Distancias de bigramas morfosintácticos en P2, Herrera y Pacheco

- Anexo IX. 20 trigramas morfosintácticos más frecuentes en el corpus completo

- Anexo X. Distancias de trigramas morfosintácticos en P2, Herrera y Pacheco

- Anexo XI. Descripción del corpus de Siglo de Oro utilizado

- Anexo XII. Imágenes en color de los análisis de Rolling Classify (capítulo 4.5)

## Anexo I. Poemas en B, H y P

Listado con los títulos de los poemas herrerianos que aparecen en los testimonios B, H y P.

## Anexos II y III. Digitalización del corpus poético de Herrera y Pacheco

Los Anexos II y III contienen el corpus digitalizado de la poesía de Herrera y Pacheco. Se encuentran en la carpeta "corpus". Dentro de esta, el corpus con la ortografía original (Anexo II) se encuentra en la carpeta "original", y el corpus con ortografía modernizada (Anexo III), en la carpeta "modernizado".

## Anexo IV. Corpus etiquetado morfosintácticamente

El Anexo IV contiene el corpus poético de Herrera y Pacheco anotado automáticamente con información de Part-of-Speech (categorías morfológicas). Se encuentra también dentro de la carpeta "corpus", dentro de "POS".

## Anexo V. Scripts en R

En el Anexo V se incluyen los scripts propios en R utilizados en la carpeta "scripts".

## Anexo VI. Lista de palabras de H que no aparecen en P

El Anexo VI contiene dos lista desglosada de las palabras de H que no aparecen en P, clasificadas en las siguientes categorías: 

a) Palabras que corresponden a la égloga venatoria

b) Palabras que corresponden a los dos sonetos que no pasan a P

c) Palabras eliminadas al pasar a P

La primera lista incluye las palabras como tokens, mientras que la segunda incluye la lista de lemas de H que no pasan a P.

## Anexos VII y IX. Ngramas morfosintácticos más frecuentes en el corpus

Los Anexos VII y IX incluyen los 20 bigramas y trigramas morfosintácticos más frecuentes del corpus completo obtenidos en los apartados 3.3.3.2.1 y 3.3.3.2.2 del libro. Se encuentran en la carpeta "POS-ngrams".

### Anexo VII. Bigramas morfosintácticos

Relación de los 20 bigramas morfosintácticos más frecuentes en el corpus completo de la Tesis doctoral. La tabla "bigramas_frecuencias-absolutas" contiene las frecuencias absolutas, ordenados por sus valores en el total del corpus. La tabla "bigramas_frecuencias-relativas" contiene las frecuencias relativas en tantos por mil.

### Anexo IX. Trigramas morfosintácticos

Relación de los 20 trigramas morfosintácticos más frecuentes en el corpus completo de la Tesis doctoral. La tabla "trigramas_frecuencias-absolutas" contiene las frecuencias absolutas, ordenados por sus valores en el total del corpus. La tabla "trigramas_frecuencias-relativas" contiene las frecuencias relativas en tantos por mil.

## Anexos VIII y X. Distancias de los ngramas morfosintácticos

Los Anexos VIII y X incluyen los resultados completos del cálculo de los z-scores para bigramas y trigramas morfosintácticos, analizados en los apartados 3.3.3.2.1 y 3.3.3.2.2 del libro. Se encuentran en la carpeta "Distancias_POS-ngrams".

### Anexo VIII. Bigramas morfosintácticos

Tabla completa de las distancias de patrones morfosintácticos obtenidas para P2, Herrera (H y poemas sueltos) y Pacheco (poesía escrita por él), mediante el cálculo de z-scores. La primera columna recoge cada relación de dos etiquetas o bigramas, las tres siguientes columnas contienen la frecuencia relativa de cada uno de los trigramas para Herrera, P2 y Pacheco respectivamente, mientras que la quinta columna incluye la media de cada bigrama en los tres corpus, y la sexta representa el valor de desviación típica obtenido para cada uno de los bigramas (SD). A continuación, las tres siguientes columnas recogen los valores de z-scores obtenidos para cada uno de los corpus. Para finalizar, las dos últimas columnas contienen los valores de distancia basados en los z-scores de P2 frente a Herrera (“P2 vs Herrera”) y P2 frente a Pacheco (“P2 vs Pacheco”).

### Anexo X. Trigramas morfosintácticos

Tabla completa de las distancias de patrones morfosintácticos obtenidas para P2, Herrera (H y poemas sueltos) y Pacheco (poesía escrita por él), mediante el cálculo de z-scores. La primera columna recoge cada relación de tres etiquetas o trigramas, las tres siguientes columnas contienen la frecuencia relativa de cada uno de los trigramas para Herrera, P2 y Pacheco respectivamente, mientras que la quinta columna incluye la media de cada trigrama en los tres corpus, y la sexta representa el valor de desviación típica obtenido para cada uno de los trigramas (SD). A continuación, las tres siguientes columnas recogen los valores de z-scores obtenidos para cada uno de los corpus. Para finalizar, las dos últimas columnas contienen los valores de distancia basados en los z-scores de P2 frente a Herrera (“P2 vs Herrera”) y P2 frente a Pacheco (“P2 vs Pacheco”).

## Anexo XI. Descripción del corpus de Siglo de Oro utilizado

En la carpeta "descripción-corpus-ampliado", se presenta el corpus de poetas del Siglo de Oro utilizado en los análisis estilométricos de esta Tesis, ofreciendo información sobre los autores que lo componen, fecha de nacimiento y muerte, número de poemas que constituyen el corpus de cada autor, y número total de palabras.

Una de las tablas muestra el corpus de sonetos de Siglo de Oro, preparado a partir de los textos del proyecto ADSO (Navarro-Colorado et al., 2016), además de los sonetos escritos por Herrera y Pacheco digitalizados para la Tesis (en su versión modernizada). Como se indicó en el apartado 2.1.3.4, la ortografía del corpus digitalizado para la Tesis se contrastó con la de los textos extraídos de ADSO para comprobar que no existieran diferencias que pudieran producir distorsiones en el análisis. Asimismo, conforme a las reglas de ortografía actuales se ha eliminado la tilde en sólo en todos los textos. El corpus de sonetos de Siglo de Oro ha sido utilizado para los análisis estilométricos de los apartados 4.2, 4.3, 4.4 (solo Arguijo, Herrera, Góngora y Pacheco) y 4.7.

Por otra parte, se han recopilado poemas de diferentes subgéneros poéticos de Garcilaso y Góngora con el objetivo de utilizarlos como autores de control en los análisis estilométricos de los apartados 4.4 (solo Góngora) y 4.5 (ambos). Como ya se ha indicado en estos apartados, los textos poéticos de Garcilaso fueron extraídos de la Biblioteca Virtual Miguel de Cervantes (http://www.cervantesvirtual.com/portales/garcilaso_de_la_vega/), mientras que los de Góngora han sido copiados de la edición digital de su poesía completa que ofrece el proyecto Góngora del OBVIL (Góngora, 2016): http://obvil.sorbonne-universite.site/corpus/gongora/gongora_obra-poetica. El texto ha sido copiado de esta edición, y a continuación se han eliminado la numeración y fechas de los poemas, las diéresis métricas y los titulillos de los poemas, con el objetivo de utilizar en el análisis únicamente el texto de las composiciones gongorinas. Más información sobre estos corpus se recoge en la tabla "garcilasoygongora".

## Anexo XII. Imágenes en color de Rolling Classify

En la medida de lo posible, los gráficos resultantes de los análisis estilométricos se han generado en blanco y negro para facilitar su impresión y visualización por parte del lector. En el caso de Rolling Classify, esto no ha sido posible, pues no lo permite la herramienta. Por esta razón, se incluyen en el Anexo XII las imágenes originales en color por si el lector necesita consultarlas. Se encuentran en "rolling_classify-color.zip". Descárguela en su ordenador y descomprima para extraer todo el contenido.

## Cómo citar

Hernández Lorenzo, Laura, <i>Los textos poéticos de Fernando de Herrera: aproximaciones desde la Estilística de corpus y la Estilometría</i>
