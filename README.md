# 🧠 Sistema de Recomendação com Deep Learning (Imagens)

Este projeto cria um sistema de recomendação visual de produtos (como roupas e acessórios) utilizando **redes neurais convolucionais (CNNs)** e **Transferência de Aprendizado** com `MobileNetV2`.

---

## 📌 Objetivo

Treinar um modelo de deep learning para classificar 4 tipos de produtos com base em imagens:

- 👕 Camisa normal  
- 👕 Camisa de time  
- ⌚ Relógio smartwatch  
- 🩴 Chinelo  

Depois, usando a **similaridade de vetores extraídos do modelo**, recomendaremos produtos similares automaticamente.

---

## 🛠️ Requisitos

- ✅ Python 3.7+
- ✅ TensorFlow 2.x
- ✅ NumPy, Matplotlib, scikit-learn
- ✅ Google Colab (recomendado)

---

## 📁 Estrutura do Projeto

Organize suas imagens em subpastas (1 por classe):

dataset/
├── camisa_normal/
│ ├── img1.jpg
│ ├── img2.jpg
│ └── ...
├── camisa_time/
│ ├── img1.jpg
│ ├── img2.jpg
│ └── ...
├── relogio_smartwatch/
│ ├── img1.jpg
│ └── ...
└── chinelo/


