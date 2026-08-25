# Python Insights: Análise de Cancelamento de Clientes (Churn)

Projeto de Análise Exploratória de Dados (EDA) desenvolvido em Python para identificar os fatores determinantes no cancelamento de contratos de uma base de aproximadamente 50 mil clientes. O objetivo principal é extrair insights estratégicos para orientar ações de retenção e redução do índice de churn.

Projeto desenvolvido como estudo prático durante a **Jornada Python**, promovida pela **Hashtag Programação**.

---

## Contexto e Objetivos

A perda contínua de clientes impacta diretamente a receita e a sustentabilidade de um negócio. Esta análise foi estruturada para responder às seguintes questões:

- Quais padrões comportamentais caracterizam os clientes que cancelam os serviços?
- Quais variáveis operacionais e financeiras possuem maior correlação com a taxa de cancelamento?
- Quais medidas estratégicas podem ser tomadas para diminuir o churn de forma imediata?

---

## Tecnologias Utilizadas

- **Linguagem:** Python 3.x
- **Manipulação e Tratamento de Dados:** Pandas
- **Visualização Gráfica Interativa:** Plotly Express
- **Ambiente de Desenvolvimento:** Jupyter Notebook

---

## Estrutura do Repositório

```text
├── .gitignore          # Especificação de arquivos ignorados no controle de versão
├── cancelamentos.csv   # Base de dados histórica para análise
├── inicial.ipynb       # Notebook principal com o desenvolvimento e gráficos
├── gabarito.ipynb      # Notebook de referência com o código completo
└── README.md           # Documentação do projeto
```

---

## Etapas da Análise

1. **Carregamento e Inspeção:** Leitura do arquivo de dados e eliminação de colunas irrelevantes (ex: identificadores de cliente).
2. **Tratamento de Dados:** Identificação e remoção de registros nulos ou inconsistentes para evitar contaminação nas métricas estatísticas.
3. **Mapeamento do Churn Geral:** Cálculo da taxa global de cancelamentos para definição do parâmetro de controle.
4. **Análise Exploratória de Dados (EDA):** Criação de histogramas comparativos para analisar o comportamento de cada variável em relação ao cancelamento.
5. **Síntese de Diagnósticos:** Identificação de gargalos operacionais e padrões críticos na jornada do cliente.

---

## Principais Insights Encontrados

- **Atendimento ao Cliente:** Clientes com mais de 4 acionamentos ao suporte/call center apresentam taxa de cancelamento próxima de 100%.
- **Atraso de Pagamento:** Clientes com pendências financeiras superiores a 20 dias tendem a cancelar os serviços massivamente.
- **Modalidade de Contrato:** O modelo de assinatura mensal é o principal gerador de churn se comparado aos planos anuais ou trimestrais.

---

## Como Executar o Projeto

### Pré-requisitos

- **Python 3.8+** instalado.
- **Jupyter Notebook** ou extensão do Jupyter no VS Code.

### Instruções

1. Clone este repositório:
   ```bash
   git clone https://github.com/barbcarol-dev/python-insights-analise-dados.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd python-insights-analise-dados
   ```

3. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas plotly jupyter
   ```

4. Execute o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   - Abra o arquivo `inicial.ipynb` para navegar pelos dados, gerar as visualizações gráficos e conferir as conclusões da análise.

---

## Autora

**Bárbara Caroline**  
Estudante de Programação, Python e Análise de Dados.
