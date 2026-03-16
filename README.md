# House-Price-Prediction-Model

Descripcion: Desarrolle un modelo predictivo del precio de viviendas, puede ser usado como base el servicio de asesoria de ventas de vivienda. Las metricas de evaluacion que se utilizo para ver que tan bueno era el modelo fue R2 y RMSE.

Tecnoligia y librerias utilizadas: Utilice Python y las librerias pandas, sklearn, matplotlib, numpy y seaborn. Ademas utilice el modelo XGBoost y el modelo LightGBM

Responsabilidad clave: Ademas de la limpieza de datos, se realizo una EDA (analisis exploratorio de datos), se crearon dos modelos (XGBoost y LightGBM), se comparararon y se tomo el mejor (LightGBM).

Impacto logrado: R² (0.7629) y RMSE ($200,961). Puede que los valores no sean los esperados pero con una base de datos tan limitada (4600 datos) con valores en columnas con 0 y outliers y a pesar de realizar procesos de limpieza de datos los valores de las metricas fueron los que mejor se pudieron obtener.
