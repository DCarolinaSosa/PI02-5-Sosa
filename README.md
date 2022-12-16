Segundo proyecto individual

Machine Learning

Los pasos para realizar el proyecto fueron:

    -Carga de datos
    -Análisis de datos
    -Limpieza de datos
    -Relación entre los datos
    -Escalabilidad de los datos.
    -Creación del modelo.
    -Predicciones.

Para la carga de datos utilicé la librería pandas creando un dataframe con la información. Luego, para el análisis de los datos y limpieza de los mismos vi el tipo de dato que tenía cada columna, en su mayoría "object" lo que significó que más adelante debía cambiar este tipo de datos para que el modelo machine learning pueda entenderlos. A su vez, busqué datos nulos y filas duplicadas.

En la relación entre datos realicé gráficos entre las categorías y las clases 0 y 1 que representaban estadías cortas con 0 y estadías largas con 1. También la relación entre las clases y las variables numéricas "Available Extra Rooms in Hospital", "staff_available" y "Admission_Deposit". Luego, use LabelEncoder para hacer numéricos las variables categóricas y estandaricé.

Luego de esto, creé el modelo de regresión logística y lo entrené. Por último, obtuve el archivo csv pedido con las predicciones.
