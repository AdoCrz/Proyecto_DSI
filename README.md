# Proyecto_DSI_CruzRazoAdolfo

## ABSTRACT

### Resúmen

Este proyecto se centra en analizar la prevalencia y las causas de la diabetes en Estados Unidos, utilizando un conjunto de datos basado en la encuesta BRFSS 2015 del CDC, disponible en Kaggle. La diabetes, una enfermedad crónica que impacta significativamente la salud pública y la economía, afecta a millones de personas en el país. En la primera fase, se busca analizar y visualizar hallazgos clave en los datos de más de 70,000 participantes, lo que permitirá en fases posteriores desarrollar modelos predictivos para mejorar el diagnóstico y tratamiento de la diabetes.

Dataset:
    Teboul, A. (2019). Diabetes Health Indicators Dataset. Kaggle. https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset



### Hipótesis de interés:
#### Basándonos en un análisis previo del conjunto de datos, planteamos las siguientes hipótesis:
- La prevalencia de diabetes varía según el nivel educativo.
- Factores como la obesidad y la hipertensión aumentan el riesgo de diabetes.
- La actividad física y la dieta influyen en el desarrollo de diabetes.
- El consumo del alcohol y tabaco influyen en el padecimiento de la diabetes.
- La edad y el género influyen en el padecimiento de la diabetes.

### Objetivos:
- Probar las hipótesis mediante análisis estadísticos y visualizaciones.
- Identificar hallazgos importantes en los datos mediante visualizaciones.
- Mostrar la información de forma fácil y sencilla de comprender para la población  .

### Impacto:
#### Los resultados permitirán:
- Comprender mejor los factores que influyen en el riesgo de diabetes.
- Mejorar las estrategias de prevención y políticas de salud pública para la diabetes.



### Descripción de las variables:

| **Nombre**               | **Descripción**                                                                                                                                          |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Diabetes_binary**       | 0 = no diabetes<br>1 = prediabetes<br>2 = diabetes                                                                                                      |
| **HighBP**                | 0 = no hipertensión<br>1 = hipertensión                                                                                                                 |
| **HighChol**              | 0 = no colesterol alto<br>1 = colesterol alto                                                                                                           |
| **CholCheck**             | 0 = no se ha realizado un chequeo de colesterol en 5 años<br>1 = sí se ha realizado un chequeo de colesterol en 5 años                                  |
| **BMI**                   | Índice de Masa Corporal (IMC)                                                                                                                            |
| **Smoker**                | ¿Has fumado al menos 100 cigarrillos en toda tu vida? [Nota: 5 cajetillas = 100 cigarrillos]<br>0 = no<br>1 = sí                                        |
| **Stroke**                | ¿Alguna vez te han dicho que tuviste un derrame cerebral?<br>0 = no<br>1 = sí                                                                            |
| **HeartDiseaseorAttack**  | Enfermedad coronaria (CHD) o infarto de miocardio (IM)<br>0 = no<br>1 = sí                                                                              |
| **PhysActivity**          | Actividad física en los últimos 30 días - excluyendo el trabajo<br>0 = no<br>1 = sí                                                                      |
| **Fruits**                | Consumes fruta 1 o más veces al día<br>0 = no<br>1 = sí                                                                                                  |
| **Veggies**               | Consumes vegetales 1 o más veces al día<br>0 = no<br>1 = sí                                                                                              |
| **HvyAlcoholConsump**     | (Hombres adultos >=14 bebidas por semana y mujeres adultas >=7 bebidas por semana)<br>0 = no<br>1 = sí                                                  |
| **AnyHealthcare**         | ¿Tienes algún tipo de cobertura de salud, incluyendo seguro médico, planes prepagos como HMO, etc.?<br>0 = no<br>1 = sí                                |
| **NoDocbcCost**           | ¿Hubo un momento en los últimos 12 meses en que necesitabas ver a un médico pero no pudiste por el costo?<br>0 = no<br>1 = sí                           |
| **GenHlth**               | ¿Cómo dirías que es tu salud en general?<br>Escala 1-5<br>1 = excelente<br>2 = muy buena<br>3 = buena<br>4 = regular<br>5 = mala                       |
| **MentHlth**              | Días de mala salud mental<br>Escala de 1 a 30 días                                                                                                       |
| **PhysHlth**              | Días de enfermedad física o lesión en los últimos 30 días<br>Escala de 1 a 30                                                                            |
| **DiffWalk**              | ¿Tienes serias dificultades para caminar o subir escaleras?<br>0 = no<br>1 = sí                                                                         |
| **Sex**                   | 0 = femenino<br>1 = masculino                                                                                                                            |
| **Age**                   | Categoría de edad en 13 niveles<br>1 = 18-24 años<br>2 = 25-29 años<br>3 = 30-34 años<br>4 = 35-39 años<br>5 = 40-44 años<br>6 = 45-49 años<br>7 = 50-54 años<br>8 = 55-59 años<br>9 = 60-64 años<br>10 = 65-69 años<br>11 = 70-74 años<br>12 = 75-79 años<br>13 = 80 o más años |                                                        |
| **Education**             | Nivel de educación<br>Escala de 1 a 6<br>1: No se graduó de la escuela secundaria<br>2: Graduado de la escuela secundaria<br>3: Asistió a la universidad<br>4: Graduado universitario<br>5: Estudios de posgrado<br>6: Doctorado o equivalente |
| **Income**                | Escala de ingresos<br>Escala de 1 a 8<br>1: <$10 K<br>2: $10–$15 K<br>3: $15–$20 K<br>4: $20–$25 K<br>5: $25–$35 K<br>6: $35–$50 K<br>7: $50–$75 K<br>8: >$75 K |


### Archivos del Proyecto

- **Df_diabetes.csv**: Este archivo contiene el conjunto de datos utilizado en el análisis, que incluye más de 70,000 respuestas sobre indicadores de salud y prevalencia de diabetes.

- **Notebook del Proyecto**: 


