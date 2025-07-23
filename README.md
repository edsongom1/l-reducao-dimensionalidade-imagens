# 🧠 ML - Redução de Dimensionalidade em Imagens para Redes Neurais

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

## 📋 Descrição

Este projeto implementa técnicas de **redução de dimensionalidade** em imagens como etapa de **pré-processamento para redes neurais**. O sistema processa imagens RGB convertendo-as para tons de cinza e posteriormente para binário, aplicando conceitos fundamentais de **processamento de imagens para Machine Learning**.

## 🎯 Objetivos

- Demonstrar técnicas de redução de dimensionalidade
- Implementar conversão RGB → Escala de Cinza com pesos perceptuais
- Aplicar binarização com threshold adaptativo
- Visualizar e comparar as transformações da imagem
- Preparar imagens para entrada em redes neurais

## 🚀 Funcionalidades

- ✅ Suporte a imagens PNG, JPG, JPEG, BMP
- ✅ Conversão RGB → Grayscale com pesos perceptuais (0.299R + 0.587G + 0.114B)
- ✅ Binarização adaptativa com média dos pixels
- ✅ Visualização lado a lado das transformações
- ✅ Exportação da análise final como PNG
- ✅ Interface gráfica via Tkinter

## 🛠️ Tecnologias Utilizadas

- Python 3.7+
- NumPy
- Matplotlib
- Tkinter

---

## 📦 Instalação

### ✅ Pré-requisitos

```bash
python --version  # Requer Python 3.7+
