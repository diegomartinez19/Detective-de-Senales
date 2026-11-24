# Detective-de-Senales

Repositorio destinado a los avances semanales de código desarrollados en **Google Colab** para el proyecto *Detective de Señales* (clasificación automática de modulaciones digitales `ASK`, `FSK`, `PSK` y `QAM` con Deep Learning).

## Avances por semana

- **Semana 1 (`PrimeraSemana.ipynb`):** Generación de señales moduladas (`ASK`, `FSK`, `PSK`, `16-QAM`), adición de ruido AWGN a distintos niveles de SNR, división entrenamiento/prueba y gráficas iniciales.
- **Semana 2 (`SegundaSemana.ipynb`):** Diseño, compilación y entrenamiento de una red neuronal convolucional 1D (`Conv1D` + `ReLU` + `Flatten` + salida `Softmax` de 4 clases) y guardado del modelo entrenado.
- **Semana 3 (`TerceraSemana.ipynb`):** Evaluación sobre el conjunto de prueba, matriz de confusión, prueba de estrés por nivel de SNR (`0` a `20 dB`), gráfica de rendimiento y análisis de errores/preguntas técnicas.
