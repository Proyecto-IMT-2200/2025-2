# 📊 Proyecto de Ciencias de Datos

Este repositorio contiene el desarrollo de un proyecto académico para la asignatura de **Ciencias de Datos**.  
Aquí se incluyen los códigos, análisis y documentación asociados al trabajo en equipo , el trabajo como tal se encuentra dentro de la carpeta notebooks, llamandose presentacion.ipynb.

---

## 👥 Integrantesa

- Sebastián Ignacio Mena — [@Sebastmenas](https://github.com/Sebastmenas)  
- Matías Pérez Unda — [@sone6e](https://github.com/sone6e)  
- Esteban Ignacio Cortes — [@esteban78009](https://github.com/esteban78009)  

---
## 💾 Datos
para abrir y poder ejecutar el jupyter se requieren de datos, los cuales se pueden encontrar publicos en la pagina del demre [https://portal-transparencia.demre.cl/portal-base-datos] o descargar directamente en el siguiente link [https://uccl0-my.sharepoint.com/:f:/g/personal/sebastin_mena_estudiante_uc_cl/EhgUUbAemNVLubCEjJvLvMkBOtbi40OF61aDvJpW7fV5DA?e=ymSFkT] (se recomienda la ultima opcion puesto que es instalar y poner en la carpeta , ademas de para no saturar los servidores del demre)

## Ejecucion del repositorio 💻

Para ejecutar el repositorio se debe de tomar los datos presentados en la seccion datos y dejarlo en la forma que se presenta en la seccion {Contenido del repositorio}, posterior a eso se puede ejecutar los jupyter, que se requieren en un cierto orden, y se recomienda este mismo orden

respecto a la ejecucion de nuestro codigo, se requieren de las librerias dadas en requirements.txt ademas del uso de python3.13 , posterior a esto se deben de ejecutar, primero, la lectura de archivos, para tener los datos, de forma correcta en pkl-data y csv_respaldo (carpetas que deben ser creadas por el usuario) posterior a esto, se pueden ejecutar el resto de preguntas, y el archivo presentacion que contiene todo nuestro analisis, el archivo presentacion depende de datos de todo el resto de archivos, es por eso que es imperativo la ejecucion del resto de notebooks para su posterior ejecucion.

respecto a la carpeta prototipos, al ser prototipos y no la entrega final se muestra como una muestra de la travesia que a sido el proyecto y no esperamos una revision de la misma, mas alla de una vision por un tema de curiosidad por como se desarollo nuestro trabajo.

## 📂 Contenido del repositorio
```
2025-2/
|_ NoteBooks/
|  |--Graficos-Imagenes/
|  |--|[en graficos-imagenes se contienen los datos usados para la presentacion]
|  |--pkl-data/ [datos peakle]
|  |--raw_data/ datos_crudos
|  |--pregunta1.ipynb
|  |--pregunta2.ipynb
|  |--pregunta3.ipynb
|  |--pregunta4.ipynb
|  |--pregunta5.ipynb
|  |--Modelo_Predictivo_NEM _ff.ipynb
|  |--Lectura_Archivos.ipynb
|  |--presentacion.ipynb
|_ .gitignore
|_ Prototipos/
|__Borrador_Proyecto.ipynb
|__Borrador_trabajo_final_seba.ipynb
|_ requirements.txt
|_ README.md
```

## ⚙️ Librerias utilizadas
```
matplotlib.pyplot 
seaborn 
pandas 
numpy
os
pathlib
copy --> deepcopy -
sklearn
pickle
```

## Motivaciones e ideas

En el contexto de la educacion se sabe que se tiene una educación desigual a lo largo de nuestro país, en este contexto presentamos nuestro proyecto, buscamos hacer un analisis de este mismo entorno.

### Objetivo principal

Nuestro objetivo es poder, mediante el análisis de los datos, responder preguntas como: ¿De qué sectores socioeconómicos vienen los estudiantes universitarios de nuestro pais?
¿Cuáles comunas tienen la mayor cantidad de estudiantes de la educacion superior?
¿Cuánta gente ha dado la prueba a lo largo de los años?
Entre otras preguntas, todas con el objetivo en mente de comprender de mejor manera como ha cambiado el entorno a lo largo de los años, cómo está el tema de la equidad, si ha mejorado o empeorado en este y otros aspectos, y poder dar una imagen clara de cómo esta la educación superior a lo largo de nuestro país.

### Cómo lo hicimos

La respuesta a las preguntas dadas se hizo mediante un analisis de datos basados en los datos publicos de la página web del DEMRE, buscando así hacer relaciones entre las mismas para poder responder las preguntas dadas. Se requirió hacer una limpieza de los datos, eliminando valores nulos o inconsistentes, además de hacer correlaciones y uniones en las bases de datos para poder responder las preguntas dadas, todas estas mismas se presentan en el Jupyter Notebook junto al codigo de las mismas.

### ¿Se respondieron las preguntas y se cumplió el Objetivo dado?

Sí, se logró responder a las preguntas presentadas en el PDF que era el guía de nuestro proyecto. Además, consideramos cumplido el objetivo de hacer un análisis de datos buscando saber cómo está el area del acceso a la educación superior, sabiendo de dónde provienen nuestros futuros profesionales y cómo ha cambiado el entorno de la educacion/acceso a la universidad a lo largo de los años.

### Organizacion

La manera de organizarnos fue

pregunta 1/2 => hecha por sebastian mena
pregunta 4 => Esteban cortes
pregunta 3 => Matías Pérez
pregunta 5 => hecha en conjunto

el resto fue hecho en colaboracion entre todos.