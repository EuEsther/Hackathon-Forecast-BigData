# Hackathon-Forecast-BigData

 🛒 Hackathon - Previsão de Vendas por PDV/SKU

Este repositório contém a solução desenvolvida para o desafio de **previsão de vendas** (forecast) em um hackathon.  
O objetivo é prever a **quantidade semanal de vendas por Ponto de Venda (PDV) e SKU** para as cinco semanas de **janeiro/2023**, utilizando como base o histórico de vendas de **2022**.

---

## 📂 Estrutura do Projeto

- `Hackathon.ipynb` → Notebook principal com todo o pipeline de análise e modelagem.
- `requirements.txt` → Dependências do projeto.
- `data/` → Pasta para armazenamento dos arquivos `.parquet` (baixados automaticamente).
- `output/` → Pasta de saída contendo os arquivos de previsão gerados em `.csv` ou `.parquet`.

---

## 🚀 Tecnologias Utilizadas

- [Python 3.9+](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [LightGBM](https://lightgbm.readthedocs.io/)
- [gdown](https://github.com/wkentaro/gdown) (para download dos dados via Google Drive)

---

## ⚙️ Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seuusuario/hackathon-vendas.git
cd hackathon-vendas
pip install -r requirements.txt
