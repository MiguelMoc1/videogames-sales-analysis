# Análisis de Ventas de Videojuegos: Identificación de Patrones de Éxito

## Introducción
Este proyecto analiza datos de ventas, calificaciones de usuarios y críticos, plataformas, géneros y clasificaciones ESRB para identificar patrones que determinen el éxito de los videojuegos. El análisis está diseñado para respaldar decisiones estratégicas y de marketing en la industria de los videojuegos, permitiendo priorizar géneros, plataformas y estrategias según las preferencias regionales.

## Objetivos del Proyecto
1. **Identificar patrones de éxito**: Analizar ventas, calificaciones y tendencias de género para identificar características de los videojuegos más exitosos.
2. **Optimización regional**: Comprender las diferencias en preferencias por región (NA, EU, JP).
3. **Soporte estratégico**: Proveer insights para campañas publicitarias y decisiones de lanzamiento de productos.

## Estructura del Proyecto
1. **Preparación de los Datos**:
   - Carga y limpieza de datos.
   - Conversión de tipos de datos.
   - Tratamiento de valores ausentes en columnas clave (`critic_score`, `rating`, etc.).
   - Cálculo de métricas como `total_sales`.

2. **Análisis Exploratorio**:
   - Ventas totales por género y plataforma.
   - Ciclo de vida de las plataformas.
   - Distribución de ventas por región (NA, EU, JP).
   - Relación entre las calificaciones de usuarios/críticos y las ventas.

3. **Pruebas de Hipótesis**:
   - Comparación de calificaciones entre plataformas (`Xbox One` vs. `PC`).
   - Análisis de diferencias entre géneros (`Acción` vs. `Deportes`).

4. **Visualización de Datos**:
   - Gráficos de barras, diagramas de caja y gráficos de dispersión para representar hallazgos clave.
   - Identificación de tendencias en ventas y preferencias.

## Herramientas y Lenguajes Utilizados
- **Lenguajes**:
  - Python: Análisis y procesamiento de datos.
  - SQL: Recopilación y manipulación de datos desde bases de datos.
- **Bibliotecas**:
  - `pandas`: Limpieza y análisis de datos.
  - `matplotlib`: Visualización de datos.
  - `scipy`: Pruebas estadísticas.
  - `numpy`: Cálculos numéricos.

## Conclusiones Clave
- **Géneros más populares**: Acción y Deportes son los géneros más rentables globalmente.
- **Plataformas líderes**:
  - NA: Xbox 360 y PS2 dominan.
  - EU: PS2 y PS3 son las más populares.
  - JP: DS y PS lideran.
- **Clasificación ESRB**:
  - Clasificación "E" (Everyone) tiene la mayor cantidad de ventas en NA y EU.
  - JP muestra una alta proporción de ventas en juegos con clasificación "Unknown".
- **Tendencias de ventas**:
  - Picos en ventas globales alrededor de 2008-2010, seguidos de una caída constante.

## Recomendaciones
1. **Foco en géneros populares**: Priorizar el desarrollo de juegos de Acción y Deportes.
2. **Estrategias regionales**: Adaptar lanzamientos y marketing a las preferencias locales.
3. **Optimizar clasificaciones**: Incrementar la cantidad de juegos clasificados como "E" para maximizar el mercado objetivo.
4. **Críticas como métrica clave**: Mejorar la relación con críticos para potenciar la percepción del producto.

## Cómo Ejecutar el Proyecto
1. **Instalar dependencias**:
   - Usa el archivo `requirements.txt` para instalar las dependencias:
     ```bash
     pip install -r requirements.txt
     ```
2. **Cargar el conjunto de datos**:
   - Asegúrate de que los archivos de datos (`games.csv`) estén en la ubicación especificada.
3. **Ejecutar el análisis**:
   - Corre el notebook Jupyter para explorar los datos y gráficos interactivos.

## Estructura de Archivos
```plaintext
📁 Proyecto
├── README.md
├── requirements.txt
├── notebooks/
│   └── analisis_ventas_videojuegos.ipynb
├── datasets/
│   └── games.csv
