# 👩🏻‍🚀 Ciencia de datos aplicada: Space Y - IBM 🚀

Proyecto final de ciencia de datos para aplicar los conocimientos adquiridos durante el programa del <strong>Certificado profesional de Ciencia de datos de IBM.</strong>

<img src='https://images.unsplash.com/photo-1517976487492-5750f3195933?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80'>

## <center>Descripción:</center>

Para esta tarea, asumí el papel de un científico de datos que trabaja para una nueva 
compañía de cohetes: <strong><font color="#088880">Space Y.</font></strong>

Mi trabajo fue predecir si los lanzamientos de mi competencia, <strong><font color="#088880">Space X</font></strong>, aterrizaran con éxito, prestando atención a la primera etapa. <strong>Primera etapa 
es el factor que posibilita que los lanzamientos de cohetes sean relativamente económicos para 
esta empresa</strong>.

En lugar de usar ciencia espacial para predecir esto, entrené y refiné modelos de machine learning con información pública de la competencia que previamente recopilé y procesé.

## <center>Un poco de contexto...</center>

En su sitio web, Space X anuncia lanzamientos de cohetes Falcon 9 con un 
costo de 62 millones de dólares, siendo que otros proveedores cuestan más 
de 165 millones de dólares cada uno. Gran parte del ahorro se debe a que 
Space X puede reutilizar la primera etapa. Por lo tanto, <strong>si puedo determinar 
si la primera etapa aterrizará con éxito, y por ende será reutilizada, puedo 
determinar el costo de un lanzamiento.</strong> <font color="#FFD580">Esta información es útil si una 
empresa alternativa quiere hacer una oferta contra <strong>Space X</strong> para el 
lanzamiento de un cohete, como es el caso de <strong>Space Y</strong></font>.

## <center>Estructura del proyecto</center>

+ <a href='https://github.com/LilenFr/IBM-SpaceY-es/tree/master/1-primera_semana'>1-primera_semana</a>: Obtención y disputa de datos.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/1-primera_semana/1-obtener_datos_API.ipynb'>1-obtener_datos_API.ipynb</a>: Recolección de datos a través de la API de Space X.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/1-primera_semana/2-obtener_datos_webscraping.ipynb'>2-obtener_datos_webscraping.ipynb</a>: Recolección de datos haciendo web scraping a una wiki con información de interés.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/1-primera_semana/3-disputa_datos.ipynb'>3-disputa_datos.ipynb</a>: EDA y creación de etiquetas de entrenamiento.
+ <a href='https://github.com/LilenFr/IBM-SpaceY-es/tree/master/2-segunda_semana'>2-segunda_semana</a>: EDA con SQL y visulización de datos.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/2-segunda_semana/4-EDA_Sql.ipynb'>4-EDA_Sql.ipynb</a>: EDA con consultas SQL e integración con una instancia DB2 de IBM.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/2-segunda_semana/5-EDA_visualizacion.ipynb'>5-EDA_visualizacion.ipynb</a>: EDA con visualización de datos usando las librerías Matplotlib y Seaborn.
+ <a href='https://github.com/LilenFr/IBM-SpaceY-es/tree/master/3-tercera_semana'>3-tercera_semana</a>: Análisis visual interactivo.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/3-tercera_semana/6-analisis_visual_interactivo_1.ipynb'>6-analisis_visual_interactivo_1.ipynb</a>: Análisis de mapas con Folium.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/3-tercera_semana/7-analisis_visual_interactivo_2.ipynb'>7-analisis_visual_interactivo_2.ipynb</a>: Creación de un tablero con Plotly Dash para interactuar con los datos en tiempo real.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/3-tercera_semana/spacex_dash_app.py'>spacex_dash_app.py</a>: App Plotly Dash.
+ <a href='https://github.com/LilenFr/IBM-SpaceY-es/tree/master/4-cuarta_semana'>4-cuarta_semana</a>: Modelos predictivos.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/4-cuarta_semana/8-analisis_pred_ML.ipynb'>8-analisis_pred_ML.ipynb</a>: Ajuste de cuatro modelos de clasificación con GridSearchCV.
+ <a href='https://github.com/LilenFr/IBM-SpaceY-es/tree/master/5-quinta_semana'>5-quinta_semana</a>: Presentación del proyecto.
    * <a href='https://github.com/LilenFr/IBM-SpaceY-es/blob/master/5-quinta_semana/presentacion.pdf'>presentacion.pdf</a>: Presentación hecha en Power Point exportada como pdf.
+ datasets: Carpeta encargada de almacenar los distintos datasets utilizados y producidos por de los cuadernos jupyter.
+ requirements.txt: Contiene las dependencias necesarias para el correcto desarrollo de los cuadernos.

## <center>Ver proyecto / correr cuadernos</center>

+ Por cuestiones de renderizado, se recomienda ver el proyecto con <strong>nbviewer</strong> a través del siguiente <a href='https://nbviewer.org/github/LilenFr/IBM-SpaceY-es/tree/master/'>link.</a>

+ Para interactuar con el proyecto a nivel local y correr los cuadernos jupyter:
    ```sh
    # Primero clonar repositorio
    git clone https://github.com/LilenFr/IBM-SpaceY-es.git
    # instalar las dependencias necesarias
    pip install -r requirements.txt
    # Correr JupyterLab
    jupyter-lab
    ```
    
## <center>Menciones especiales</center>

Agradecer a <a href='https://www.coursera.org/instructor/yanluo'>Yan Luo</a> y a <a href='https://www.coursera.org/instructor/~28511493'>Joseph Santarcangelo</a>, tutores principales del <a href='https://www.coursera.org/learn/applied-data-science-capstone/home/week/1'>curso final</a> del programa de <a href='https://www.coursera.org/professional-certificates/ibm-data-science'>ciencia de datos de IBM</a>, que me acompañó durante el desarrollo de este proyecto.

---

<strong>¡Saludos! 🙋🏻</strong>
