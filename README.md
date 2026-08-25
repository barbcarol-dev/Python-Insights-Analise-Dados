📊 Python Insights — Análise de Cancelamento de Clientes
Projeto de análise de dados com Python focado em entender os principais fatores que levam ao cancelamento de clientes (churn) em uma base com aproximadamente 50 mil registros.

📚 Projeto de estudos desenvolvido pela hashtag programação, durante a Jornada Python.

🧠 Contexto do Projeto
Uma empresa com mais de 800 mil clientes identificou que grande parte de sua base está inativa, ou seja, clientes que já cancelaram o serviço.
O objetivo deste projeto é:

Identificar padrões de comportamento dos clientes que cancelam
Entender quais variáveis mais impactam o churn
Gerar insights acionáveis para reduzir o número de cancelamentos

🎯 Objetivos da Análise
Realizar limpeza e tratamento de dados
Explorar estatísticas básicas da base
Analisar a taxa de cancelamento
Avaliar como cada variável influencia o churn
Criar visualizações para apoiar a tomada de decisão

🛠️ Tecnologias Utilizadas
Python
Pandas
Plotly
Jupyter Notebook
Análise Exploratória de Dados (EDA)

📁 Estrutura do Projeto

📦 python-insights
├── inicial.ipynb        # Notebook principal com a análise
├── gabarito.ipynb       # Notebook de referência
├── cancelamentos.csv    # Base de dados
└── README.md            # Documentação do projeto
🔍 Etapas da Análise

1️⃣ Abertura e Visualização da Base
Leitura do arquivo CSV
Remoção de colunas irrelevantes (ex: CustomerID)
Visualização inicial da base

2️⃣ Análise da Estrutura dos Dados
Tipos de dados
Valores nulos
Tamanho da base e consumo de memória

3️⃣ Tratamento de Dados
Remoção de registros com valores nulos
Garantia de consistência para análise

4️⃣ Análise Inicial do Cancelamento
Contagem de clientes que cancelaram vs. ativos
Cálculo da porcentagem de churn

5️⃣ Análise Detalhada (EDA)
Análise do impacto de cada variável no cancelamento
Criação de histogramas comparando clientes que cancelaram e não cancelaram
Identificação de padrões comportamentais

📈 Principais Insights (exemplos)
Clientes com maior número de ligações ao call center apresentam maior taxa de cancelamento
Dias em atraso influenciam diretamente o churn
Tipo de assinatura e frequência de uso impactam no comportamento do cliente
Clientes com menor engajamento tendem a cancelar mais rapidamente

⚠️ Os insights completos podem ser visualizados diretamente no notebook.

🚀 Como Executar o Projeto
1. Clone o repositório
git clone https://github.com/barbcarol-dev/Python-Insights-Analise-Dados.git
2. Acesse a pasta
cd python-insights
3. Instale as dependências
pip install pandas plotly jupyter
4. Execute o notebook
jupyter notebook
Abra o arquivo inicial.ipynb.

📚 Contexto Educacional
(Projeto desenvolvido como estudo prático de Análise de Dados com Python, durante a
Jornada Python, promovida pela hashtag programação.)

👩‍💻 Autora
Bárbara Caroline
(Estudante de Programação | Python | Análise de Dados)

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!                                      o que acha desse readme que eu fiz?
