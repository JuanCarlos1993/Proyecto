Proyecto Intoxicación por picadura de alacrán     03/11/14
==========================================================================================

Información acerca de git.

Repositorio      https://github.com/JuanCarlos1993/Proyecto
Commits          3

==========================================================================================

Información importante.

1. En la carpeta DATOS/PROCESADOS se incluye un archivo RData, con las 3 tablas 
principales que corresponden a Mes, Grupo y Fuente, de igual forma contiene esas mismas 
tablas pero en formato largo, que se pueden obtener mediante los siguientes objetos.

           x        Tabla por Mes
           y        Tabla por Fuente
           z        Tabla por Grupo
           x1       Tabla por Mes (formato largo)
           y1       Tabla por Fuente (formato largo)
           z1       Tabla por Grupo (formato largo)
           
           
2. De igual forma se incluye en la carpeta DATOS/PROCESADOS un diccionario de datos con 
información acerca de las instituciones.


3. La carpeta DATOS/BRUTOS contiene los archivos correspondientes a su sección antes de 
limpieza y organización.


4. En la carpeta CODIGO se incluyen 3 R-Markdown que corresponden al análisis de casos 
de intoxicación por picadura de alacrán por mes, grupo de edad y fuente.

 
5. La carpeta TEXTO contiene un reporte técnico donde se buscó resolver las principales 
preguntas con respecto al tema, y un resumen ejecutivo que corresponde a los hallazgos 
después del análisis de los datos.


6. La carpeta FIGURAS incluye todas las gráficas obtenidas en la realización del 
proyecto, si se quiere mayor información para entender mejor las gráficas abrir el 
reporte técnico.

7. En el R-Markdown nombrado como ProyectoAlacranesFD, al querer leer los archivos CSV 
con un for se tuvo que agregar un argumento en la función read.csv que fue el 
fileEncoding="latin1", ya que dicho Markdown fue elaborado en un sistema Windows y los 
otros 2 restantes se trabajaron en Mac, gracias a esto se pudieron leer los archivos 
por fuente sin ningún problema.

==========================================================================================



          
