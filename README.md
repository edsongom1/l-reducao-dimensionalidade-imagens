# ML - Redução de Dimensionalidade em Imagens para Redes Neurais

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

## 📋 Descrição

Este projeto implementa técnicas de redução de dimensionalidade em imagens como etapa de pré-processamento para redes neurais. O sistema processa imagens coloridas (RGB) convertendo-as para tons de cinza e posteriormente para formato binário, demonstrando conceitos fundamentais de processamento de imagens aplicados ao Machine Learning.

## 🎯 Objetivos

- Demonstrar técnicas de redução de dimensionalidade em imagens
- Implementar conversão RGB para escala de cinza usando pesos perceptuais
- Aplicar binarização baseada em threshold adaptativo
- Visualizar e comparar as diferentes representações da imagem
- Preparar dados de imagem para entrada em redes neurais

## 🚀 Funcionalidades

- ✅ **Carregamento de Imagens**: Suporte para formatos PNG, JPG, JPEG e BMP
- ✅ **Conversão para Escala de Cinza**: Implementação com pesos perceptuais (0.299R + 0.587G + 0.114B)
- ✅ **Binarização Adaptativa**: Threshold baseado na média dos pixels
- ✅ **Visualização Comparativa**: Display lado a lado das três representações
- ✅ **Exportação de Resultados**: Salvamento da análise completa em PNG
- ✅ **Interface Gráfica**: Seleção intuitiva de arquivos via Tkinter
