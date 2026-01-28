# Trabajo Fin de Estudios del Máster de Análisis y Visualización de Datos Masivos de la UNIR. Realizado por Sergio Gómez García. 
#### <div align="justify"> En este documento se procederá a explicar como replicar los datos obtenidos a través de los documentos proporcionados en el repositorio. En este caso se explica desde Google Colab ya que permite despreocuparse bastante de la instalación de librerías y la compatibilidad entre las mismas, además de ser la opción por la que se acabó optando durante el desarrollo del trabajo. En caso de querer ejecutarlo desde Anaconda y Jupyter Notebook, instalar las librerías necesarias comprobando la compatibilidad, los pasos serán muy similares en esta otra herramienta. </div>

# Google Colab

## 1º Paso: 
### <div align="justify"> Descargar el fichero zip titulado como DATOS_ACCIDENTES.zip, una vez descargado, en la carpeta se mostrarán 3 ficheros, el fichero a utilizar en el resto de pasos es el titulado como ACCIDENTES-DEFINITIVOS3.csv </div>

## 2º Paso:
### <div align="justify"> Descargar los ficheros con extensión .ipynb, tanto el de R como el de IA, una vez descargados acceder a la página oficial de Google Colab (https://colab.research.google.com/), en la que será necesario iniciar sesión con la cuenta de Google personal, una vez iniciada la sesión se abrirá un recuadro con diferentes opciones para usar un cuaderno, en este caso se seleccionará la opción de subir, tal y como se muestra a continuación y se subirá el cuaderno descargado anteriormente, una vez haya cargado correctamente se abrirá automaticamente para poder ejecutarlo, repetir este proceso para ambos cuadernos. </div>

<p align="center">
  <img width="893" height="558" alt="image" src="https://github.com/user-attachments/assets/ef46dc69-97b9-4731-b7b6-6f32221e1975" />
</p>

## 3º Paso:

### <div align="justify"> Una vez abierto el cuaderno, antes de ejecutar el código, es necesario cargar el csv descargado anteriormente, para ello, en el panel lateral izquierdo seleccionar la sexta opcion, la que tiene icono de carpeta, a continuación arrastar el fichero csv hacia la carpeta y esperar a que se suba por completo. En el caso del fichero de IA, se podria también subir el fichero en Google Drive y desde Google Colab montar Google Drive seleccionando la tercera opción de nuestra carpeta y esperando a que se cargue correctamente, tal y como se muestra en la siguiente imagen. </div>

<p align="center">
  <img width="360" height="396" alt="image" src="https://github.com/user-attachments/assets/a21022d4-9ff4-4990-8d81-2cae6b83d1d8" />
</p>

## 4º Paso:

### <div align="justify"> Una vez cargado el fichero, colocarse sobre el mismo y hacer click en los 3 puntos, después, hacer click en copiar ruta, esto será muy importante ya que sin la ruta correcta los cuadernos no podrán ser ejecutados, por último, buscar en el código la linea donde pone DATA_PATH en el caso de IA y ruta_fichero en el caso de R y sustituir el valor por la ruta copiada anteriormente, tal y como se muestra en las siguiente imagenes. </div>

<p align="center">
  <img width="381" height="169" alt="image" src="https://github.com/user-attachments/assets/ce02682d-f764-4a61-829a-10f99ef9bdeb" />
</p>

<p align="center">
  <img width="308" height="163" alt="image" src="https://github.com/user-attachments/assets/51e1db88-c578-474c-a2c9-d6325acefda5" />
</p>

<p align="center">
  <img width="525" height="58" alt="image" src="https://github.com/user-attachments/assets/6817da0f-a50b-41fc-8e51-93f79f88e97b" />
</p>

<p align="center">
  <img width="428" height="40" alt="image" src="https://github.com/user-attachments/assets/27ace635-02b7-45b9-8d16-c1cb9a516fb4" />
</p>

## 5º Paso:

### <div align="justify"> Antes de ejecutar el cuaderno, es muy importante que el entorno de ejecución sea el correcto, para ello hacer click en entorno de ejecución y posteriormente en cambiar tipo de entorno de ejecución, para el caso de IA deberá de figurar Python y en el caso de R deberá de figurar R, tal y como se muestra en las siguientes imágenes. </div>

