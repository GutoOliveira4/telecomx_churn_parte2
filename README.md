TelecomX – Parte 2: Prevendo Churn
📖 Descrição
Este projeto faz parte do desafio de Data Science da Telecom X.
O objetivo é construir um pipeline de Machine Learning para prever a evasão de clientes (churn), utilizando dados demográficos, serviços contratados e informações de faturamento.

🎯 Objetivos
Preparar e tratar os dados para modelagem.

Realizar análise exploratória e correlação entre variáveis.

Treinar e avaliar modelos de classificação (Logistic Regression, Random Forest, XGBoost).

Interpretar os resultados e identificar os principais fatores que influenciam a evasão.

Elaborar relatório final com conclusões e recomendações estratégicas.

📂 Estrutura do Repositório

telecomx_churn_parte2/
│
├── data/                # Dados brutos e tratados
│   ├── TelecomX_Data.json
│   └── TelecomX_Parte2_DadosTratados.csv
│
├── notebooks/           # Notebook principal
│   └── TelecomX_Churn_Parte2.ipynb
│
├── reports/             # Relatórios e imagens
│   ├── Relatorio_TelecomX_Parte2.md
│   └── gráficos (.png)
│
└── README.md            # Documentação inicial

🚀 Tecnologias Utilizadas
Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn

Google Colab para execução dos notebooks

GitHub para versionamento e organização do projeto

📊 Principais Insights
Cerca de 27% dos clientes cancelaram o serviço.

Clientes com menos meses de contrato tendem a evadir.

Cobranças mensais mais altas estão associadas à evasão.

Forma de pagamento (especialmente débito automático) e tipo de contrato influenciam fortemente o churn.

💡 Recomendações Estratégicas
Campanhas de retenção nos primeiros meses de contrato.

Revisão de preços e planos para clientes com cobrança mensal elevada.

Estimular uso de serviços adicionais (streaming, suporte técnico).

Incentivar contratos mais longos para reduzir evasão.

Abra o notebook notebooks/TelecomX_Churn_Parte2.ipynb no Google Colab.

Certifique-se de que o dataset data/TelecomX_Data.json está disponível.

Execute todas as células para reproduzir a análise e os modelos.

Os relatórios e gráficos serão salvos na pasta reports/.

📄 Relatório Final
O relatório completo com conclusões e recomendações está disponível em:
reports/Relatorio_TelecomX_Parte2.md
