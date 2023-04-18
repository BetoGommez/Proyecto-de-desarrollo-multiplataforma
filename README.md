# Proyecto-de-desarrollo-multiplataforma

## -Data Science en Python:
### Preparación del entorno:
+ Instalar Anaconda
+ Con el Anaconda Prompt nos posicionamos en el directoria deseado y lanzaremos: \
```conda create --name datascience_openwebinars python=3.7```
+ Para la activación del proyecto: \
```conda activate datascience_openwebinars```
+ Pasaremos a instalar las librerias
``` conda install -c conda-forge jupyterlab
conda install -c conda-forge numpy
conda install -c conda-forge pandas
conda install -c conda-forge matplotlib
conda install -c anaconda seaborn 
```
+ Creamos una carpeta en el proyecto para lanzar las notebook (en mi caso *Visualizaciones*)
+ Ahora para iniciar el entorno: \
```jupyter lab```
+ Aparecerá la pestaña de jupyterlab y en eslector de archivos crearemos una carpeta para nuestro primer gráfico
+ En mi caso se llamará **Cursos/Curso_Visualizacion_Datos/MiPrimerGráfico** y aquí haremos click derecho y crearemos un notebook
+ Esta será el entorno que usaremos
### Cursos
#### Visualización de datos:
+ Todos los gráficos creados pueden ser vistos desde github, simplemente navegando entre carpetas y abriendo \
 los archivos **.ipynb** , esta es una de las ventajas del jupyter notebook, su fácil visualización.
#### Tratamiento Datos con Pandas:
+ Todo el código generado se encontrará en la carpeta **Cursos/Tratamiento_Datos_Pandas**
#### Manipulación de DataFrames con Pandas:
+ Es una pequeña expansión del curso de tratamiento, todos los archivos se encontrarán en **Cursos/Manipulacion_Dataframes**
#### NumPy:
+ Los archivos estarán en el directorio **Cursos/NumPy**
### Talleres
#### Lectura y escritura de diferentes fuentes con Pandas
+ Todo lo realizado se encontrará en **Talleres/Lectura_Escritura**
+ Aquí aprenderemos a escribir y leer archivos como (csv ,pdf, api(online), json, html y pickle)
#### Caso de estudio con Pandas
+ El directorio será **Talleres/Caso_estudio_pandas**
+ Realizaremos una práctica de posibles tareas (sencillas) que nos mandarían hacer como Data Sciencists
#### EDA: Exploratory Data Analysis con Python
+ El directorio será **Talleres/Exploratory_data_analysis**
+ Aprenderemos a clasificar bien los datos y estudiar su relevancia. Así mismo haremos un pequeño entrenamiento de una maquina