# Recomendador de Canciones en Spotify

Este repositorio contiene un sistema de recomendación de canciones basado en datos de Spotify. A partir de una canción seleccionada, el sistema sugiere cinco canciones similares utilizando técnicas de procesamiento de datos y modelos de recomendación.

## Contenido del Repositorio

1. **spotify_114k_tracks.csv**: Archivo CSV que contiene información detallada de 114,000 pistas de Spotify. Incluye metadatos como nombre de la canción, artista, popularidad, duración, clave tonal, modo, tempo, entre otras características técnicas y musicales.
2. **spotify_ia_refresh.ipynb**: Un notebook de Jupyter donde se realiza el procesamiento y análisis de los datos, con diversas técnicas de manipulación, limpieza, visualización y modelado predictivo.

## Requisitos y Configuración

Para ejecutar el notebook correctamente, se deben instalar las siguientes dependencias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Es recomendable utilizar un entorno virtual para evitar conflictos con otras bibliotecas:

```bash
python -m venv env
source env/bin/activate  # En macOS/Linux
env\Scripts\activate  # En Windows
pip install -r requirements.txt
```

## Descripción del Notebook

El notebook `spotify_ia_refresh.ipynb` está estructurado en varias secciones:

1. **Carga de Datos**: Se lee el archivo CSV y se inspecciona su contenido.
2. **Limpieza y Preprocesamiento**:
   - Eliminación de valores nulos o duplicados.
   - Normalización y escalado de variables.
   - Conversión de datos categóricos a numéricos.
3. **Sistema de Recomendación**:
   - Implementación de un algoritmo de similitud basado en distancia euclidiana o coseno.
   - A partir de una canción seleccionada, se calculan las canciones más cercanas según sus características musicales.
   - Generación de una lista de 5 canciones recomendadas.
4. **Modelado Predictivo**:
   - Implementación de modelos de aprendizaje automático para predecir la popularidad de una canción en base a sus características.
5. **Interfaz de Usuario en el Notebook:s**:
   - Se permite al usuario seleccionar una canción y obtener nuevas recomendaciones de forma iterativa.

## Uso del Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/rubenmuinho/spotify_ia.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd spotify_ia
   ```
3. Abre el notebook en Jupyter:
   ```bash
   jupyter notebook spotify_ia_refresh.ipynb
   ```

## Contribuciones

Las contribuciones son bienvenidas. Si tienes sugerencias o mejoras, puedes abrir un issue o enviar un pull request. Se recomienda seguir buenas prácticas de programación y documentación al contribuir.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para obtener más detalles.
