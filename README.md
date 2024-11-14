# Analisis-de-datos-y-modelacion-predictiva-de-e-commerce
Objetivos del proyecto:
1.   Predecir si un cliente devolverá un producto o no.

2.   Predicción de churn: Utilizando las características de cada cliente y sus patrones de compra, el objetivo es predecir la probabilidad de que un cliente se vuelva inactivo o deje de comprar en la plataforma. Esto se podría modelar como una tarea de clasificación binaria, donde el objetivo es la columna "Churn".

3. Segmentación de clientes: Usando clustering (no necesariamente un modelo de machine learning supervisado), podrías identificar segmentos de clientes en función de sus patrones de compra, categorías de productos, métodos de pago, etc. Luego, podrías utilizar un modelo de clasificación para predecir a qué segmento probablemente pertenezca un nuevo cliente.

4. Predicción de categoría de producto para futuras compras: Utilizando los datos históricos de compras, podrías intentar predecir la próxima categoría de producto que un cliente comprará. Esto podría ser útil para personalizar recomendaciones de productos.

5. Análisis de recurrencia de compras: Usando redes neuronales recurrentes, podrías modelar los patrones temporales de compra de los clientes para predecir cuándo realizarán su próxima compra. Esto implicaría hacer una serie temporal con la "Purchase Date" y otras variables relevantes, y ajustar el modelo para hacer predicciones a intervalos de tiempo.


Para el punto 2, trabajaremos con un dataset que tiene registros de compras de clientes de una e-commerce ficticia en la cuál, para poder realizar dichas compras, debes estar registrado con una especie de "membresia" y es por esto que, existe una columna en el dataset de entrenamiento que determina si el cliente abandonó el servicio o no.
