# Analítica Predictiva y Prescriptiva 🎓👩‍💻
## _Brecha de género en los ingresos del mercado salarial de Chile_

[![My Skills](https://skillicons.dev/icons?i=py,github)](https://skillicons.dev)

## Descripción
Este proyecto tiene como objetivo desarrollar un análisis predictivo y prescriptivo basado en los datos previamente procesados durante las etapas de analítica descriptiva y diagnóstica [Analítica descriptiva - Web Scraping][df1] y [Analítica diagnóstica - Web Scraping][df2] respectivamente. El repositorio cuenta con dos notebook's de Python que utiliza librerias como _'Pandas'_, _'Matplotlib'_ , _'Scikit-learnn'_ y _'numpy'_ para realizar las visualizaciones y cálculos necesarios, implementando dos modelos predictivos principales:
- **Regresión Lineal**:Utilizada para identificar relaciones lineales entre las variables y generar predicciones continuas basadas en los patrones observados. Este modelo es adecuado para casos donde las variables tienen una relación proporcional.
- **Random Forest**: Modelo basado en árboles de decisión que emplea un enfoque de ensamble para mejorar la precisión de las predicciones. Es útil para detectar relaciones no lineales y manejar datos con múltiples características.

## Contenido

- **Analitica_Predictiva_y_Prescriptiva.ipynb** : Este notebook se centra en la creación de los modelos mencionados anteriormente y la visualización de datos utilizando gráficos y metricas.
- **3-4.ipynb** : Unión de los dataset de los trabajos anteriores.
- **dataset_final.csv** : Data set creado con el archivo anterior, que se utilizó para la creación de los modelos.

## Tecnologías utilizadas

- Jupyter Notebook
- Google Colab
- Scikit-learnn
- numpy

```sh
!pip install scikit-learn
!pip install numpy 
```
## Ejecución en Google Colab

Para facilitar la ejecución del análisis, se recomienda utilizar [Google Colab](https://colab.research.google.com/). Colab permite ejecutar código Python en la nube sin necesidad de configuraciones locales, lo que es ideal para trabajar con datos y bibliotecas.

### Instrucciones

1. Abre Google Colab en tu navegador.
2. Crea un nuevo notebook.
3. Copia y pega el código del análisis desde este repositorio en las celdas del notebook.
4. Asegúrate de cargar los archivos CSV necesarios en el entorno de Colab. Puedes hacerlo utilizando la función de carga de archivos o montando tu Google Drive.
5. Ejecuta las celdas para realizar el análisis y visualizar los resultados.

### Ejemplo de Carga de Datos

Puedes usar el siguiente código para cargar los archivos CSV desde tu Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```
>Si no está familiarizado con colab aquí está el link directo al proyecto
>el archivo al estar privador debe solicitar permiso para visualizarlo,
>luego solo tiene que dar click a 'Ejecutar todas las celdas'
>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1klrbjKtGyusJ0TiQ5ndqa8eAalzIHh0R)

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

# Agradecimientos🎅
Queremos agradecer a los siguientes autores por el arduo trabajo en este proyecto:

- **Ignacia Quezada** - [VicQA96][df6]
- **Thiare Águila** - [ThiareAguila][df7]

**2024-S2 ANALÍTICA INFB6100📘!**

   [df1]: <https://github.com/VicQA96/web-scraping>
   [df2]: https://github.com/VicQA96/analitica-diagnostica
   [df6]: <https://github.com/VicQA96>
   [df7]: <https://github.com/ThiareAguila>
