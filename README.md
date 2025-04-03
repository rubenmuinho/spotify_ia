# Recomendador de Canciones en Spotify

Este repositorio contiene un sistema de recomendación de canciones basado en datos de Spotify. 
Utiliza técnicas de procesamiento de datos y algoritmos de aprendizaje automático para analizar 
las características musicales de cada pista y sugerir canciones similares a una dada.

## Descripción del Proyecto

El objetivo de este proyecto es desarrollar un sistema de recomendación de música que, a partir 
de una canción de entrada, sugiere cinco canciones similares. Para ello, se emplean técnicas de 
análisis de datos y modelos de aprendizaje automático, basados en la similitud de características 
musicales como tempo, tonalidad, popularidad, entre otras.

### ¿Cómo funciona?
1. **Carga de Datos**: Se extraen y analizan las características de más de 114,000 canciones disponibles en un archivo CSV.
2. **Procesamiento y Limpieza**: Se realizan tareas de normalización, escalado y conversión de datos categóricos para su correcta manipulación.
3. **Algoritmo de Recomendación**:
   - Se implementa un sistema basado en distancia euclidiana o coseno para calcular la similitud entre canciones.
   - A partir de una canción seleccionada, el modelo encuentra las más cercanas en términos de características musicales.
4. **Modelado Predictivo**: Se prueban modelos de machine learning para predecir la popularidad de una canción en base a sus atributos.
5. **Interfaz en Jupyter Notebook**: Permite al usuario seleccionar una canción y obtener recomendaciones de manera interactiva.

## Contenido del Repositorio

- **spotify_114k_tracks.csv**: Base de datos con información de 114,000 canciones, incluyendo artista, duración, popularidad y características musicales.
- **spotify_ia_refresh.ipynb**: Notebook de Jupyter con todo el flujo de trabajo, desde la carga de datos hasta la implementación del recomendador.

## Requisitos y Configuración

Para ejecutar el notebook correctamente, instala las siguientes dependencias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Se recomienda utilizar un entorno virtual:

```bash
python -m venv env
source env/bin/activate  # macOS/Linux
env\Scripts\activate  # Windows
pip install -r requirements.txt
```

## Uso del Proyecto

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/rubenmuinho/spotify_ia.git
   ```
2. Acceder al directorio del proyecto:
   ```bash
   cd spotify_ia
   ```
3. Ejecutar el notebook en Jupyter:
   ```bash
   jupyter notebook spotify_ia_refresh.ipynb
   ```

## Contribuciones

Las contribuciones son bienvenidas. Puedes abrir un issue o hacer un pull request con mejoras en el código, documentación o implementación de nuevos algoritmos.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
