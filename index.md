---
layout: default
title: Inicio
---

# Análisis de las pruebas de acceso a la educación superior

### Como grupo buscamos el analizar y también el responder las dudas que hemos tenido a lo largo del proceso y resultados de la prueba de acceso a la educación superior chilena , buscamos el examinar la relación entre la equidad y estos mismos procesos , desde un ámbito informativo explicar el cómo estas diversas pruebas (PSU , PTU , PAES) han ido cambiando el quien accese a la educación universitaria

### Importante, todos los datos a analizar se recolectaron en https://portal-transparencia.demre.cl/portal-base-datos , para mayor información ver nuestro jupyter notebook [https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/Lectura_Archivos.ipynb]

### Integrantes del grupo:

```
Esteban Cortes
Sebastian Mena
Matias Gonza
```

# UN POCO DE CONTEXTO

A lo largo del tiempo nuestro país a tenido diversas pruebas para con el acceso a la educación superior, las cuales han ido cambiado en contenidos y metodología de medición a lo largo de los años, en este contexto nosotros buscamos hacer un análisis de los datos presentados enfocados en las siguientes preguntas y ver como se relacionan/que cambios se pueden ver reflejados a través de la respuestas de estas preguntas a lo largo del tiempo:

```
- 1°¿Cuantas personas se incribieron en cada periodo de admision entre 2004 a 2025?

- 2°¿Hubo un aumento en las inscripciones en los periodos de transicion (PSU/PTU/PAES)?

- 3°Segun el gruposocioeconomico , ¿cual fue el porcentaje de ingresos a la educacion superior?

- 4°¿Que comunas presentaron los mayores porcentajes de ingresos a la educacion superior?

- 5°¿Que relacion existe entre la situacion de egreso de los estudiantes y los resultados de admision a la educacion superior?
```

## Pregunta 1
- ¿Cuántas personas se inscribieron en cada periodo de admisión entre 2004 a 2025?

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/pregunta1.png?raw=true" alt="Texto alternativo" width="100%">
    </td>
    <td width="50%">
      <h3>¿Hubo un aumento en las inscripciones en los periodos de transición (PSU/PTU/PAES)?</h3>
      <p>Aquí en el gráfico presentado podemos ver la cantidad de gente que ha rendido esta prueba, esto a lo largo de los años, permitiendo identificar la tendencia al alza a lo largo de los años , siendo el punto más alto el año 2024 (admisión 2025) con más de 300.000 personas yendo al examen</p>
      <ul>
        <li>Importante, entre el 2010 a 2014 se puede notar un claro descenso en la curva ascendente de años pasados, nuestra hipótesis como grupo es que esto fue a razón del terremoto del 2010</li>
        <li>Respecto al descenso de los años 2020 a 2021, estos mismos fueron surgidos debido a la pandemia de COVID-19 , no profundizaremos en como esta pandemia ha afectado este proceso ni a su educación, aunque en el gráfico se ve una recuperación de la misma</li>
        Conclusión final, se puede ver una clara tendencia al alza en la cantidad de personas que rinden la prueba de acceso a la educación superior a lo largo de los años
      </ul>
    </td>
  </tr>
</table>

## Pregunta 2
- ¿Hubo un aumento en las inscripciones en los periodos de transición (PSU/PTU/PAES)?

La respuesta es, depende, depende de los años y el periodo en el cual estemos para con nuestra historia, por ejemplo:

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/pregunta2psu.png?raw=true" alt="Imagen 1" width="100%">
    </td>
    <td width="50%">
      <h3>Resultados PSU</h3>
      <p>En el gráfico presentado se puede notar una tendencia alcista hasta la década del 2010, este es un ejemplo perfecto de la respuesta del "depende", al haber una crisis esos años en nuestro país, menos gente tuvo el tiempo y/o recursos para su educación, por esto mismo y en años superiores se vio una bajada en la gente rindiendo esta prueba </p>
    </td>
  </tr>

  <tr>
    <td width="50%">
      <h3>Resultados PTU</h3>
      <p>podemos notar un gráfico muy alcista, este mismo , al ser pocos años, se notan "más grandes" en relación a los datos brutos, sin embargo permite el notar el aumento hacia el deseo de estudiar por el estudiantado , en el momento post pandemia (2021, 2022)</p>
    </td>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/pregunta2ptu.png?raw=true" alt="Imagen 2" width="100%">
    </td>
  </tr>

  <tr>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/pregunta2paes.png?raw=true" alt="Imagen 3" width="100%">
    </td>
    <td width="50%">
      <h3>Resultados PAES</h3>
      <p>Podemos notar que, al igual que el gráfico antes PSU , peca de no poseer una alta cantidad de datos, la diferencia relativa más grande es una tendencia más alta, mostrando una leve "caída" en su tendencia en los años posteriores al 2024</p>
    </td>
  </tr>
