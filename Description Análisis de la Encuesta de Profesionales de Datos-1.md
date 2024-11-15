# Data Professional Survey Breakdown

Este proyecto en Power BI presenta un análisis visual basado en una encuesta realizada a profesionales de datos. El objetivo principal del proyecto es poner en práctica habilidades de análisis y visualización de datos utilizando Power BI, con el propósito de explorar las tendencias laborales en el sector.

1) Objetivos del Proyecto:

-Analizar las diferencias salariales y de satisfacción laboral entre distintos roles en el sector de los datos.
-Visualizar las preferencias de lenguajes de programación y el nivel de satisfacción con el balance entre vida laboral y personal.

2) Proceso de Preparación de Datos:

La base de datos utilizada proviene de un archivo Excel, y todo el proceso de limpieza y transformación se realizó en Power BI. A continuación, se detallan los pasos llevados a cabo:

### Eliminación de columnas innecesarias: 
    Se eliminaron las columnas Browser, OS, City, Country y Referrer.
### Limpieza de roles múltiples: 
    Se dividió la columna "Q1 - Which Title Best Fits your Current Role?.1" por delimitador para limpiar los múltiples roles dentro de la categoría "Other", eliminando la segunda columna resultante. Se aplicó el mismo procedimiento a la columna "Q5 - Favorite Programming Language".

### Modificación de la columna de salario: La columna "Q3 - Current Yearly Salary (in USD)" fue dividida utilizando la opción "De dígito a no dígito".
    Se eliminaron las columnas no útiles, se limpiaron los valores para obtener solo los números de los rangos salariales y se cambió el tipo de dato para realizar operaciones matemáticas.
    Se creó una columna personalizada para calcular el promedio de los rangos salariales y se eliminaron columnas en desuso.
### Limpieza de roles múltiples en otras columnas: 
    Se dividió la columna "Q11 - Which Country do you live in?.1" por delimitador y se eliminó la segunda columna.
    Se realizó el mismo procedimiento para la columna "Q4 - What Industry do you work in?.1".

3) Descripción del Panel:

### Filtros por País: 
    Permite segmentar los datos según la ubicación geográfica de los encuestados (Canadá, India, Reino Unido, Estados Unidos).

### Promedio de Salario por Cargo: 
    Muestra el salario promedio para roles como Data Scientist, Data Engineer, Data Analyst, entre otros.

### Lenguajes de Programación Favoritos: 
    Visualiza las preferencias de los encuestados en cuanto a lenguajes de programación (Python, R, JavaScript, etc.).

### Promedio de Salario por Sexo: 
    Compara los salarios entre hombres y mujeres dentro del sector.

### Satisfacción con el Salario y Balance Vida-Trabajo: 
    Indicadores visuales que reflejan el nivel de satisfacción de los profesionales en relación con el salario y el equilibrio entre vida laboral y personal.

4) Fuente de Datos:
La base de datos utilizada proviene de un archivo Excel generado a partir de una encuesta realizada en Linkedin y compartida por el analista de datos Alex Freberg.

5) Conclusiones:
Este panel interactivo ofrece una visión detallada de las dinámicas laborales en el sector de los datos, proporcionando una comparación clara de salarios, preferencias tecnológicas y niveles de satisfacción en relación con la vida laboral. El análisis es útil tanto para profesionales como para empleadores interesados en las tendencias del sector.
















### PASOS

1) Eliminación de columnas innecesarias:(Browser, OS, City, Country y Referrer)
2) División de columnas por delimitador para poder limpiar los multiples roles dentro de la categoría "Other" de la columna "Q1 - Which Title Best Fits your Current Role?.1". Se dividen las columnas y se elimina la segunda.
3) División de columnas por delimitador para poder limpiar los multiples roles dentro de la categoría "Other" de la columna "Q5 - Favorite Programming Language". Se dividen las columnas y se elimina la segunda.
4) Modificación de la columna "Q3 - Current Yearly Salary (in USD)  Dividimos la columna, con la opción "De dígito a no dígito" y luego eliminamos las columnas que no nos sean útiles. La columna que contiene el límite superior del rango de salario la limpiamos con la opción "reemplazar valores". Una vez que logramos tener solo los números de los rangos salariales, les cambiamos el tipo de dato para poder realizar operaciones matemáticas con esos números. Finalmente, creamos una columna personalizada que sea el promedio de los rangos salariales obtenidos y eliminando las columnas en desuso.
5) División de columnas por delimitador para poder limpiar los múltiples roles dentro de la categoría "Other" de la columna "Q11 - Which Country do you live in?.1". Se dividen las columnas y se elimina la segunda.
6) División de columnas por delimitador para poder limpiar los múltiples roles dentro de la categoría "Other" de la columna "Q4 - What Industry do you work in?.1". Se dividen las columnas y se elimina la segunda.
7) Creación de tarjetas "Count of Survery Takers" y "Average of Survey Takers".