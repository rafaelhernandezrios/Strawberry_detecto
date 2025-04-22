# Modelo de Detección de Fresas con YOLOv8 / Strawberry Detection Model with YOLOv8

## Español

### Descripción
Este proyecto implementa un modelo de detección de fresas utilizando YOLOv8, capaz de identificar y localizar fresas en videos en tiempo real.

### Requisitos
- Python 3.8 o superior
- PyTorch
- Ultralytics
- OpenCV

### Instalación
```bash
# Crear un entorno virtual (recomendado)
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows

# Instalar dependencias
pip install ultralytics
pip install opencv-python
```

### Uso con Videos
1. Coloca tu video en el directorio del proyecto
2. Ejecuta el siguiente comando:
```bash
# Para procesar un video
yolo predict model=yolov8n.pt source="tu_video.mp4" save=True

# Para usar la webcam
yolo predict model=yolov8n.pt source=0 save=True
```

### Ejemplos Incluidos
El proyecto incluye videos de muestra:
- `strawberry.mp4`
- `bery.mp4`

## English

### Description
This project implements a strawberry detection model using YOLOv8, capable of identifying and locating strawberries in videos in real-time.

### Requirements
- Python 3.8 or higher
- PyTorch
- Ultralytics
- OpenCV

### Installation
```bash
# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows

# Install dependencies
pip install ultralytics
pip install opencv-python
```

### Usage with Videos
1. Place your video in the project directory
2. Run the following command:
```bash
# To process a video
yolo predict model=yolov8n.pt source="your_video.mp4" save=True

# To use webcam
yolo predict model=yolov8n.pt source=0 save=True
```

### Included Examples
The project includes sample videos:
- `strawberry.mp4`
- `bery.mp4`

## Additional Information
- Model: YOLOv8n
- Dataset: Custom strawberry detection dataset
- License: CC BY 4.0 