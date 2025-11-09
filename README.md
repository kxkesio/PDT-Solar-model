# Proyecto MODEL_PDT

Sistema de detección y clasificación de paneles solares mediante YOLOv8.

### 📂 Estructura
- `Modelo_V2/train_model.py` → script de entrenamiento.
- `Modelo_V2/runs/train/.../weights/best.pt` → modelo final.
- `app.py` → dashboard de visualización en PyQt.
- `requirements.txt` → dependencias del entorno.

### 🔍 Clases detectadas
1. Panel  
2. Panel_incompleto  
3. Panel_impureza  
4. Cono_ref

Entrenado con **YOLOv8x**, 100 epochs, mAP50 = 0.91.
