# 🧠 Reconhecimento de Dígitos Manuscritos com PyTorch (MNIST)

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![Dataset](https://img.shields.io/badge/Dataset-MNIST-green?style=for-the-badge)

---

## 📌 Sobre o Projeto

Este projeto implementa uma **Rede Neural Convolucional (CNN)** utilizando **PyTorch** para reconhecimento de dígitos manuscritos do famoso dataset **MNIST**.

O objetivo principal é demonstrar, na prática, o fluxo completo de um projeto de **Deep Learning**, passando por:

- carregamento e tratamento dos dados;
- criação da arquitetura da rede neural;
- treinamento do modelo;
- validação e análise de desempenho.

---

## 🖼️ Dataset Utilizado

O projeto utiliza o dataset **MNIST**, contendo:

- 70.000 imagens em escala de cinza;
- dígitos de `0` a `9`;
- imagens com dimensão `28x28 pixels`.

---

## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
|---|---|
| Python | Linguagem principal do projeto |
| PyTorch | Framework de Deep Learning |
| Torchvision | Carregamento do dataset MNIST |
| NumPy | Operações numéricas |
| Matplotlib | Visualização de imagens |

---

# ▶️ Como Executar

Execute o notebook utilizando uma das opções abaixo:

- Jupyter Notebook
- VS Code
- Google Colab

---

## 1. Importação das Bibliotecas

Carregamento das dependências necessárias para o funcionamento do projeto.

---

## 2. Carregamento do Dataset

Download automático do dataset MNIST utilizando o Torchvision.

```python
from torchvision import datasets
```

---

## 3. Visualização das Imagens

Exibição de exemplos de dígitos manuscritos presentes no dataset.

```python
import matplotlib.pyplot as plt
```

---

## 4. Construção da Rede Neural

Definição da arquitetura da CNN utilizando PyTorch.

```python
import torch.nn as nn
```

---

## 5. Treinamento do Modelo

Treinamento utilizando:

- SGD (Stochastic Gradient Descent)
- NLLLoss (Negative Log Likelihood Loss)

```python
optimizer = torch.optim.SGD(model.parameters(), lr=0.01)
```

---

## 6. Validação do Modelo

Avaliação da precisão do modelo em dados nunca vistos anteriormente.

```python
model.eval()
```

#  Resultados

O modelo foi capaz de aprender padrões dos dígitos manuscritos, alcançando uma boa precisão durante o processo de validação.

## Exemplos de capacidades do modelo

- Reconhecimento automático de números manuscritos;
- Classificação entre 10 classes diferentes (`0-9`);
- Generalização em imagens não vistas durante o treinamento.

---

# 📷 Exemplo de Saída

## Dígitos do Dataset

```markdown
<img src="assets/mnist-example.png" width="500">
```

---

# 👨‍💻 Autor

## Yago Alves Toledo

Projeto desenvolvido para estudos de Deep Learning e Redes Neurais utilizando PyTorch Orientado pelo professor Diego da DIO.

---

# Considerações Finais

Este projeto demonstra conceitos fundamentais de:

- Machine Learning;
- Deep Learning;
- Redes Neurais Convolucionais;
- Classificação de Imagens;
- Processamento de Dados com PyTorch.

---
