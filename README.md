#  Laboratorio 03 - Ensamblaje de genomas y predicción de genes.

# Constanza Ortega Fuentes

## Parte 1: El artículo genoma

#### ¿Cuántos genomas han sido depositados en GOLD? ¿Son los mismos de GENBANK?

- Han sido depositados 85.202 genomas  en GOLD, en cambio en GENBANK  existen depositados 163.657, una gran diferencia. 

#### ¿Cuál es la distribución de procariontes y eucariontes secuenciados?

- En procariontes hay 249.709 genomas de procariontes y hay 18.241 genomas de eucariontes

 #### ¿Qué es el N50, L50, NG50?

- N50: Este valor es una estimación de la calidad del secuenciamiento, en relación al largo de los fragmentos (contings). Se calcula sumando todos los fragmentos de mayor a menor, hasta la suma de la mitad de todo el genoma, el ultimo valor dentro del rango es el N50.

- L50: Número de contigs que se necesitaron para cubrir la mitad del genoma.

- NG50: se comporta de la misma forma que el N50 pero es 50% del tamaño del genoma conocido o estimado que debe ser de longitud NG50 o más larga.

#### ¿Cuál es el propósito de calcular estas estadísticas?

- midiendo  reads, contigs y scaffolds se puede terminar la calidad de la secuenciación en relación al largo de la secuencia original.

 #### ¿Cuál es el genoma que escogiste? Adjunta la referencia.

-  secuenciación de la heterocromatina de la Drosophila melanogaster

- http://science.sciencemag.org/content/316/5831/1625.full


 #### ¿Cuál es el N50 del genoma que escogiste? ¿Y el NG50?

- 35 kb 

#### ¿Qué tipo de tecnología se uso para secuenciar el genoma que escogiste?

- se uso la tecnología de: The whole-genome shotgun sequence (WGS3) 

#### ¿Qué organismo escogiste, cuántos cromosomas tiene tu organismo y cuál es su tamaño?

- posee 7 cromosomas y un largo total de 6.16 Mb

## Parte 2: Predicción de genes

#### ¿Cuántos ORF o genes encontró ORFfinder?

![orf](https://raw.githubusercontent.com/constanzaortega/laboratorio-3-bioinformatica./master/Sin%20t%C3%ADtulo.jpg)


- La secuencia entregó 7 orf.

#### ¿Cuántos ORF o genes encontró Glimmer?

- Glimmer encontró 10 orf

#### ¿Alguno de los genes predichos por estas herramientas coinciden?

- ninguno cohincide

#### ¿En qué hebra están codificados?

- En Glimmer los ORF 1, 3, 5, 7 estan en la hebra adelantada y los demas en la retrasada, en ORFinder los ORF 1, 2 y 3 estan en la hebra adelantada y  los demas en la retrasada.

#### ¿Qué tipo de programa es GLIMMER? ¿Ab initio o por homología?

- Glimmer es un sistema para encontrar genes en el ADN microbiano, especialmente los genomas de bacterias, arqueas y virus, funciona  por homologia de secuencias.

#### Describe los resultados encontrados con respecto a los genes que encontraste con GLIMMER y ORFfinder

- Según la secuencias de nucleotidos entregadas, por ambos programas GLIMMER y ORFinder dan como resultado proteinas de tipo deshidrogenasa de una bacteria (Haemophilus influenzae).


## Bibliografía

https://www.ncbi.nlm.nih.gov/genome/?term=drosophila+melanogaster


https://gold.jgi.doe.gov/


https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics


https://blast.ncbi.nlm.nih.gov/Blast.cgi

