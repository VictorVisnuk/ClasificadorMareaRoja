
# APLICACIÓN HERRAMIENTAS DE INTELIGENCIA ARTIFICIAL EN EL FENOMENO MAREA ROJA EN EL CANAL BEAGLE




## Autor

- Universidad Tecnológica Nacional – Facultad Regional Tierra del Fuego
victorvisnuk@gmail.com


# Resumen
La marea roja, provocada por floraciones algales nocivas, representa una amenaza significativa para la salud pública y la actividad pesquera en el Canal Beagle. Este trabajo presenta un avance en la aplicación de inteligencia artificial para la detección temprana de eventos tóxicos en el Canal Beagle puntalmente en la zona Puerto Almanza. Los objetivos específicos fueron:
- Construir un conjunto de datos amplio y representativo
- Diseñar y entrenar modelos de clasificación que alcancen una precisión mínima del 75% para detectar eventos de marea roja 
- Evaluar su aplicabilidad como herramienta de apoyo a la toma de decisiones.

El dataset (2021–2024) incluye variables meteorológicas y concentraciones de toxina paralizante en moluscos (TPM), provistas por el Laboratorio de Toxinas Marinas y Microbiología de Ushuaia. Se entrenaron clasificadores (SVM, Random Forest, XGBoost) con Python y bibliotecas como pandas y scikit-learn, utilizando validación cruzada y ajuste de hiperparámetros.El enfoque más efectivo fue el modelo jerárquico en dos etapas: detección binaria de presencia/ausencia de toxina, seguido de clasificación de su peligrosidad. Random Forest logró el mejor resultado en la primera etapa: F1-score Macro de 0,874 y SVM en la segunda etapa: F1-score Macro de 0,947, el clasificador jerárquico obtuvo un F1 Score Macro de 0,87 sobre un conjunto de datos reservado para validacion.

Limitaciones: desbalance de clases, falta de datos oceanográficos en algunos períodos, e imposibilidad de sectorizar por zonas de muestreo.
Conclusión: Los modelos desarrollados superaron los objetivos propuestos y demuestran potencial como herramienta complementaria para la gestión de alertas tempranas. Actualmente no existen sistemas automatizados de predicción en la región, siendo el único mecanismo de detección el análisis de toxina en el laboratorio. Su implementación permitiría un monitoreo diario automatizado, sin los costos ni la logística asociada a los análisis presenciales, lo que agilizaría considerablemente la respuesta ante eventos tóxicos y permitiría optimizar el uso de los recursos disponibles, especialmente en contextos de baja probabilidad de ocurrencia.

## Keywords
Palabras Claves: marea roja, Inteligencia Artificial, aprendizaje automático, aprendizaje profundo, Python, Toxina Paralizante en Moluscos.
Eje Temático: Ciencia de Datos aplicada a la pesca y el ambiente marino.
