# \# 🧠 IA para Detecção de Melanoma (PIBIC 2025/2026)

# 

# Repositório responsável pelo desenvolvimento, treinamento e validação da Rede Neural Convolucional (CNN) para classificação de lesões de pele.

# 

# \## 🎯 Objetivo

# Treinar um modelo capaz de distinguir \*\*Melanoma\*\* de outras 7 lesões cutâneas utilizando o dataset \*\*ISIC 2019\*\*.

# 

# \## 🛠️ Tecnologias

# \- \*\*Linguagem:\*\* Python 3.10+

# \- \*\*Framework:\*\* TensorFlow / Keras

# \- \*\*Ambiente:\*\* Google Colab (GPU T4)

# 

# \## 📊 Resultados Atuais (V2)

# \- \*\*Acurácia de Treino:\*\* ~60%

# \- \*\*Acurácia de Validação:\*\* ~62%

# \- \*\*Status:\*\* Overfitting eliminado com sucesso usando Data Augmentation e Dropout.

# 

# \## 📂 Estrutura

# \- `/notebooks`: Contém os Jupyter Notebooks com o histórico de experimentos.

# \- `/models`: Contém o arquivo `.keras` final pronto para inferência.

# 

# \## 🚀 Como usar o modelo

# ```python

# import tensorflow as tf

# model = tf.keras.models.load\_model('models/modelo\_treinado\_v2.keras')

# \# model.predict(imagem)

