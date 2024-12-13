# Proyecto de Análisis Competitivo en el Sector SaaS

Este proyecto implementa un análisis completo de datos de marketing para empresas SaaS, incluyendo preparación de datos, análisis estadístico y visualizaciones en múltiples plataformas.

## Estructura del Proyecto

```
proyecto_saas_analytics/
├── data/
│   ├── raw/                      # Datos originales
│   └── processed/                # Datos procesados
├── scripts/
│   ├── python/                   # Scripts de Python
│   │   ├── data_preparation.py
│   │   └── analysis.py
│   └── R/                        # Scripts de R
│       ├── statistical_analysis.R
│       └── visualizations.R
├── tableau/
│   ├── workbook.twb             # Archivo de Tableau
│   └── dashboards/              # Exportaciones de dashboards
├── outputs/
│   └── visualizations/          # Gráficos exportados
└── README.md                    # Documentación del proyecto
```

## Contenido de las Carpetas

### Data
- **raw/**: Contiene el dataset original `enhanced_saas_marketing_data.csv` con información de 4 empresas SaaS
- **processed/**: Almacena los datos después del preprocesamiento, con correcciones en separadores decimales y tipos de variables

### Scripts
#### Python
- **data_preparation.py**: Implementa:
  - Limpieza de datos
  - Manejo de valores faltantes
  - Creación de métricas derivadas (gross margin, marketing efficiency, CLV/CAC ratio)
  - Agregación de métricas temporales
  
- **analysis.py**: Realiza:
  - Análisis exploratorio de datos
  - Visualizaciones básicas
  - Cálculo de correlaciones
  - Análisis estadístico inicial

#### R
- **statistical_analysis.R**: Ejecuta:
  - Análisis estadístico detallado
  - Tests de normalidad
  - Análisis de correlaciones
  - Cálculos de métricas clave
  
- **visualizations.R**: Genera:
  - Gráficos de tendencias temporales
  - Análisis de distribuciones
  - Matrices de correlación
  - Visualizaciones avanzadas

### Tableau
- **workbook.twb**: Contiene el análisis visual principal con:
  - Campos calculados básicos
  - Métricas financieras y de usuario
  - Visualizaciones interactivas

### Outputs
- **visualizations/**: Contiene las exportaciones de visualizaciones generadas por los scripts de Python y R

## Métricas Analizadas

### Métricas de Tráfico
- Visitas orgánicas
- Visitas directas
- Visitas por referidos
- Visitas de campañas pagadas

### Métricas Financieras
- Ingresos mensuales
- Costos operativos
- Inversión en marketing
- CAC (Customer Acquisition Cost)
- CLV (Customer Lifetime Value)

### Métricas de Usuario
- Usuarios activos mensuales
- Tasa de cancelación
- Puntuación de satisfacción
- Net Promoter Score

## Herramientas Utilizadas
- Python (pandas, numpy, seaborn, matplotlib, plotly)
- R (tidyverse, plotly, scales, lubridate, corrplot)
- Tableau Desktop

## Preparación de Datos
Se realizó un trabajo específico de preparación de datos para Tableau, incluyendo:
- Corrección de separadores decimales
- Ajuste de tipos de variables (conversión de texto a numérico)
- Validación de formatos de fecha
- Limpieza de datos inconsistentes

## Resultados
El análisis proporciona insights sobre:
- Rendimiento competitivo de las empresas SaaS
- Eficiencia de marketing y ventas
- Comportamiento y satisfacción del cliente
- Tendencias temporales en métricas clave
