# NLP
Repositorio Materia de NLP - MIAA
Mini-proyecto NLP y LSTM — Detección de SMS Spam

Mini-proyecto de clasificación de texto para Google Colab. El caso utiliza
ucirvine/sms_spam y compara:

TF-IDF + Regresión Logística.

LSTM con embeddings aleatorios.

BiLSTM + atención con embeddings aleatorios.

BiLSTM + atención con embeddings preentrenados de spaCy.

#Contenido académico

EDA textual.

Normalización orientada al dominio.

Split estratificado train/validation/test.

Control de data leakage.

Vocabulario construido sólo con train.

pack_padded_sequence.

PyTorch Lightning + early stopping + TensorBoard.

Accuracy, Precision, Recall, F1, ROC-AUC y PR-AUC.

Ajuste de threshold exclusivamente con validación.

Matrices de confusión.

Análisis de errores.

Visualización exploratoria de atención.

Demo con mensajes nuevos.

Exportación de métricas y configuración.

#Ejecución

Abrir MiniProyecto_NLP_SMS_Spam_LSTM_Colab.ipynb en Google Colab y seleccionar
una GPU T4 cuando esté disponible. Ejecutar las celdas en orden.

#Dataset

SMS Spam Collection, disponible mediante Hugging Face Datasets como
ucirvine/sms_spam.

#Nota metodológica

La etiqueta del corpus es spam/ham. El proyecto no interpreta automáticamente
spam como malware o phishing.
