# Título del Proyecto
FRAMEWORK PARA LA DETECCIÓN, SEGMENTACIÓN Y CLASIFICACIÓN DE IMÁGENES DIGITALES DE HERIDAS CRÓNICAS, EN PACIENTES CON PIE DIABETICO.


## Descripción

Este proyecto se centra en el desarrollo y evaluación de modelos de segmentación y clasificación de imágenes de heridas utilizando arquitecturas de redes neuronales profundas como UNet y algoritmos de clustering no supervisados como K-Means y clustering jerárquico. El objetivo es mejorar la precisión y la eficacia en la identificación y clasificación de diferentes tipos de heridas.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Tabla de Contenidos](#tabla-de-contenidos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Resultados](#resultados)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Autores](#autores)
- [Licencia](#licencia)

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/usuario/repositorio.git
    ```
2. Navega al directorio del proyecto:
    ```sh
    cd repositorio
    ```
3. Crea un entorno virtual:
    ```sh
    python -m venv env
    ```
4. Activa el entorno virtual:
    - En Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - En macOS/Linux:
        ```sh
        source env/bin/activate
        ```
5. Instala las dependencias:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Preprocesa los datos:
    ```sh
    python preprocess_data.py
    ```
2. Entrena el modelo de segmentación UNet:
    ```sh
    python train_unet.py
    ```
3. Aplica los algoritmos de clustering:
    ```sh
    python clustering.py
    ```
4. Realiza la evaluación y visualiza los resultados:
    ```sh
    python evaluate.py
    ```

## Resultados

Los resultados obtenidos muestran la efectividad de la arquitectura UNet para la segmentación de imágenes de heridas, así como la capacidad del algoritmo K-Means para agrupar imágenes con características visuales distintivas. Además, se ha comprobado la utilidad de aplicar PCA para mejorar la separación de clusters en el análisis jerárquico.

### Ejemplos de Resultados

- **Dendrograma con Datos Originales:**
  ![Dendrograma con Datos Originales](figures/dendrogram_original.png)

- **Dendrograma con Datos de PCA:**
  ![Dendrograma con Datos de PCA](figures/dendrogram_pca.png)

- **Comparación de Imágenes en Clusters:**
  ![Comparación de Imágenes](figures/comp1kmeans.png)
  ![Comparación de Imágenes](figures/comp2kmeans.png)

## Tecnologías Utilizadas

- Python
- Keras / TensorFlow
- scikit-learn
- pandas
- matplotlib

## Autores

- Dessarrollado por Cristobal Arenas Olivares en conjunto al profesor guia Julio Sotelo

