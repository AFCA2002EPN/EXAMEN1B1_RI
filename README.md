# ICCD753 Recuperación de Información - Examen 1

## Descripción
Este proyecto implementa técnicas de recuperación de información utilizando embeddings de documentos y análisis de similitud en reseñas de películas de Rotten Tomatoes.

## Archivos del Proyecto
- `CorreaAdrian_ex1bim_ir26a.ipynb` - Notebook principal con todo el código
- `rotten_tomatoes_critic_reviews.csv` - Dataset de reseñas de críticos
- `embeddings.npy` - Embeddings pre-calculados (generados al ejecutar el notebook)
- `requirements.txt` - Dependencias de Python

## Requisitos Previos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)

## Instrucciones para Ejecutar

### 1. Instalar Dependencias
```bash
pip install -r requirements.txt
```

### 2. Colocar los Datos
Asegúrese de que `rotten_tomatoes_critic_reviews.csv` esté en la misma carpeta que el notebook.

### 3. Ejecutar el Notebook
Abra `CorreaAdrian_ex1bim_ir26a.ipynb` y ejecute todas las celdas en orden:
- **Jupyter Notebook**: `jupyter notebook CorreaAdrian_ex1bim_ir26a.ipynb`
- **VS Code**: Abra el archivo y haga clic en "Run All"
- **JupyterLab**: `jupyter lab CorreaAdrian_ex1bim_ir26a.ipynb`

## Notas Importantes
- ⏱️ La generación de embeddings puede tardar varios minutos dependiendo del tamaño del corpus
- 💾 Los embeddings se guardan automáticamente en `embeddings.npy` para futuras ejecuciones
- 📊 El notebook incluye visualización PCA y comparación entre modelos