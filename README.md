# Predição de Preços de Criptomoedas com Inteligência Artificial

**Título Completo:** Predição de Preços de Criptomoedas Utilizando Modelos de Séries Temporais Lineares, Não Lineares e Híbridos

---

##  Sobre o Projeto

Este projeto explora a aplicação de modelos de Inteligência Artificial para prever o preço de fechamento do Bitcoin (BTC). O objetivo é construir, treinar e avaliar comparativamente três famílias distintas de modelos de séries temporais para determinar sua eficácia em um ambiente financeiro volátil.

As famílias de modelos a serem estudadas na próxima fase são:
* **Modelos Lineares** (ARIMA)
* **Modelos Não Lineares** (LSTM)
* **Modelos Híbridos** (ARIMA-LSTM)

### Contexto Acadêmico
Este trabalho é parte da avaliação da disciplina de **Inteligência Artificial** (7º Semestre, CC-Noite), ministrada pelo Prof. Dr. Ivan Carlos Alcântara de Oliveira na **Universidade Presbiteriana Mackenzie**.

---
##  Progressão do Projeto

Este projeto é dividido em duas entregas principais, conforme o cronograma da disciplina.

####  **Entrega N1 (28/09/2025)**
      Definição da Proposta e Estrutura do Projeto
      Obtenção e Limpeza do Dataset 
      Análise Exploratória de Dados 
      Preparação e Geração dos Dados Processados 
      Criação do Relatório Parcial 
      Configuração do Ambiente 

####  **Entrega N2 (Próximos Passos)**
Implementação dos Modelos (ARIMA, LSTM, Híbrido)
Análise Comparativa dos Resultados
Finalização do Relatório
Gravação do Vídeo de Apresentação

---

## Estrutura do Repositório

```
Proj.IA2026.02/
│
├── README.md           # Este arquivo de apresentação.
├── requirements.txt    # Lista de bibliotecas Python para o projeto.
│
├── dados/
│   ├── raw/            # Contém o dataset original.
│   │   └── Bitcoin Historical Data.csv
│   └── processed/      # Contém os dados limpos e prontos para modelagem.
│       ├── btc_data_cleaned.csv
│       ├── X_data_lstm.npy
│       ├── y_data_lstm.npy
│       └── price_scaler.pkl
│
├── notebooks/
│   └── 01_Exploratory_Data_Analysis.ipynb
│
└── relatorio/
    └── [Nome do seu arquivo de relatório.pdf]
```

---

## Dataset

Os dados utilizados neste projeto consistem no histórico diário de preços do Bitcoin (BTC), obtidos manualmente do portal **Investing.com**.

* **Fonte:** `https://www.investing.com/crypto/bitcoin/historical-data`
* **Período dos Dados:** 06 de Setembro de 2014 a 20 de Setembro de 2025.
* **Features:** Data, Preço de Fechamento, Abertura, Máxima, Mínima e Volume.

---

## Como Executar e Verificar (Entrega N1)

Para replicar os resultados da primeira entrega (Análise e Preparação dos Dados):

**1. Clone o repositório:**
```bash
git clone [https://github.com/mlinard/Proj.IA2026.02]
cd Proj.IA2026.02
```

**2. Crie e ative um ambiente virtual:**
```bash

python -m venv venv
.\venv\Scripts\activate
```

**3. Instale as dependências:**
```bash
pip install -r requirementos.txt
```

**4. Verifique os resultados:**
* **Para ver os dados já processados:** Navegue até a pasta `dados/processedos/`. Os arquivos gerados pela análise já estão salvos lá.
* **Para executar a análise novamente:** Abra e execute o notebook `notebooks/01_Exploratory_Data_Analysis.ipynb`. Ele irá carregar os dados brutos de `dados/raw/` e recriar os arquivos processados.

---

##  Tecnologias e Ferramentas

* **Python 3.9+**
* **Google Colab**
* **Pandas & NumPy**
* **Matplotlib & Seaborn**
* **Scikit-learn**
* **TensorFlow & Statsmodels** (serão usados na N2)


---

## Autor

Feito por **Marcello Linard Teixeira**.

* **RA:** 10419338
