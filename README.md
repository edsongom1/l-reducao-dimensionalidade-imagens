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
-
- 
ML - Redução de Dimensionalidade em Imagens para Redes Neurais
Mostrar Imagem
Mostrar Imagem
Mostrar Imagem

📋 Descrição
Este projeto implementa técnicas de redução de dimensionalidade em imagens como etapa de pré-processamento para redes neurais. O sistema processa imagens coloridas (RGB) convertendo-as para tons de cinza e posteriormente para formato binário, demonstrando conceitos fundamentais de processamento de imagens aplicados ao Machine Learning.

🎯 Objetivos
Demonstrar técnicas de redução de dimensionalidade em imagens
Implementar conversão RGB para escala de cinza usando pesos perceptuais
Aplicar binarização baseada em threshold adaptativo
Visualizar e comparar as diferentes representações da imagem
Preparar dados de imagem para entrada em redes neurais
🚀 Funcionalidades
✅ Carregamento de Imagens: Suporte para formatos PNG, JPG, JPEG e BMP
✅ Conversão para Escala de Cinza: Implementação com pesos perceptuais (0.299R + 0.587G + 0.114B)
✅ Binarização Adaptativa: Threshold baseado na média dos pixels
✅ Visualização Comparativa: Display lado a lado das três representações
✅ Exportação de Resultados: Salvamento da análise completa em PNG
✅ Interface Gráfica: Seleção intuitiva de arquivos via Tkinter
🛠️ Tecnologias Utilizadas
Python 3.7+
NumPy: Operações matriciais e processamento numérico
Matplotlib: Visualização e manipulação de imagens
Tkinter: Interface gráfica para seleção de arquivos
📦 Instalação
Pré-requisitos
bash
python --version  # Verificar Python 3.7+
Dependências
bash
pip install numpy matplotlib
Clone do Repositório
bash
git clone https://github.com/edsongom1/l-reducao-dimensionalidade-imagens.git
cd l-reducao-dimensionalidade-imagens
💻 Como Usar
Execução Básica
bash
python projeto-imagempb.py
Fluxo de Trabalho
Seleção da Imagem: Interface gráfica para escolher arquivo
Processamento Automático:
Carregamento da imagem RGB
Conversão para escala de cinza
Binarização com threshold adaptativo
Visualização: Display comparativo das três versões
Salvamento (opcional): Exportação dos resultados
Exemplo de Saída
======================================================================
Projeto: Redução de Dimensionalidade em Imagens para Redes Neurais
Desenvolvido por Edson Gomes Chaves - 07/2025 - Dio.me
======================================================================
[INFO] Selecione uma imagem para iniciar o processamento...
[INFO] Threshold para binarização: 127
[SUCESSO] Imagem salva em: resultado_analise.png
🔬 Metodologia Técnica
Conversão RGB → Escala de Cinza
Utiliza a fórmula padrão de luminância perceptual:

Cinza = 0.299 × R + 0.587 × G + 0.114 × B
Binarização Adaptativa
Aplica threshold baseado na média aritmética dos pixels:

python
threshold = np.mean(imagem_cinza)
imagem_binaria = np.where(imagem_cinza >= threshold, 255, 0)
📊 Estrutura do Projeto
projeto-imagempb.py
├── carregar_imagem()          # Interface de seleção
├── ler_imagem()              # Carregamento e normalização
├── converter_para_cinza()     # Conversão RGB → Grayscale
├── binarizar()               # Threshold adaptativo
└── exibir_e_salvar()         # Visualização e exportação
🔧 Parâmetros Configuráveis
Pesos RGB: Modificar constantes w_r, w_g, w_b para diferentes conversões
Threshold: Alterar método de cálculo em binarizar()
Resolução de Saída: Ajustar DPI no salvamento
Formatos Suportados: Expandir lista em filedialog.askopenfilename()
📈 Aplicações em ML
Pré-processamento: Redução de dimensionalidade (RGB → Grayscale → Binary)
Feature Extraction: Simplificação de características visuais
Data Augmentation: Base para técnicas de aumento de dados
Computer Vision: Preparação para CNNs e algoritmos de visão
🤝 Contribuições
Contribuições são bem-vindas! Para contribuir:

Fork o projeto
Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
Commit suas mudanças (git commit -m 'Add some AmazingFeature')
Push para a branch (git push origin feature/AmazingFeature)
Abra um Pull Request
📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

👨‍💻 Autor
Edson Gomes Chaves

📧 Email: edsgom@gmail.com
🎓 Projeto: Dio - BairesDev - Machine Learning Training
📅 Data: Julho/2025
🏢 Instituição
Desenvolvido como parte do programa de treinamento em Machine Learning:

Dio - BairesDev - Machine Learning Training

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!

