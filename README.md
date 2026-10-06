Hito 1: Análisis Estructural de Viga Simplemente Apoyada
Este repositorio contiene el análisis estructural del comportamiento mecánico de una viga simplemente apoyada sometida a una carga puntual en el centro de su luz. El proyecto compara datos sintéticos de deflexión medidos experimentalmente con el modelo teórico de flexión de Euler-Bernoulli.
Estructura del Repositorio
La organización de los directorios permite distinguir claramente entre las entradas originales, los archivos de procesamiento, las salidas gráficas y el reporte final:
data/ (Entradas): Contiene los datos crudos originales e inalterados.datos_viga.csv: Carga aplicada y deflexión medida empíricamente en el centro de la viga.   parametros_viga.xlsx: Parámetros geométricos (L, b, h) y mecánicos (E) de la viga.   
analysis/ (Procesamiento):analisis_viga.xlsx: 
Planilla que rastrea el cálculo del momento de inercia (I), la deflexión teórica y los esfuerzos máximos.figures/ 
(Salidas visuales):carga_deflexion.png: Gráfico generado que compara la deflexión medida experimentalmente con la deflexión teórica calculada.report/ 
(Documento final):main.tex: Código fuente en LaTeX de la nota técnica.referencias.bib
Archivo de bibliografía para el reporte en LaTeX.nota_tecnica.pdf 
Informe final compilado con los resultados y conclusiones.Archivos base
README.md: Este archivo, con las instrucciones para reproducir el análisis.  
USO_IA.md: Declaración formal del uso (o no uso) de herramientas de Inteligencia Artificial durante el desarrollo del encargo. 