</table>

<br>

## Pregunta 3
- Según el grupo socioeconómico , ¿cuál fue el porcentaje de ingresos a la educación superior?

En esta pregunta analizamos cómo se distribuyen los estudiantes que ingresan a la educación superior según su grupo socioeconómico (GSE), usando información de ingreso familiar disponible en los datos del DEMRE entre 2004 y 2025.

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/pregunta3.png?raw=true" alt="Distribución de grupos socioeconómicos por universidad" width="100%">
    </td>
    <td width="50%">
      <h3>Distribución de grupos socioeconómicos por universidad</h3>
      <p>El gráfico muestra, para cada universidad, el porcentaje de sus estudiantes matriculados que pertenecen a cada grupo socioeconómico (GSE): AB, C, D y E. Para construirlo se promediaron los años 2004–2025, de modo que cada barra ve la composición socioeconómica de cada universidad.</p>
      <ul>
        <li>Desde el campo de ingreso familiar se extrajo un tramo numérico entre 1 y 12, que luego se agrupó en cuatro GSE: tramos 1–2 → E (más vulnerables), 3–4 → D, 5–8 → C y 9–12 → AB (ingresos más altos).</li>
        <li>Para cada universidad se contó cuántos estudiantes pertenecen a cada GSE y se transformó a porcentajes, de manera que la suma por universidad es 100%.</li>
        <li>Las barras están ordenadas según el porcentaje del grupo AB, de mayor a menor, para facilitar la comparación entre universidades.</li>
      </ul>
      <p>En el gráfico se puede observar una fuerte desigualdad: las universidades más selectivas y privadas concentran una mayor proporción de estudiantes en los grupos AB–C, mientras que muchas universidades tienen mayoría de estudiantes en los grupos D–E. Esto se mantiene casi igual durante en el período 2004–2025, lo que nos indica que el acceso universitario sigue estando fuertemente asociado al nivel de ingreso familiar.</p>
    </td>
  </tr>
</table>

<br>

## Pregunta 4
- ¿Que comunas presentaron los mayores porcentajes de ingresos a la educacion superior?

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/tendencia_egresados_pregunta4.png?raw=true" alt="Texto alternativo" width="100%">
    </td>
    <td width="50%">
      <h3>Comunas que representan los mayores porcentajes de ingresos a la educación superior</h3>
      <p>se puede notar del grafico una tendencia a mantenerse el top5 mayores comiunas, siendo estas mismas santiago , maipu, temuco , concepcion y puente alto, como grupo creemos que este resultado es debido a factores tanto poblacionales como de ayudas hacia la educacion que permite a mas gente ir a estudiar/educarse.</p>
    </td>
  </tr>
</table>

<br>

## Pregunta 5
- ¿Que relacion existe entre la situacion de egreso de los estudiantes y los resultados de admision a la educacion superior?

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/pregunta5.png?raw=true" alt="Texto alternativo" width="100%">
    </td>
    <td width="50%">
      <h3>¿cual es la relacion existente entre la situacion de egreso de los estudiantes y los resultados de la admision a la educacion superior?</h3>
      <p>La relacion entre la situacion de egreso y los resultados de admision nos muestran que los recien egresados(primera prueba) suele tener mejores resultados tanto en tasas de matriculacion como en sus puntajes, tambien existen una tendencia descendiente entre ambos indicadores a medida que aumentan los años , esto nos da a entende que quienes llevan mas tiempo afuera del sistema escolar, suelen tener un impacto negativo en su oportunidad de acceder a la educacion superior</p> 
    </td>
  </tr>
</table>

## BONUS Pregunta 6
- ¿Qué grupo socioeconómico resultó más afectado por el terremoto del 2010?

Como grupo nos dio una curiosidad respecto a la bajada de inscripciones en los años posteriores al terremoto del 2010, por lo que decidimos hacer un analisis extra respecto a esto

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/terremoto2010.png?raw=true" alt="Texto alternativo" width="100%">
    </td>
    <td width="50%">
      <h3>Grupos socioeconomicos afectados</h3>
      <p>A partir del grafico se puede notar que dependiendo del grupo socioeconomico de las personas, tuvieron un impacto mayor o menor en cuando a como les afecto el terremoto del 2010 , prevaleciendo los grupos con menos redes de apoyo</p> 
    </td>
  </tr>
</table>

# Modelo predictivo de puntajes PAES

Como grupo creamos un modelo predectivo regresivo que busca el ser una herramienta que predisca los datos del puntaje paes por medio del puntaje nem, esto como herramiuenta que ayude a la ciudadania a saber que puede esperar en su respectiva prueba de acceso a la educacion superior

