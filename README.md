# TFG: NeuralProphet para la predicción de series temporales

### Resumen

Las series temporales siempre han sido uno de los principales temas de estudio a la hora de realizar predicciones a futuro. Coloquialmente, se puede definir una serie temporal como una sucesión de datos en orden cronológico. Dada la masiva cantidad de información que se genera en la actualidad, se buscan constantemente nuevas formas de usarla.

En este trabajo, se han estudiado diferentes modelos de series temporales, desde un punto de vista teórico hasta una visión práctica de los mismos.

En primer lugar, se comienza presentando las definiciones introductorias para contextualizar el trabajo y los procesos clásicos de series temporales. En concreto, se han introducido  los modelos ARIMA para poder tratar los modelos SARIMA.

En segundo lugar, el trabajo se centra en un modelo predictivo reciente: el modelo Prophet. Se verá su eficiencia para modelar datos con fuertes relaciones estacionales y el porqué, a día de hoy, sigue siendo uno de los primeros modelos a tener en cuenta cuando se pretende predecir una serie temporal.

A continuación, se tratan teóricamente las Redes Neuronales para introducir las Redes Neuronales Recurrentes, que son un tipo de redes neuronales diseñadas para procesar datos que siguen un orden secuencial. Así, se finaliza la sección con la explicación teórica y puesta en práctica del modelo LSTM, que son un tipo de redes neuronales recurrentes específico cuyo objetivo es suplir las limitaciones de las mismas. 

Posteriormente, se aborda NeuralProphet, un modelo de reciente creación que combina el modelo Prophet y redes neuronales. Principalmente, este modelo se beneficia de la interpretabilidad y capacidad para captar estacionalidades del modelo Prophet y de la flexibilidad para modelar relaciones no lineales de las redes neuronales.

Finalmente, se han comparado los distintos modelos con datos con y sin ruido para comprobar su precisión en las predicciones, resumiendo sus principales diferencias. Se ha desarrollado un proyecto en Python para comprobar la eficacia de los modelos y estudiar su implementación en Python con datos relacionados con el tráfico aéreo en EE.UU., cuyo código puede consutarse en el repositorio público de GitHub del autor.

**Palabras clave:** SARIMA, Prophet, Redes Neuronales, LSTM, NeuralProphet.

### Abstract

Time series have always been one of the main fields studied when it comes to forecasting the future. Colloquially, time series can be defined as a sequence of data in chronological order. Due to the massive amount of data being generated everyday, there are constant efforts being made to find new ways to use it.

In this project, different models of time series have been studied from both a theoretic and practical point of view. 

Firstly, basic definitions have been given in order to contextualize the project and the most elemental processes regarding time series. Specifically, ARIMA models have been briefly introduced in order to work with SARIMA models. 

Secondly, this project focuses on a recent predictive model known as Prophet. The aim is to show its efficiency in modelling data with strong seasonal relationships and illustrate the reason why it continues to be at the forefront when it comes to the prediction of time series. 

Moreover, a theoretic framework about Neural Networks is presented in order to introduce Recurrent Neural Networks, which are types of neural networks designed to process data indexed in chronological order. Finally, this section introduces a theoretic explanation and practical demonstration of the LSTM model, which is a specific type of recurrent neural network whose aim is to make up for the limitations of said recurrent neural networks. 

Subsequently, one last model, which is a combination of the Prophet model and neural networks named NeuralProphet, is discussed. This model mainly works with the ability to interpret and capture seasonality present in the Prophet model and the flexibility to model non-linear relationships present in neural networks. 

Finally, a comparison between the different models including data with and without noise is made in order to check their precision accuracy, summarising their main differences. A Python project has been developed to test the effectiveness of the models and study their implementation in Python with data related to air traffic in the USA, whose code can be found in the author’s public GitHub repository.

**Key words:** SARIMA, Prophet, Neural Networks, LSTM, NeuralProphet.