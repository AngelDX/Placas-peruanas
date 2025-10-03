# Dataset de Placas Vehiculares Peruanas

Este repositorio contiene un **dataset de imágenes de placas vehiculares peruanas** recolectado con fines académicos e investigativos. Además, se incluyen los **resultados de pruebas realizadas con modelos de OCR y detección de objetos** para el reconocimiento automático de placas.

## 📂 Contenido del repositorio

- `dataset/` → Carpeta con las imágenes de placas vehiculares peruanas.
- `experimentos/` → Reportes y gráficos con los resultados de los experimentos.
- `README.md` → Este archivo de documentación.

## 🎯 Objetivo

El objetivo de este dataset es facilitar la investigación y el desarrollo de **sistemas de reconocimiento automático de placas (ALPR)** en el contexto peruano, considerando particularidades como:
- Tipografía de las placas peruanas.
- Variaciones de iluminación y ángulo.
- Condiciones de ruido en las imágenes.

## 🧪 Pruebas realizadas

Se evaluaron distintos modelos de reconocimiento y detección:

- **Detección de placas**: Modelos basados en YOLOv12 con 100 epocas de entrenamiento.
- **OCR**: Pruebas con PaddleOCR.
- **Métricas obtenidas**:
  - **Precisión (Precision):** 1.000
  - **Exhaustividad (Recall):** 1.000
  - **mAP50:** 0.995
  - **mAP50-95:** 0.945


## 📊 Resultados destacados

- Se logró una tasa de reconocimiento correcta de **placas completas del 99.5%**.
- Los errores más comunes fueron por:
  - Placas con iluminación deficiente.
  - Fotografías en ángulos extremos.
  - Ruido en la imagen (movimiento, baja resolución).

## 🚀 Próximos pasos

- Entrenar modelos específicos para mejorar la precisión en condiciones nocturnas.
- Publicar scripts de preprocesamiento y entrenamiento.
- Mejorar la clasificación de los 0 con "O" y 1 con "I".  

## ⚖️ Licencia

Este dataset se distribuye bajo la licencia **CC BY-NC 4.0** (Uso académico e investigativo, no comercial).  
Por favor, citar este repositorio si utilizas el dataset en tu investigación o proyecto.

## ✨ Autor

- **Angel Rosendo Condori Coaquira**  
  Docente e investigador Universidad Peruana Unión.  
  Escuela Profesional de Ingenieria de Sistemas
  angelrc2@upeu.edu.pe
