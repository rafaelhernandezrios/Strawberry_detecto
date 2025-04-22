# Configuración del Proyecto / Project Setup

## Español

### Descarga del Modelo YOLOv8
1. Instala ultralytics:
```bash
pip install ultralytics
```

2. Descarga el modelo base:
```bash
# Opción 1: Usando Python
python -c "from ultralytics import YOLO; YOLO('yolov8n.pt')"

# Opción 2: Descarga directa
# Visita: https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt
```

### Archivos de Video de Ejemplo
Los archivos de video de ejemplo no están incluidos en el repositorio debido a su tamaño. Para obtener los videos de ejemplo:

1. Descarga los siguientes archivos:
   - `strawberry.mp4`
   - `bery.mp4`

2. Coloca los archivos descargados en el directorio raíz del proyecto.

### Configuración del Modelo
Una vez descargado el modelo base `yolov8n.pt`, si necesitas reentrenarlo:

1. Prepara tu dataset
2. Modifica el archivo `data.yaml` según sea necesario
3. Sigue las instrucciones en el README.md para el entrenamiento

## English

### YOLOv8 Model Download
1. Install ultralytics:
```bash
pip install ultralytics
```

2. Download the base model:
```bash
# Option 1: Using Python
python -c "from ultralytics import YOLO; YOLO('yolov8n.pt')"

# Option 2: Direct download
# Visit: https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt
```

### Example Video Files
The example video files are not included in the repository due to their size. To get the example videos:

1. Download the following files:
   - `strawberry.mp4`
   - `bery.mp4`

2. Place the downloaded files in the project root directory.

### Model Setup
Once you have downloaded the base model `yolov8n.pt`, if you need to retrain it:

1. Prepare your dataset
2. Modify the `data.yaml` file as needed
3. Follow the training instructions in README.md

## Links de Descarga / Download Links
Para obtener videos de ejemplo de fresas, puedes usar tus propios videos o descargar videos de muestra de:
To get strawberry example videos, you can use your own videos or download sample videos from:

- [Roboflow Universe](https://universe.roboflow.com/mirai-am0w4/object-detection-project-wq4pk-7nhec)
- [Kaggle Datasets](https://www.kaggle.com/datasets?search=strawberry+detection) 