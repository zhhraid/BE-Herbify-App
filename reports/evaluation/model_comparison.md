# Perbandingan Model: MobileNetV2 vs ResNet50 vs EfficientNetB0

## Tabel Perbandingan

| Metrik             |   MobileNetV2 |       ResNet50 |   EfficientNetB0 |
|:-------------------|--------------:|---------------:|-----------------:|
| Accuracy           |   0.973       |    0.6984      |      0.9884      |
| Precision          |   0.9739      |    0.7309      |      0.9891      |
| Recall             |   0.973       |    0.6984      |      0.9884      |
| F1-Score           |   0.9729      |    0.7039      |      0.9884      |
| Avg Inference (ms) | 252.74        | 1178.48        |    283.98        |
| Model Size (MB)    |   9.2         |   90.7         |     16           |
| Total Parameters   |   2.34557e+06 |    2.37088e+07 |      4.12924e+06 |

## Rekomendasi

**Model terbaik untuk production: EFFICIENTNETB0**

Model ini akan di-load oleh FastAPI backend untuk endpoint `/predict`.
