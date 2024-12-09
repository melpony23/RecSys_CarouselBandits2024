# **RecSys_CarouselBandits2024**

## **Descripción del Proyecto**
Este proyecto utiliza el código y los recursos provenientes del repositorio [Carousel Bandits de Deezer](https://github.com/deezer/carousel_bandits), que replica los experimentos presentados en el artículo *"Carousel Personalization in Music Streaming Apps with Contextual Bandits"* publicado en RecSys 2020. Como parte del proyecto final del curso de **Sistemas Recomendadores** de la **Pontificia Universidad Católica de Chile**, se exploran las técnicas y resultados propuestos en esta investigación. 

Además, se introduce una nueva política llamada **Most Popular** y se evalúan métricas adicionales, como **nDCG**, **Novelty**, **Diversity** y **MRR**.

El proyecto también amplía los experimentos replicándolos con un dataset distinto, proveniente del artículo *"A Semi-Personalized System for User Cold Start Recommendation on Music Streaming Apps"*. Este enfoque permite evaluar la eficacia del método presentado en el artículo original de RecSys 2020 cuando se aplica a otro contexto.

---

## **Estructura del Código**
El proyecto contiene dos notebooks principales que permiten realizar los experimentos y análisis:

1. **`ProyectoFinal_SysRec_AnalisisYBaselines.ipynb`**:
   - Replica los experimentos originales descritos en *Carousel Personalization in Music Streaming Apps with Contextual Bandits*.
   - Requiere los datasets `playlist_features.csv` y `user_features_small.csv`, que contienen un pequeño registro de 9 usuarios anonimizados de la plataforma Deezer.
   - Cada celda debe ejecutarse en orden después de cargar los datos necesarios.

2. **`proyecto_sysrec_sample_y_playlist_de_cluster.ipynb`**:
   - Permite replicar el experimento utilizando el dataset del artículo *A Semi-Personalized System for User Cold Start Recommendation on Music Streaming Apps*.
   - Requiere importar los archivos con extensión `.parquet` provistos en el dataset.
   - Al igual que el primer notebook, basta con cargar los datos y ejecutar las celdas en orden para obtener los resultados.

Ambos notebooks están diseñados para facilitar la ejecución, y el flujo de trabajo está claramente especificado en los comentarios del código.

---

## **Dataset Utilizados**
1. **Deezer Dataset (RecSys 2020)**:
   - Contiene datos anonimizados de 9 usuarios y múltiples playlists.
   - Útil para replicar los experimentos del artículo original.

2. **Cold Start Dataset (KDD 2021)**:
   - Proporciona datos más amplios para analizar escenarios de "cold start" en aplicaciones de streaming musical.
   - Se incluye en formato `.parquet` y es compatible con el segundo notebook.
     Se pueden encontrar en el siguiente link: https://zenodo.org/records/5121674#.YQuiitMzaIZ
   - Se usan: song_embeddings.parquet, user_embeddings.parquet, user_features_train_svd.parquet.

---

## **Referencias**
1. **Papers**:
   - Bendada, Walid, Salha, Guillaume, & Bontempelli, Theo. (2020). *Carousel Personalization in Music Streaming Apps with Contextual Bandits.* 14th ACM Conference on Recommender Systems (RecSys 2020).
   - Léa Briand, Guillaume Salha-Galvan, Walid Bendada, Mathieu Morlon, & Viet-Anh Tran. (2021). *A Semi-Personalized System for User Cold Start Recommendation on Music Streaming Apps* [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.5121674](https://doi.org/10.5281/zenodo.5121674).

2. **Recursos Adicionales**:
   - [JavatPoint: Recommendation Systems](https://www.javatpoint.com/recommendation-system-machine-learning).

---

## **Integrantes del Proyecto**
- Lucas Aguilera 
- Melanie Castillo
- Anaís Montanares


---