<table width="100%" style="border: none;">
  <tr style="border: none;">
    <td width="50%" style="vertical-align: top; border: none;">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/regresion_lineal_multiple.png?raw=true" alt="Regresion lineal" width="100%">
    </td>
    <td width="50%" style="vertical-align: top; padding-left: 20px; border: none;">
      <h3>Regresion lineal multiple</h3>
      <p>Aqui podemos ver los resultados de la dispercion de datos con los resultados del modelo</p>
      <ul>
        <li>=== Regresión Polinomial (Grado 2) ===
Features generados: 5
R² (train): 0.2697
R² (test): 0.2724
MSE: 14060.5262
RMSE: 118.5771
MAE: 96.1683</li>
        <li>=== Regresión Polinomial (Grado 3) ===
Features generados: 9
R² (train): 0.2714
R² (test): 0.2735
MSE: 14039.8142
RMSE: 118.4897
MAE: 96.0576</li>
      </ul>
    </td>
  </tr>
</table>

<br>

<table width="100%">
  <tr>
    <td width="33%" style="vertical-align: top; padding: 10px;">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/regresion_polinomial.png?raw=true" width="100%">
      <p>Estos son los datos en diversos modelos y entrenamientos </p>
    </td>
  </tr>
</table>

<br>

<table width="100%">
  <tr>
    <td width="33%" style="vertical-align: top; padding: 10px;">
      <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/Comparacion_modelos.png?raw=true" width="100%">
      <p>Comparativa entre los diversos modelos
      
      
      Usando los mismos podemos ver que el mejor modelo es el polinomial de grado 3
  </tr>
</table>

<br>

<div align="center">
    <h3></h3>
    <img src="https://github.com/Proyecto-IMT-2200/2025-2/blob/main/NoteBooks/graficos-imagenes/estadisticas_residuos.png?raw=true" alt="Descripcion" width="80%">
    <p style="font-style: italic; color: #666; font-size: 0.9em;">
        Por medio de nuestro modelo obtuvimos diversos analisis predictivos.
    </p>
</div>

<br>

### Resultados predictivos de nuestro modelo

<table border="1" width="100%" cellspacing="0" cellpadding="5" style="border-collapse: collapse; text-align: center;">

  <tr style="background-color: #f0f0f0;">
    <th width="25%">Mate 1</th>
    <th width="25%">Clec</th>
    <th width="25%">Promedio Nem</th>
    <th width="25%">Puntaje paes predicho</th>
  </tr>

  <tr>
    <td>400</td>
    <td>400</td>
    <td>400.0</td>
    <td>624.70</td>
  </tr>

  <tr>
    <td>500</td>
    <td>500</td>
    <td>500</td>
    <td>649.37</td>
  </tr>

  <tr>
    <td>600</td>
    <td>600</td>
    <td>600</td>
    <td>701.81</td>
  </tr>

  <tr>
    <td>700</td>
    <td>700</td>
    <td>700</td>
    <td>767.27</td>
  </tr>

  <tr>
    <td>800</td>
    <td>800</td>
    <td>800</td>
    <td>831.03</td>
  </tr>

  <tr>
    <td>600</td>
    <td>700</td>
    <td>650.0</td>
    <td>726.66</td>
  </tr>

  <tr>
    <td>700</td>
    <td>600</td>
    <td>650.0</td>
    <td>740.00</td>
  </tr>

</table>

<br>

## ¿Que podria haber salido mal?

Queremos dedicar una seccion de nuestro analisis a comentar nuestros sesgos personales

de partida, tenemos un sesgo social , con el pensamiento de , las mejores comunas en el aspecto socioeconomico tambien tendran acceso a una educacion basica/media de mejor calidad, esto si bien , puede o no ser verdad, esto no elimina el ser un sesgo importante.

Tambien , asumimos como grupo que nuestra base de datos es correcta y esta sin errores graves de medicion, si bien esto fue tomando la mismisima fuente de los datos, es importante comentar que cualquier error en la medida de los datos nos afecta a nosotros

Tambien, nos enfocamos de manera extrema solamente en el acceso a la educacion superior y los puntajes, en este sentido, no hubo mucho enfoque en que tipo de educacion superior, en si entraron a una universidad , un instituto , entre otros

Respecto a nuestro modelo, si bien el modelo ses predictivo y presenta lo que buscabamos, es importante aclarar que no es perfecto, puede tener errores y la tendencia que marca no es absoluta ni debe tomarse como verdad absoluta.



###### Uso de IA para el desarollo de esta pagina web https://gemini.google.com/share/215f10f2ceb9
