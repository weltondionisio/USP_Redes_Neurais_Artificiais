# Modelagem de Dados com Redes Neurais Artificiais

**Universidade de São Paulo (USP)**  
**Programa/Área:** Zoologia  
**Oferta:** 2026/2  
**Carga horária:** 60 horas | 4 créditos | 4 semanas  
**Modalidade:** Presencial  

## Sobre a disciplina

A disciplina **Modelagem de Dados com Redes Neurais Artificiais** apresenta os fundamentos teóricos e computacionais de Redes Neurais Artificiais (RNA) e Deep Learning, com ênfase na aplicação dessas técnicas a problemas de pesquisa em Ciências Biológicas.

Ao longo da disciplina, serão abordados desde os fundamentos de Inteligência Artificial, aprendizado de máquina e redes neurais até arquiteturas modernas de Deep Learning, incluindo **Multilayer Perceptrons (MLPs), Redes Convolucionais (CNNs), Redes Recorrentes (RNNs), LSTM, GRU e Transformers**.

As atividades combinam fundamentos teóricos, implementação computacional e aplicação a dados biológicos, ecológicos, ambientais, epidemiológicos, genômicos, bioinformáticos, imagens, sons e séries temporais.

O objetivo não é apenas utilizar modelos prontos, mas compreender **como os modelos funcionam, como treiná-los, avaliá-los e interpretar seus resultados**, permitindo sua utilização crítica em pesquisas científicas.

---

## Objetivos

Ao final da disciplina, espera-se que os estudantes sejam capazes de:

- compreender os fundamentos de Inteligência Artificial, Machine Learning e Deep Learning;
- compreender os princípios matemáticos e computacionais das Redes Neurais Artificiais;
- construir, treinar e validar modelos neurais;
- selecionar arquiteturas adequadas para diferentes tipos de dados;
- aplicar redes neurais a problemas biológicos reais;
- utilizar técnicas de regularização e otimização;
- interpretar modelos utilizando técnicas de Explainable AI (XAI);
- aplicar CNNs à análise de imagens biológicas;
- utilizar redes recorrentes para modelagem de séries temporais;
- compreender a arquitetura e o funcionamento de Transformers;
- utilizar modelos pré-treinados em problemas científicos;
- desenvolver fluxos reprodutíveis de análise utilizando Python;
- interpretar criticamente os resultados de modelos de Deep Learning.

---

# Estrutura da disciplina

## Módulo 1 — Fundamentos de Inteligência Artificial e Redes Neurais

**10 horas**

Introdução aos conceitos fundamentais de Inteligência Artificial, Machine Learning e Deep Learning.

### Conteúdos

- História da Inteligência Artificial
- IA simbólica e aprendizado de máquina
- Aprendizado supervisionado e não supervisionado
- Deep Learning na ciência moderna
- Vetores e matrizes
- Álgebra linear aplicada
- Derivadas e gradientes
- Probabilidade e estatística
- Neurônio artificial
- Modelo de McCulloch-Pitts
- Perceptron
- Funções de ativação:
  - Sigmoid
  - Tanh
  - ReLU
  - Leaky ReLU
  - GELU

### Laboratório

Construção de um perceptron em Python e visualização de fronteiras de decisão.

---

## Módulo 2 — Redes Neurais Feedforward e Treinamento

**10 horas**

Construção e treinamento de redes neurais multicamadas.

### Conteúdos

- Multilayer Perceptrons (MLPs)
- Arquitetura de redes neurais
- Forward propagation
- Backpropagation
- Funções de perda
- Gradient Descent
- Stochastic Gradient Descent (SGD)
- Momentum
- RMSProp
- Adam
- Early Stopping
- Regularização L1 e L2
- Batch Normalization
- Dropout

### Laboratório

Construção de classificadores utilizando dados biológicos.

---

## Módulo 3 — Deep Learning para Dados Biológicos Tabulares

**8 horas**

Aplicação de redes neurais a dados estruturados provenientes de estudos biológicos e ecológicos.

### Conteúdos

- Predição e classificação
- Presença e ausência de espécies
- Dados epidemiológicos
- Bioindicadores ambientais
- Modelagem de dados ecológicos
- Interpretabilidade de modelos
- Feature Importance
- SHAP
- LIME

### Laboratório

Desenvolvimento de modelos neurais aplicados a dados ecológicos.

---

## Módulo 4 — Redes Convolucionais e Visão Computacional

**10 horas**

Introdução ao Deep Learning para análise automatizada de imagens.

### Conteúdos

- Redes Convolucionais (CNNs)
- Operações de convolução
- Pooling
- Extração de características
- LeNet
- AlexNet
- VGG
- ResNet
- EfficientNet
- Transfer Learning
- Fine-tuning
- Data Augmentation

### Aplicações biológicas

- Identificação automatizada de espécies
- Fototrilhas
- Microscopia
- Diagnóstico automatizado

### Laboratório

Treinamento de CNNs utilizando imagens biológicas.

---

## Módulo 5 — Redes Recorrentes e Séries Temporais

**6 horas**

Aplicação de redes neurais à modelagem de dados sequenciais e temporais.

### Conteúdos

- Redes Neurais Recorrentes (RNNs)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Fenologia
- Séries climáticas
- Dinâmica populacional
- Monitoramento ambiental

### Laboratório

Predição de séries temporais ecológicas.

---

## Módulo 6 — Transformers e Inteligência Artificial Generativa

