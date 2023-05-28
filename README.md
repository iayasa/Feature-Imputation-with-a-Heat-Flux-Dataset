# Feature-Imputation-with-a-Heat-Flux-Dataset


![Captura de pantalla de la competición de Kaggle](picture_KaggleCompetition.png)


##  Descripción del problema: 
<br>
El objetivo de esta competición es desarrollar modelos de aprendizaje automático que puedan predecir y completar los valores faltantes en el conjunto de datos de flujo de calor. El conjunto de datos contiene información sobre diversas variables, como presión, flujo de masa, diámetros, longitudes y valores de flujo de calor. Sin embargo, algunos de estos valores están incompletos y es nuestro objetivo imputarlos de manera precisa.

<br>

## Estructura del repositorio:

- **Data**: Archivo que incluye los datos para el proyecto y un ejemplo de submission para cargar los datos en Kaggle. 
  <br>

- **submission.csv**: Archivo CSV de muestra que muestra el formato requerido para la presentación de resultados.
  <br>

- **notebooks**: Carpeta que contiene los cuadernos de Jupyter utilizados en el análisis exploratorio de datos, desarrollo de modelos y evaluación de resultados.
  <br>

- **README.md**: Archivo que proporciona información sobre la competición y el uso del repositorio.
  <br>

- **presentacion.ppt**: fichero donde se presentan el workflow y comparación de los modelos en base a la metricas RMSE, MSE, MAE y R2. 

## Evaluación: 

Error cuadrático medio (RMSE)

Las presentaciones se califican en base al error cuadrático medio (RMSE, por sus siglas en inglés). El RMSE se define de la siguiente manera:

RMSE = √(1/N ∑(y<sub>i</sub> - ŷ<sub>i</sub>)<sup>2</sup>)

donde ŷ<sub>i</sub> es el valor predicho y y<sub>i</sub> es el valor original para cada instancia i.





