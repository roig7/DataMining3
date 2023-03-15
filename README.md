# DataMining3

## Práctica 1: Decision Support System para enfermedades cardiacas
Las enfermedades relacionadas con el corazón son unas de las que mas afectan a la población a día de hoy. Lo curioso de dichas enfermedades es que un pronto diagnóstico y la adopción de una dieta saludable junto con una rutina de actividad física hacen que dichos problemas remitan. Un hospital quiere crear un Decision Support System para la planta de cardiología de manera que se puedan clasificar una serie de pacientes en torno a los resultados de una prueba médica. Es por ello qué se quiere construir un clasificador que proporcione dicha información.
Para ello usaremos el dataset “corazon.csv” que se encuentra en Moodle. Elige el clasificador que más se adapte de entre los vistos en clase y usa scikit-learn junto con las librerías que necesites para resolver las siguientes cuestiones. Muestra todos los resultados del algoritmo paso a paso.
1) Crea un clasificador en el que uses al menos dos criterios de división distintos. Calcula el error en cada uno de ellos y elige el qué mejor clasifique. (1 punto)
2) Dibuja el modelo elegido en el punto anterior. (0,5 puntos)
3) Selecciona tres reglas que sean las que generalicen lo menos posible y otras tres que especialicen
los menos posible. Interprétalas. (0,5 puntos)
4) Usa tu clasificador para clasificar a 5 pacientes que no se hayan usado en los pasos anteriores.
Dichos pacientes deberán presentar diferentes resultados en sus pruebas médicas. (1 punto)


## Práctica 2 : Decision Support System para cáncer de mama
En el mismo hospital del apartado anterior se quiere agilizar los métodos de screening en cáncer de mama para ser óptimo a la hora de diagnosticar y asignar los distintos tratamientos para los pacientes que reciben. Para ello han decidido crear un clasificador basado en las diferentes características de las pacientes y la necesidad de recibir un tratamiento de radioterapia o no.
Para ello usaremos el dataset “cancer_mama.csv” que se encuentra en Moodle. Elige el clasificador que más se adapte de entre los vistos en clase y usa scikit-learn junto con las librerías que necesites para resolver las siguientes cuestiones. Muestra todos los resultados del algoritmo paso a paso.
1) Realiza todo el preprocesamiento necesario para poder entrenar el clasificador y muestra las distintas tablas de distribución. (1 punto)
2) Crea un clasificador e indica su error. Úsalo para saber a qué clase corresponden al menos 5 pacientes que no hayas usado para entrenar el modelo. (1 punto)

## Práctica 4 : Predicción demanda de habitaciones
Una cadena de hoteles se está preparando para el cambio que el impacto del COVID-19 tendrá en su negocio. Para ello quiere crear un modelo que permita saber que tipo de habitación será mas demandada. Para ello, tendremos en cuenta el lugar que ocupan en un espacio n-dimensional donde n es el número de características de cada reserva de hotel que se ha hecho anteriormente.
Para ello usaremos el dataset “reservas.csv” que se encuentra en Moodle. Elige el clasificador que más se adapte de entre los vistos en clase y usa scikit-learn junto con las librerías que necesites para resolver las siguientes cuestiones. Muestra todos los resultados del algoritmo paso a paso.
1. Haz todo el preprocesamiento para crear un set de entrenamiento y otro de validación qué permita clasificar habitaciones qué tengan sólo las características necesarias. Usaremos como atributos todos los tipos numéricos, en caso de que sean categóricos se recomienda transformarlos Explica qué has hecho y porqué.
2. Prueba con distintas configuraciones de las dos métricas principales. La primera métrica corresponde al número de individuos que usarás para clasificar una nueva instancia y la segunda cómo vas a medir la cercanía de esa nueva instancia con el resto. ¿Qué decisiones has tomado? ¿Por qué? 
3. Elige la mejor configuración entre las anteriores. Para ello dibuja una tabla ver cómo evoluciona la clasificación. Dibuja los resultados que se obtienen con ambas configuraciones elegidas cómo las mejores. (1 punto)
4. Utiliza el clasificador para saber que ocurre con los asteroides de un dataset que se llame “habitaciones_clasificar.csv” que obtendremos del dataset proporcionado. 