<p align="center">
  <img width="445" height="541" alt="image" src="https://github.com/user-attachments/assets/7cd8141f-ccc7-4130-9cdb-2ba9b7683626" />
</p>

<p align="center">
  <img width="557" height="526" alt="image" src="https://github.com/user-attachments/assets/f2e497c1-1691-4c68-aa65-e7c4e2190d58" />
</p>

<p align="center">
  <img width="557" height="519" alt="image" src="https://github.com/user-attachments/assets/0d251774-75a9-4fdb-b8f7-161ac4e21dbb" />
</p>

## 6º Paso:

### <div align="justify"> Ahora ya se puede ejecutar los códigos sin ningún problema, para ello simplemente hay que darle al botón de play, tal y como se muestra en la siguiente imagen, tener en cuenta que en el caso de R es muy importante que primero se ejecute la línea de instalación de las librerias que no vienen instaladas por defecto en Google Colab y después ejecutar la línea de importación de las librerías. </div>

<p align="center">
  <img width="484" height="243" alt="image" src="https://github.com/user-attachments/assets/5f24f09e-b0f4-48ae-bd7a-f61c1a4d72af" />
</p>

# Power BI

## 1º Paso: 

### <div align="justify"> En caso de no tener Power BI instalado en el ordenador, descargarlo desde la web oficial de Microsoft (https://www.microsoft.com/es-es/power-platform/products/power-bi/downloads) e instalarlo, en caso de ya tenerlo instalado se puede omitir este paso. </div>

## 2º Paso: 

### <div align="justify"> Descargar el fichero TFM_DB.pbix del repositorio y hacer doble click en el, esto abrirá el proyecto automáticamente en Power BI y desde aquí ya se podrá ver las diferentes gráficas e interactuar con los distintos filtros, tal y como se ve en la siguiente imagen. </div>

<p align="center">
  <img width="761" height="425" alt="image" src="https://github.com/user-attachments/assets/69aa5710-03ae-4ef2-a1d4-c531fdadf2f5" />
</p>

## 3º Paso (Opcional): 

### <div align="justify"> En caso de dar problemas porque no encuentre los datos o se necesite especificar la ruta de los datos para algo en concreto, en la barra superior darle a transformar datos, tal y como se muestra en la imagen. </div>

<p align="center">
  <img width="642" height="145" alt="image" src="https://github.com/user-attachments/assets/57e526d3-d970-4b3e-8e31-f14cc790b4d5" />
</p>

### <div align="justify"> Se abrirá Power Query y para evitar perder los pasos realizados habrá que ir al menú lateral derecho y en pasos aplicados hacer click en Origen y cambiar la ruta que aparece por la de nuestro ordenador, tal y como se muestra en la siguiente imagen, finalmente se dará a cerrar y aplicar para aplicar los cambios correctamente. </div>

<p align="center">
  <img width="1356" height="388" alt="image" src="https://github.com/user-attachments/assets/3c46cb28-b2a6-4223-84c0-140ebcb922e1" />
</p>

# Scimago Graphica (Complementario)

### <div align="justify"> Aunque Scimago Graphica no se usó como tal para la parte de análisis estadístico o de inteligencia artificial, si fue usado para generar una de las gráficas que se pueden ver en el apartado de contexto del problema dentro del estado del arte, cuyos datos fueron descargados de la web oficial del INE (https://www.ine.es/jaxi/Tabla.htm?tpx=33350), para poder visualizar esta gráfica lo primero que habrá que hacer será descargar Scimago Graphica desde la web oficial (https://www.graphica.app/download) e instalarla, una vez instalada, descargar el fichero "Top hombres y mujeres.gph" del repositorio y hacer doble click sobre el, tras esto el fichero se abrirá automaticamente en la aplicación, tal y como se muestra en la imagen. </div>

<p align="center">
  <img width="1363" height="712" alt="image" src="https://github.com/user-attachments/assets/679b85d4-68fb-472b-b3b5-223df7b287d4" />
</p>
