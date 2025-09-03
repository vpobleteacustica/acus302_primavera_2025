# Práctica de Ecoacústica — Guía rápida

1. Instala dependencias (una vez):  
   `pip install librosa soundfile numpy matplotlib pandas scipy`

2. Abre el notebook `Humedales_Ecoacustica_Practica.ipynb` y:
   - Completa `metadatos_campo.csv` (una fila por audio).
   - Carga tu archivo (`audio_file = "mi_audio.wav"`).
   - Genera waveform, espectrograma y PSD.
   - Etiqueta segmentos en `anotaciones_segmentos.csv`.
   - (Opcional) Exporta pequeños fragmentos WAV.
   - Calcula el **resumen por clases** (% tiempo bio/antro/geo).

3. Entrega: los dos CSV + 1–2 figuras con espectrogramas y una breve reflexión.

> Consejo: si el viento es fuerte, aplica el filtro pasa-altos (300 Hz).
