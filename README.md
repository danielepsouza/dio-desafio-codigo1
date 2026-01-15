# 📊 ETL de Consumo de Energia Elétrica

Projeto de ETL (Extract, Transform, Load) desenvolvido em Python com Pandas,
simulando o processamento de medições mensais de consumo de energia elétrica
de clientes de uma concessionária.

---

## 🧩 Estrutura do Projeto

```text
.
├── data
│   ├── raw               # Dados brutos (entrada)
│   ├── processado        # Dados tratados (gerados pelo ETL)
│   └── saida             # Dados finais para consumo
├── notebooks
│   └── 01_etl_consumo_mensal_energia.ipynb
├── venv                  # Ambiente virtual (ignorado)
├── .gitignore
├── README.md
└── LICENSE
```


## 🚀 Como Executar o Projeto Localmente

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/danielepsouza/dio-desafio-codigo1.git
cd dio-desafio-codigo1
```

### 2️⃣ Criar e ativar o ambiente virtual

```bash
python -m venv venv
source venv/Scripts/activate
```

### 3️⃣ Instalar dependências
```bash
pip install notebook pandas
```

### 4️⃣ Abrir o Jupyter Notebook
```bash
jupyter notebook
```
#### Abra o arquivo: 
```bash
notebooks/01_etl_consumo_mensal_energia.ipynb
```

### 5️⃣ O que fazer após a execução
- Interromper o notebook:
  
```bash
Pressione ctrl + c no seu teclado
```

- Desativar o ambiente virtual:
```bash
deactivated
```
- Verificar os dados gerados nas pastas data/saida

## 📥 Dados de Entrada
Este é o arquivo CSV contendo medições mensais de consumo de energia.
```bash
data/raw/consumo_mensal.csv
```

## 📤 Dados Gerados:
Ao executar o notebook, o ETL gera:
```bash
- data/processado/consumo_tratado.csv
- data/saida/consumo_final_formatado.csv
- data/saida/resumo_clientes.csv
```

## 🛠 Tecnologias Utilizadas
- Python
- Pandas
- Jupyter Notebook
- Git / GitHub

## 📌 Observações
O notebook pode ser visualizado diretamente no GitHub.
Para executar o ETL, é necessário rodar o notebook localmente.










