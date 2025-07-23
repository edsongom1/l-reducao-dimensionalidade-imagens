# 🧐 ML - Redução de Dimensionalidade em Imagens para Redes Neurais

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

## 📋 Descrição

Este projeto implementa técnicas de **redução de dimensionalidade** em imagens como etapa de **pré-processamento para redes neurais**. O sistema processa imagens RGB convertendo-as para tons de cinza e posteriormente para binário, aplicando conceitos fundamentais de **processamento de imagens para Machine Learning**.

## 🎯 Objetivos

* Demonstrar técnicas de redução de dimensionalidade
* Implementar conversão RGB → Escala de Cinza com pesos perceptuais
* Aplicar binarização com threshold adaptativo
* Visualizar e comparar as transformações da imagem
* Preparar imagens para entrada em redes neurais

## 🚀 Funcionalidades

* ✅ Suporte a imagens PNG, JPG, JPEG, BMP
* ✅ Conversão RGB → Grayscale com pesos perceptuais (0.299R + 0.587G + 0.114B)
* ✅ Binarização adaptativa com média dos pixels
* ✅ Visualização lado a lado das transformações
* ✅ Exportação da análise final como PNG
* ✅ Interface gráfica via Tkinter

## 🛠️ Tecnologias Utilizadas

* Python 3.7+
* NumPy
* Matplotlib
* Tkinter

---

## 📦 Instalação

### ✅ Pré-requisitos

```bash
python --version  # Requer Python 3.7+
```

### 📅 Instalar dependências

```bash
pip install numpy matplotlib
```

### 📁 Clonar o repositório

```bash
git clone https://github.com/edsongom1/l-reducao-dimensionalidade-imagens.git
cd l-reducao-dimensionalidade-imagens
```

---

## 💻 Como Usar

### ▶️ Execução Básica

```bash
python projeto-imagempb.py
```

### 🔄 Fluxo de Trabalho

1. **Seleção da imagem**: Interface gráfica para escolher o arquivo
2. **Processamento automático**:

   * Carregamento da imagem RGB
   * Conversão para escala de cinza
   * Binarização com threshold adaptativo
3. **Visualização comparativa** das representações
4. **Exportação** (opcional): Salvamento dos resultados

### 🖼️ Exemplo de Saída

```
======================================================================
Projeto: Redução de Dimensionalidade em Imagens para Redes Neurais
Desenvolvido por Edson Gomes Chaves - 07/2025 - Dio.me
======================================================================
[INFO] Selecione uma imagem para iniciar o processamento...
[INFO] Threshold para binarização: 127
[SUCESSO] Imagem salva em: resultado_analise.png
```

---

## 🔬 Metodologia Técnica

### 🎨 Conversão RGB → Grayscale

```python
Cinza = 0.299 * R + 0.587 * G + 0.114 * B
```

### 🧪 Binarização Adaptativa

```python
threshold = np.mean(imagem_cinza)
imagem_binaria = np.where(imagem_cinza >= threshold, 255, 0)
```

---

## 📁 Estrutura do Projeto

```text
projeto-imagempb.py
├── carregar_imagem()          # Interface de seleção
├── ler_imagem()               # Carregamento e normalização
├── converter_para_cinza()     # Conversão RGB → Grayscale
├── binarizar()                # Threshold adaptativo
└── exibir_e_salvar()          # Visualização e exportação
```

---

## ⚙️ Parâmetros Configuráveis

* Pesos RGB (`w_r`, `w_g`, `w_b`)
* Threshold adaptativo
* Resolução de exportação (DPI)
* Formatos suportados (em `filedialog.askopenfilename()`)

---

## 📊 Aplicações em Machine Learning

* Pré-processamento de dados visuais
* Extração de características visuais (feature extraction)
* Redução de dimensionalidade
* Preparação para CNNs e outras arquiteturas

---

## 🤝 Contribuições

Contribuições são bem-vindas! 👇

1. Faça um fork do repositório
2. Crie sua branch (`git checkout -b feature/SuaFeature`)
3. Commit suas mudanças (`git commit -m 'Minha contribuição'`)
4. Push para a branch (`git push origin feature/SuaFeature`)
5. Abra um Pull Request 🚀

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja [LICENSE](LICENSE) para detalhes.

---

## 👨‍💼 Autor

**Edson Gomes Chaves**
📧 [edsgom@gmail.com](mailto:edsgom@gmail.com)
🎓 Projeto: Dio + BairesDev - Machine Learning Training
🗓️ Data: Julho/2025

---

## 🏢 Instituição

Projeto desenvolvido como parte do programa:

**Dio + BairesDev - Machine Learning Training**

---

⭐ Se este projeto foi últil para você, considere dar uma estrela no repositório!
