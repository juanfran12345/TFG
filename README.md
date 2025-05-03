# TFG: NeuralProphet para la predicción de series temporales

### Resumen

Las series temporales siempre han sido uno de los principales temas de estudio a la hora de realizar predicciones a futuro. Coloquialmente, se puede definir una serie temporal como una sucesión de datos en orden cronológico. Dada la masiva cantidad de información que se genera en la actualidad, se buscan constantemente nuevas formas de usarla.

En este trabajo, se han estudiado diferentes modelos de series temporales, desde un punto de visto teórica hasta una visión práctica de los mismos.

En primer lugar, se ha comenzado presentando las definiciones más básicas para contextualizar el trabajo y los procesos más clásicos de series temporales. En concreto, se han introducido  brevemento los modelos ARIMA para poder tratar los modelos SARIMA.

En segundo lugar, el trabajo se centra en un modelo predictivo reciente: el modelo Prophet. Se verá su eficiencia para modelar datos con fuertes relaciones estacionales y por qué, a día de hoy, sigue siendo uno de los primeros modelos a tener en cuenta cuando se pretende predecir una serie temporal.

A continuación, se tratan teóricamente las Redes Neuronales para introducir las Redes Neuronales Recurrentes, que son un tipo de redes neuronales diseñadas para procesar datos que siguen un orden secuencial. Así, se finaliza la sección con la explicación teórica y puesta en práctica del modelo LSTM, que son un tipo de redes neuronales recurrentes específico cuyo objetivo es suplir las limitaciones de las mismas. 

Posteriormente, se trata el último, que es una combinación del modelo Prophet y redes neuronales: NeuralProphet. Principalmente, este modelo utiliza la interpretabilidad y capacidad para captar estacionalidades del modelo Prophet y la flexibilidad para modelar relaciones no lineales de las redes neuronales.

Finalmente, se han comparado los distintos modelos con datos con y sin ruido para comprobar su precisión en las predicciones, resumiendo sus principales diferencias. El código desarrollado durante el trabajp se encuentra en el repositorio público de GitHub del autor, y es accesible para cualquier usuario.

**Palabras clave:** SARIMA, Prophet, Redes Neuronales, LSTM, NeuralProphet.

### Abstract

Time series have always been one of the main subjects of study when making future predictions. Colloquially, a time series can be defined as a sequence of data in chronological order. Given the massive amount of information generated today, new ways of using it are constantly being sought.

In this work, different models of time series have been studied, from a theoretical point of view to a practical view of them.

Firstly, it has begun by presenting the most basic definitions for classifying work and the more classical processes of time series. In particular, the ARIMA models have been introduced shortly to be able to treat the SARIMA models.

Secondly, the work focuses on a recent predictive model: the Prophet model. We will see its efficiency in modelling data with strong seasonal relationships and why, to this day, it remains one of the first models to be taken into account when trying to predict a time series.

Neural Networks are then theoretically treated to introduce the Recurrent Neural Networks, which are a type of neural networks designed to process data that follow a sequential order. Thus, the section ends with the theoretical explanation and implementation of the LSTM model, which are a specific type of recurrent neural networks whose objective is to overcome their limitations.

Subsequently, the latter is treated, which is a combination of the Prophet model and neural networks: NeuralProphet. Primarily, this model uses interpretability and capability to capture the seasonality of the Prophet model and flexibility to model nonlinear relationships in neural networks.

Finally, the different models have been compared with data with and without noise to check their accuracy in the predictions, summarizing their main differences. The code developed during the work is in the author’s public GitHub repository, and it is accessible to any user.

**Key words:** SARIMA, Prophet, Neural Networks, LSTM, NeuralProphet.