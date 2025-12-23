# Tennis Biomechanic Analysis Project

## Descripción
Este proyecto es un sistema integral de análisis de movimiento en tenis que utiliza visión por computadora y machine learning para analizar los movimientos del jugador, proporcionar retroalimentación en tiempo real y generar recomendaciones de entrenamiento personalizadas.

## Estructura del Proyecto
- `main.py` - Punto de entrada principal
- `motion_analyzer.py` - Analizador de movimiento y pose
- `learning_agent.py` - Agente de aprendizaje automático
- `dashboard.py` - Panel de visualización y reportes

## Componentes Principales

### TennisMotionAnalyzer
Procesa la alimentación de video y extrae métricas de pose:
- Detección de pose en tiempo real con MediaPipe
- Extracción de métricas biomecánicas
- Análisis de ángulos articulares
- Clasificación de tipos de golpe

### SelfLearningAgent
Analiza datos de rendimiento y genera insights:
- Identificación de tendencias y patrones
- Análisis de fortalezas y debilidades
- Generación de planes de entrenamiento personalizados
- Seguimiento de progreso

### TennisPerformanceDashboard
Visualiza métricas y crea reportes:
- Generación de dashboards visuales
- Comparación con benchmarks
- Exportación de reportes en JSON
- Visualización de progreso

## Instalación
```bash
pip install opencv-python mediapipe numpy pandas matplotlib scipy
```

## Uso
Ejecutar el análisis:
```bash
python main.py
```

## Tecnologías
- **Visión por Computadora**: OpenCV
- **Detección de Pose**: MediaPipe
- **Análisis de Datos**: NumPy, Pandas, SciPy
- **Visualización**: Matplotlib
- **Machine Learning**: Algoritmos de aprendizaje automático
