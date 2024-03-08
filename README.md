# Licence-Plate-Detection-using-YOLO-V8

1.  Instalar las dependencias con `pip install -r requirements.txt`
2.  Conectar cámara usb
3.  Ir al directorio de la app y ejecutar con `python3.11 ultralytics/yolo/v8/detect/predict.py model="best.pt" source=0 show=true save_crop=true vid_stride=20`
4.  Las imagenes de guardan en el directorio *runs/detect*
