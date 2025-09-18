# 🚢 Titanic Survival Analysis

Este projeto tem como objetivo analisar e modelar os dados do famoso desastre do Titanic, buscando entender os fatores que influenciaram a sobrevivência dos passageiros.  
O dataset utilizado é amplamente conhecido no Kaggle e contém informações sobre idade, sexo, classe social, cabine, entre outras variáveis.

---

## 📂 Estrutura do Projeto

- `titanic.ipynb` → Notebook principal com toda a análise e modelagem.
- `data/` → Pasta sugerida para armazenar os dados (`train.csv`, `test.csv`, etc).
- `README.md` → Documentação do projeto.

---

## ⚙️ Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-Learn](https://scikit-learn.org/)

---

## 📊 Etapas do Projeto

1. **Carregamento dos Dados**  
   Importação do dataset do Titanic.

2. **Análise Exploratória (EDA)**  
   - Tratamento de valores ausentes.  
   - Visualizações estatísticas (idade, sexo, classe, etc).  
   - Correlações entre variáveis.  

3. **Pré-processamento**  
   - Transformação de variáveis categóricas.  
   - Normalização/padronização (se necessário).  

4. **Modelagem Preditiva**  
   - Teste de diferentes algoritmos de machine learning.  
   - Avaliação com métricas de desempenho (acurácia, F1-score, etc).  

5. **Conclusão**  
   - Insights sobre os principais fatores que influenciaram a sobrevivência.  
   - Modelo com melhor desempenho.  

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/titanic-analysis.git
   cd titanic-analysis
Crie um ambiente virtual e instale as dependências:

bash
Copiar código
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

pip install -r requirements.txt
Abra o notebook:

bash
Copiar código
jupyter notebook titanic.ipynb

📌 Fontes

Kaggle - Titanic: Machine Learning from Disaster

✨ Autor

Projeto desenvolvido por Carlos Lacerda como parte de estudos em análise de dados e machine learning.
