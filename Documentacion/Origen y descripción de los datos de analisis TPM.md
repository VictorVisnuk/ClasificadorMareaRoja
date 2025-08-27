## Origen y descripción de los datos de analisis de toxina paralizante en Moluscos TPM()
**Son datos provenientes del Laboratorio de Toxinas y Microbiología de la ciudad de Ushuaia entre los años 2021 al 2024**
**Los mismos fueron preprocesados de dos fuentes, la primera contenia una tabla con el resultado de concentracion de toxina para cada analisis, la segunda con diferentes tablas de analisis con resultado categorico (no detectable, apto no apto) que fueron preprocesados para obtener este set de datos final**

#### Diccionario de datos
| Variable | Descripción | Tipo de Dato |
| ------------ | ------------ | ------------ |
| Fecha | Fecha en la que se realizó el análisis en formato dd/mm/yyyy. | Fecha (datetime). |
| Resultado_cat | Resultado del examen nivel de toxina paralizante. 0 : no detectado, 1: apto para consumo (menor a 800µg STX eq. kg)*, 2: no apto (mayor a 800) | Entero (categorico). |


