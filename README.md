# Análisis y Procesamiento de Datos de Spotify con Inteligencia Artificial

Este repositorio contiene un conjunto de datos extenso de canciones de Spotify y un notebook de Jupyter en el que se implementan técnicas de análisis y procesamiento de datos utilizando herramientas de inteligencia artificial y aprendizaje automático.

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
3. **Análisis Exploratorio**:
   - Estadísticas descriptivas.
   - Visualización de distribuciones y correlaciones.
   - Identificación de tendencias y patrones.
4. **Modelado Predictivo**:
   - Implementación de modelos de aprendizaje automático para predecir la popularidad de una canción en base a sus características.
   - Evaluación de modelos mediante métricas como MAE, MSE y R^2.
5. **Conclusiones y Reflexiones**:
   - Principales hallazgos del análisis.
   - Posibles mejoras y futuras extensiones del trabajo.

## Uso del Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd tu_repositorio
   ```
3. Abre el notebook en Jupyter:
   ```bash
   jupyter notebook spotify_ia_refresh.ipynb
   ```

## Contribuciones

Las contribuciones son bienvenidas. Si tienes sugerencias o mejoras, puedes abrir un issue o enviar un pull request. Se recomienda seguir buenas prácticas de programación y documentación al contribuir.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para obtener más detalles.
