# 🧬 IPO Internship — Bioinformatic Analysis of Molecular Alterations in Prostate Cancer

## 📋 Descrição

Este repositório contém o trabalho desenvolvido durante o estágio no **IPO (Instituto Português de Oncologia)**, com foco na análise bioinformática de **alterações moleculares no tecido normal adjacente ao tumor (NAT — Normal Adjacent Tissue)** em casos de **cancro da próstata**.

O objetivo central é compreender de que forma o tecido aparentemente normal que envolve um tumor apresenta alterações moleculares distintas do tecido saudável, contribuindo para uma melhor compreensão da progressão tumoral e dos mecanismos epigenéticos/genómicos associados ao cancro da próstata.

---

## 📁 Estrutura do Repositório

```
IPO_internship/
│
├── InitialDatasets/          # Datasets iniciais utilizados na análise
├── AnaliseEstagio.ipynb      # Notebook principal com toda a análise bioinformática
├── data.csv                  # Dados processados utilizados nas análises
└── README.md                 # Documentação do projeto
```

> ⚠️ **Nota:** O dataset `TCGA_PRAD_IlluminiSeq` (dados de sequenciação do The Cancer Genome Atlas — Prostate Adenocarcinoma) foi utilizado como base adicional, mas não foi incluído no repositório devido ao seu tamanho elevado.

---

## 🔬 Dados Utilizados

| Dataset | Fonte | Descrição |
|---|---|---|
| InitialDatasets | IPO / local | Conjuntos de dados iniciais da análise |
| data.csv | Processado | Dados integrados e limpos para análise |
| TCGA_PRAD_IlluminiSeq | [TCGA](https://www.cancer.gov/tcga) | Dados de expressão génica por sequenciação (Illumina) — não incluído |

---

## 🧪 Análise

A análise principal encontra-se no notebook **`AnaliseEstagio.ipynb`** e inclui:

- **Pré-processamento de dados** — limpeza, normalização e integração dos datasets
- **Análise exploratória (EDA)** — visualização de distribuições e padrões nos dados moleculares
- **Comparação NAT vs. Tumor** — identificação de alterações moleculares diferenciais entre tecido tumoral e tecido normal adjacente
- **Análise de expressão génica** — estudo de genes diferencialmente expressos com recurso a dados de RNA-seq (TCGA PRAD)
- **Visualizações bioinformáticas** — heatmaps, volcano plots e outros gráficos de suporte à interpretação dos resultados

---

## 🛠️ Tecnologias e Bibliotecas

- **Python 3**
- **Jupyter Notebook**
- Bibliotecas prováveis:
  - `pandas`, `numpy` — manipulação de dados
  - `matplotlib`, `seaborn` — visualização
  - `scipy`, `statsmodels` — análise estatística
  - `sklearn` — machine learning / redução de dimensionalidade (PCA, etc.)

---

## 🚀 Como Executar

1. Clona o repositório:
   ```bash
   git clone https://github.com/andrevieira1203/IPO_internship.git
   cd IPO_internship
   ```

2. Instala as dependências (recomenda-se ambiente virtual):
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
   ```

3. Abre o notebook:
   ```bash
   jupyter notebook AnaliseEstagio.ipynb
   ```

> 📌 Para reproduzir a análise completa, é necessário obter o dataset `TCGA_PRAD_IlluminiSeq` diretamente a partir do [portal do TCGA](https://portal.gdc.cancer.gov/) e colocá-lo na raiz do projeto.

---

## 🏥 Contexto

Este trabalho foi realizado no âmbito de um estágio no **IPO — Instituto Português de Oncologia**, inserido numa linha de investigação sobre biomarcadores e alterações epigenéticas/genómicas no cancro da próstata. O estudo do tecido NAT é relevante para compreender os mecanismos de campo cancerígeno (*field cancerization*) e identificar potenciais alvos terapêuticos ou marcadores de diagnóstico precoce.

---

## 👤 Autor

**André Vieira**
[GitHub: @andrevieira1203](https://github.com/andrevieira1203)

---

## 📄 Licença

Este projeto não possui licença definida. Para utilização ou reprodução, por favor contacte o autor.
