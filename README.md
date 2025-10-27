# CP5 – Modelo de Classificação com IA (Classificação de Câncer de Mama - UCI/Scikit-Learn)

## 📌 Problema
Classificar tumores como **Malignos** ou **Benignos** (classificação binária) usando medidas numéricas extraídas de imagens.

## 🎯 Justificativa
Apoio à decisão clínica em um tema de alta relevância. Dataset clássico e bem documentado, ideal para prática acadêmica com reprodutibilidade.

## 🗂️ Dataset
- **Nome:** Breast Cancer Wisconsin (Diagnostic)
- **Fonte:** UCI Machine Learning Repository (via scikit-learn)
- **Link (referência):** https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+original
- **Acesso:** `sklearn.datasets.load_breast_cancer()`
- **Tamanho:** 569 amostras, 30 features numéricas + alvo binário

## 🧪 Pipeline
1. Definição do problema e justificativa
2. Descrição do dataset (origem, tamanho, variáveis)
3. Pré-processamento: verificação de ausentes, checagem simples de outliers, padronização quando aplicável
4. Modelagem: Logistic Regression, LDA, RandomForest, KNN (≥3 exigidos)
5. Avaliação: Acurácia, Precisão, Recall, F1, Matrizes de Confusão
6. Interpretação e Conclusão (modelo escolhido + melhorias futuras)

## 🛠️ Requisitos
- Python 3.10+
- pandas, numpy, scikit-learn, matplotlib

## ▶️ Como executar no Google Colab
- Abra o arquivo `.ipynb` no Colab e rode as células em sequência.
- Justifique o **modelo final** com base no **F1-Score** e demais métricas.

## 📈 Resultados (resumo)
- Os resultados podem variar, mas tipicamente **LDA** e **Regressão Logística** apresentam F1 elevado neste dataset; **RandomForest** também costuma performar muito bem.
- Veja a **tabela comparativa** e as **matrizes de confusão** no notebook.

## 📚 Referências
- UCI ML Repository – Breast Cancer Wisconsin (Diagnostic)
- Scikit-Learn: documentação oficial
