# Análisis Inicial y Selección de Problema

## Descripción
Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre varios conjuntos de datos relacionados con nutrición y salud. El proyecto busca identificar patrones, relaciones entre variables y problemas relevantes a resolver mediante el análisis de estos datos. El objetivo final es seleccionar un problema específico para abordarlo con un modelo predictivo.

## Conjuntos de Datos Analizados
En el análisis inicial, se han trabajado con  los siguientes datos:
1. **Nutrición**: Datos sobre la edad, peso, ingesta de calorías, proteínas, carbohidratos, grasas, entre otros.
2. **Actividad Física**: Información sobre los niveles de actividad física y su relación con otros factores de salud.
3. **Salud**: Información relacionada con la obesidad, factores socioeconómicos, hábitos alimenticios, etc.
4. **Información Demográfica**: Datos sobre la edad, género y otros factores demográficos de la población.

## Resumen del EDA Inicial
Durante el análisis exploratorio de los datos (EDA), se identificaron los siguientes hallazgos principales:
- **Distribuciones de Variables**: La edad tiene una distribución casi uniforme, mientras que las calorías consumidas muestran una ligera inclinación hacia consumos más altos.
- **Outliers**: Se detectaron valores atípicos en las variables `peso`, `proteína` y `calorías`, los cuales podrían ser errores de medición o datos excepcionales que requieren un tratamiento específico.
- **Correlaciones**: Existen correlaciones fuertes entre la ingesta de calorías y nutrientes (proteínas, carbohidratos, grasas) con la ingesta calórica diaria. Sin embargo, la edad y la altura tienen correlaciones débiles con otras variables.
- **Tasa de Obesidad**: Al analizar la relación entre peso y edad, se observan posibles indicios de obesidad, especialmente en personas con un peso superior al promedio para su edad.

## Problema Seleccionado
El problema seleccionado para este proyecto es **la predicción del nivel de calorías**. La justificación para elegir este problema se basa en la importancia crítica de la salud y el creciente problema de la obesidad en la población. Con este análisis, se busca identificar patrones de obesidad y realizar una predicción precisa para ayudar a desarrollar estrategias de intervención.

**Objetivos Específicos**:
1. Identificar las características clave que afectan la obesidad (calorias, edad, peso, dieta, actividad física).
2. Construir un modelo predictivo que pueda estimar la probabilidad de obesidad basado en estas características.
3. Proponer posibles intervenciones para reducir la obesidad basadas en los resultados del modelo.

## Instrucciones para Ejecutar
Para ejecutar este proyecto y reproducir los resultados, siga los pasos a continuación:
1. Clonar este repositorio:
    ```bash
    git clone https://github.com/tu_usuario/analisis_inicial.git
    ```
2. Navegar al directorio del proyecto:
    ```bash
    cd analisis_inicial
    ```
3. Instalar las dependencias necesarias:
    ```bash
    pip install -r requirements.txt
    ```
4. Ejecutar los notebooks de EDA:
    ```bash
    jupyter notebook
    ```

Los resultados y visualizaciones generadas en los notebooks permitirán reproducir el análisis realizado en este proyecto.

## Autor
- **Juan Manuel Gonzalez Benitez** - *Data Scientist* - Análisis Exploratorio de Datos (EDA) y selección de problema.
                                   - *Data Analyst* - Limpieza de datos y análisis de correlaciones.
                                   - *Researcher* - Modelado predictivo y validación.

## Licencia
Este proyecto está bajo la Licencia WAMA. Consulte el archivo LICENSE para más detalles.

