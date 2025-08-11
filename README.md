# 📊 Dashboard de Salários na Área de Dados

Este projeto é um **dashboard interativo** desenvolvido com [Streamlit](https://streamlit.io/) e [Plotly](https://plotly.com/) para **analisar salários na área de dados** ao longo dos anos.  
O sistema permite aplicar filtros, visualizar métricas-chave e explorar gráficos interativos sobre cargos, contratos, tamanhos de empresa, tipos de trabalho e distribuição salarial.

---

## 🚀 Funcionalidades

- **Filtros Interativos**
  - Ano
  - Senioridade
  - Tipo de contrato
  - Tamanho da empresa

- **KPIs (Indicadores Principais)**
  - Salário médio
  - Salário máximo
  - Total de registros filtrados
  - Cargo mais frequente

- **Visualizações**
  - **Top 10 cargos** por salário médio
  - **Distribuição de salários** em histograma
  - **Proporção de trabalho remoto/híbrido/presencial**
  - **Mapa mundial** com salário médio de Cientistas de Dados por país

- **Tabela detalhada** dos dados filtrados

---

## 🛠️ Tecnologias Utilizadas

- **Python** 3.8+
- **[Streamlit](https://streamlit.io/)** – Framework para dashboards interativos
- **[Pandas](https://pandas.pydata.org/)** – Manipulação e análise de dados
- **[Plotly Express](https://plotly.com/python/plotly-express/)** – Criação de gráficos interativos

---

## 📦 Instalação

Clone o repositório:


git clone https://github.com/seuusuario/dashboard-salarios.git
cd dashboard-salarios
Crie e ative um ambiente virtual (opcional, mas recomendado):


python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
Instale as dependências:


pip install -r requirements.txt
Se não existir um requirements.txt, instale manualmente:


pip install streamlit pandas plotly
▶️ Como Executar
No terminal, execute:


streamlit run app.py
O Streamlit abrirá automaticamente no navegador em:


http://localhost:8501
📂 Estrutura do Projeto


├── app.py                # Código principal do dashboard
├── README.md             # Documentação do projeto
├── requirements.txt      # Dependências do projeto
📊 Fonte dos Dados
O dataset utilizado está hospedado no GitHub:


df = pd.read_csv("dados-imersao-final.csv")

Colunas principais:

ano – Ano da coleta do dado

cargo – Nome do cargo

senioridade – Nível de experiência

contrato – Tipo de contrato

tamanho_empresa – Porte da empresa

usd – Salário anual em dólares

remoto – Tipo de trabalho (remoto, híbrido, presencial)

residencia_iso3 – Código ISO do país de residência

✍🏼 Feito por Luis Gustavo — Analista de Dados
