Laboratorio 1 – Competencia Kaggle
Submit Final – Diego Farfán

Este repositorio reúne el notebook principal y los archivos necesarios para reproducir exactamente el submit final presentado en la competencia de Kaggle del Laboratorio 1.

────────────────────────────

📁 Estructura

LABORATORIO_1_COMPE_DF_R10.ipynb
↳ Notebook principal: preprocesamiento, reconstrucción de hiperparámetros, entrenamiento final multisemilla (40 modelos), ensamble y generación del submit.

kaggle/
↳ Contiene los archivos CSV generados, incluyendo el submit final.

────────────────────────────

▶️ Cómo reproducir

Abrir el notebook principal en Google Colab o RStudio.

(Colab) Montar Google Drive — instrucciones incluidas en el notebook.

Ejecutar todas las celdas en orden.

El proceso genera un archivo submit_final.csv idéntico al enviado a Kaggle.

────────────────────────────

📦 Dependencias

data.table • lightgbm • R.utils • primes
(El notebook instala todo automáticamente.)

────────────────────────────

🔁 Reproducibilidad

✓ Semillas fijas
✓ Hiperparámetros obtenidos desde BO_log.txt
✓ CSV generados en carpeta kaggle/

📬 Contacto

Diego Ernesto Farfán
Maestría en Ciencia de Datos – Laboratorio 1
