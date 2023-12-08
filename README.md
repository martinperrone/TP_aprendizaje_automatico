![feceia1](https://github.com/martinperrone/TP_aprendizaje_automatico/assets/109038969/1e6bd2ee-df8f-4f79-93fd-6d11caba36da)
![Banner-ML](https://github.com/martinperrone/TP_aprendizaje_automatico/assets/109038969/561b89d0-0b40-4afb-8417-85be0f42c224)

# Tecnicatura en Inteligencia Artificial 

## Trabajo Práctico: Predicción de lluvia en Australia.

Estudiantes:

* Alomar, Francisco J.
* Perrone, Martín L.

El objetivo del trabajo práctico es utilizar los datos proporcionados en el dataset de nombre weatherAUS.csv, que contiene información climática de Australia de los últimos diez años, para hacer una app que predice si llueve y la cantidad de lluvia.
Realizamos el análisis y tratamiento de los datos, selección de características para la predicción y probamos diferentes modelos de aprendizaje automático (regresión lineal y logística, regulación, redes neuronales) para obtener el de mejor funcionamiento. Todo esto lo hicimos en una notebook con Google Colaboratory, de nombre ***_tp_aprendizaje_entrega_final.ipynb_***, del que exportamos dos pipelines con los modelos de clasificación y regresión de redes neuronales entrenados en los archivos ***_lluvia_australia_clas_prediction.pkl_*** y ***_lluvia_australia_reg_prediction.pkl_*** respectivamente. 
Luego generamos la app de predicción de lluvia utilizando la librería streamlit de pyhton, que importa los pipelines generados para realizar las predicciones con los datos nuevos.


<h1>🌧️ App de predicción de lluvia en Australia 🌧️</h1><br>


<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b>Humidity</b></td>
    <td>Cantidad de humedad del día (0.01 / 100) </td>
  </tr>
  <tr>
    <td><b>Pressure</b></td>
    <td>Valor de la presión del día (100 / 1100)</td>
  </tr>
  <tr>
    <td><b>Cloud</b></td>
    <td>Nubosidad del día (0.01 / 10)</td>
  </tr>
  <tr>
    <td><b>MinTemp</b></td>
    <td>Temperatura mínima del día (-10 / 55)</td>
  </tr>
  <tr>
    <td><b>MaxTemp</b></td>
    <td>Temperatura máxima del día (-10 / 55)</td>
  </tr>
  <tr>
    <td><b>Rainfall</b></td>
    <td>Cantidad de lluvia del día (0.01 / 400)</td>
  </tr>
  <tr>
    <td><b>WindSpeed</b></td>
    <td>Velocidad del viento (0.01 / 200)</td>
  </tr>
  <tr>
    <td><b>Temp</b></td>
    <td>Temperatura promedio (-10 / 55)</td>
  </tr>
  <tr>
    <td><b>WindDir</b></td>
    <td>Dirección del viento (N,S,E,O)</td>
  </tr>
  <tr>
    <td><b>Estacion</b></td>
    <td>Estación del año.</td>
  </tr>
  <tr>
    <td><b>RainToday</b></td>
    <td>Informar si llovió en el día (Yes / No)</td>
  </tr>
  </tr>
</table>
<br><br>

### Modo de uso:
#### Software y Librerías necesarios:
  - Python versión 3.10.4 o superior
  - Streamlit
  -      pip install streamlit
  - Joblib
  -     pip install joblib
  - Pandas
  -     pip install pandas
  - Sklearn
  -     pip install -U scikit-learn
  - Numpy
  -     pip install numpy
  - Keras
  -     pip install keras
  - Tensorflow
  -     install tensorflow
  
### Pasos a seguir:

1. URL https://github.com/martinperrone/trabajopracticofinal.git

2. Descargar los archivos:
   - app.py
   - clases_y_funciones.py
   - lluvia_australia_clas_prediction.pkl
   - lluvia_australia_reg_prediction.pkl

3. Ejecutar por consola la app con el siguiente comando: python.exe -m streamlit run app.py

4. Elegir los valores de las features y hacer clik en Submit:


![captura de pantalla(1)](https://github.com/martinperrone/TP_aprendizaje_automatico/assets/109038969/0ab89593-dd4b-486b-96c1-de653e9106cc)
![captura de pantalla(2)](https://github.com/martinperrone/TP_aprendizaje_automatico/assets/109038969/c9c18fbd-176c-48e3-8be1-1b45dce2f4c1)


       