**8 horas**

Introdução às arquiteturas modernas baseadas em mecanismos de atenção.

### Conteúdos

- Attention Mechanism
- Self-Attention
- Multi-Head Attention
- Arquitetura Transformer
- BERT
- GPT
- Vision Transformers (ViT)
- Modelos fundacionais para Biologia
- Large Language Models (LLMs)
- Modelos de difusão
- Geração de imagens

### Aplicações em Ciências Biológicas

- Bioinformática
- Análise de sequências genéticas
- Processamento de literatura científica
- Modelos fundacionais para Biologia
- Inteligência Artificial Generativa aplicada à ciência

### Laboratório

Utilização de modelos pré-treinados em problemas biológicos.

---

## Módulo 7 — Projeto Integrador e Seminários

**8 horas**

Desenvolvimento de um projeto completo de Deep Learning aplicado a um problema biológico.

Cada equipe deverá:

1. Definir um problema biológico real;
2. Construir ou organizar uma base de dados;
3. Desenvolver um modelo neural;
4. Treinar e validar o modelo;
5. Avaliar seu desempenho;
6. Interpretar os resultados;
7. Elaborar um relatório científico;
8. Apresentar os resultados em um seminário técnico.

---

# Aplicações

A disciplina aborda diferentes tipos de dados encontrados na pesquisa biológica:

| Tipo de dado | Exemplos de aplicação |
|---|---|
| **Dados tabulares** | Ecologia, epidemiologia, bioindicadores |
| **Imagens** | Identificação de espécies, microscopia, fototrilhas |
| **Séries temporais** | Clima, fenologia, dinâmica populacional |
| **Sons** | Monitoramento acústico da biodiversidade |
| **Sequências** | Genômica e bioinformática |
| **Texto** | Literatura científica e processamento de linguagem |
| **Dados ambientais** | Predição e monitoramento de mudanças ambientais |

---

# Metodologia

A disciplina combina:

- aulas teóricas;
- aulas práticas;
- programação em Python;
- notebooks computacionais;
- análise de dados biológicos;
- exercícios de modelagem;
- discussão de aplicações científicas;
- seminários;
- projeto integrador.

A abordagem é orientada à **pesquisa científica baseada em dados**, priorizando a compreensão dos métodos e sua aplicação crítica, e não apenas a utilização de modelos como ferramentas de "caixa-preta".

---

# Avaliação

A avaliação será realizada em equipe por meio de dois produtos principais.

### Projeto escrito — 40%

Desenvolvimento de um modelo de aprendizado de máquina aplicado a um conjunto de dados biológicos, acompanhado de relatório técnico conforme as normas da ABNT e do código computacional utilizado.

| Critério | Peso |
|---|---:|
| Fundamentação teórica | 20% |
| Adequação metodológica | 30% |
| Qualidade do código | 20% |
| Análise e interpretação dos resultados | 30% |

### Seminário — 60%

Resolução, discussão e apresentação de problemas utilizando dados biológicos.

| Critério | Peso |
|---|---:|
| Domínio e clareza do conteúdo | 30% |
| Interpretação e discussão dos resultados | 30% |
| Aplicação correta das técnicas | 30% |
| Respostas aos questionamentos | 10% |

---

# Ambiente computacional

Os exemplos e atividades práticas serão desenvolvidos em **Python**.

### Ambientes recomendados

- [Jupyter Notebook](https://jupyter.org/)
- [Google Colab](https://colab.research.google.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

### Principais bibliotecas

- `pandas`
- `numpy`
- `scikit-learn`
- `tensorflow`
- `keras`
- `matplotlib`

O estudante deverá possuir um computador com acesso à internet e um ambiente Python funcional.

---

# Bibliografia principal

- **Bishop, C. M.; Bishop, H.** *Deep Learning: Foundations and Concepts*. Springer, 2024.
- **Goodfellow, I.; Bengio, Y.; Courville, A.** *Deep Learning*. MIT Press, 2016.
- **Géron, A.** *Mãos à obra: aprendizado de máquina com Scikit-Learn & TensorFlow*. Alta Books, 2019.
- **Hastie, T.; Tibshirani, R.; Friedman, J.** *The Elements of Statistical Learning*. Springer, 2009.
- **Murphy, K. P.** *Machine Learning: A Probabilistic Perspective*. MIT Press, 2012.
- **Izbicki, R.; dos Santos, T. M.** *Aprendizado de máquina: uma abordagem estatística*. UICLAP, 2020.
- **Quinn, G. P.; Keough, M. J.** *Experimental Design and Data Analysis for Biologists*. Cambridge University Press, 2002.

Uma introdução visual ao Deep Learning também será utilizada como material complementar:

- **Amer, M.** *A Visual Introduction to Deep Learning*. KDIMENSIONS, 2020.

---

# Docentes

### Dr. Welton Dionisio da Silva
Docente USP

### Dr. Rodrigo Hirata Willemart
Docente USP

---

# Organização do repositório

Este repositório reúne os materiais computacionais utilizados ao longo da disciplina, incluindo notebooks, códigos, exemplos, conjuntos de dados e atividades práticas.

```text
.
├── README.md
├── 01_fundamentos/
├── 02_mlp_treinamento/
├── 03_dados_tabulares/
├── 04_cnns/
├── 05_series_temporais/
├── 06_transformers/
├── 07_projeto_integrador/
├── datasets/
└── requirements.txt
