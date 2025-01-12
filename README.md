# Real-Time Data Pipeline for Stock Market Monitoring (Open Source)

## 📋 Description

This project develops a real-time data pipeline for stock market monitoring using exclusively **open source** tools. The system captures stock market data such as prices, volumes, and other financial indicators, processes and stores the information, making it accessible for analysis and interactive visualization. This open-source approach ensures greater flexibility and accessibility.

---

## 🛠️ Project Stages

### 1. **Data Collection**
- **Data Source**: Use free APIs like [Alpha Vantage](https://www.alphavantage.co/) or [Yahoo Finance API](https://finance.yahoo.com/).
- **Ingestion**: Set up real-time data ingestion with **Apache Kafka**.
- **Security**: Secure API keys using configuration files and manage request limits.

---

### 2. **Processing and Transformation**
- **Streaming**: Implement real-time data processing using **Apache Spark Streaming** or **Apache Flink**.
- **Data Cleaning**: Standardize formats, handle missing values, and correct inconsistencies.
- **Data Enrichment**: Compute technical indicators using Python libraries such as:
  - **TA-Lib** (Technical Analysis Library)
  - **Pandas** for data manipulation.

---

### 3. **Storage**
- **Real-Time Database**: Use **Apache Cassandra** or **PostgreSQL** with the **TimescaleDB** extension.
- **Data Lake**: Use **MinIO** as an open-source alternative for raw data storage.
- **Partitioning**: Structure data by time or symbol to optimize queries.

---

### 4. **Visualization and Analysis**
- **Dashboards**: Build interactive dashboards using **Apache Superset** or **Metabase**.
- **Alerts**: Configure automated notifications using **Apache NiFi** or **Prometheus Alertmanager**.
- **Reports**: Generate reports with Python libraries such as **Matplotlib** and **Seaborn** for custom visualizations.

---

## 🛠️ Technologies and Tools

| **Category**            | **Technology/Tool**                                        |
|-------------------------|------------------------------------------------------------|
| Programming Languages    | Python (pandas, NumPy, TA-Lib), Scala                     |
| Streaming Frameworks     | Apache Kafka, Apache Spark Streaming, Apache Flink        |
| Databases                | Apache Cassandra, PostgreSQL (TimescaleDB)                |
| Visualization Tools      | Apache Superset, Metabase                                 |
| Data Lake                | MinIO                                                     |
| Other Tools              | Prometheus, Apache NiFi                                   |

---

## ⚠️ Challenges and Considerations

- **Latency**: Ensure low latency throughout the pipeline.
- **Scalability**: Configure the system to handle increasing data volumes efficiently.
- **Reliability**: Implement fault-tolerance with backups and replication.

---

## 📊 Expected Outcomes

- **Continuous Monitoring**: Real-time financial data available for analysis.
- **Interactive Visualizations**: Customizable dashboards to display trends and patterns.
- **High-Quality Insights**: Clean and enriched data for deeper analysis.

---

## 🚀 How to Run

### Prerequisites
1. Install the required dependencies listed in `requirements.txt`.
2. Configure Kafka and Cassandra/PostgreSQL using the provided setup scripts.
3. Set environment variables for API keys and ingestion parameters.
4. Run the pipeline by following the commands in the main project directory.

---

## 🤝 Contributions

Contributions are welcome! 🎉 If you encounter any issues, have suggestions for improvements, or want to add new features, feel free to open an [issue](#) or submit a [pull request](#).

---

**PT-BR**
# Pipeline de Dados em Tempo Real para Monitoramento do Mercado de Ações (Open Source)

## 📋 Descrição

Este projeto desenvolve um pipeline de dados em tempo real para monitorar o mercado de ações, utilizando exclusivamente ferramentas **open source**. O sistema captura dados de preços, volumes e outros indicadores financeiros, processa e armazena as informações, disponibilizando-as para análise e visualização interativa. Com esta abordagem, garantimos maior acessibilidade e flexibilidade na implementação.

---

## 🛠️ Etapas do Projeto

### 1. **Coleta de Dados**
- **Fonte de Dados**: Utilizar [Yahoo Finance API](https://finance.yahoo.com/).
- **Ingestão**: Configurar ingestão de dados em tempo real com **Apache Kafka**.
- **Segurança**: Proteger chaves de API com arquivos de configuração e limitar o número de requisições.

---

### 2. **Processamento e Transformação**
- **Streaming**: Implementar processamento em tempo real utilizando **Apache Spark Streaming** ou **Apache Flink**.
- **Limpeza de Dados**: Padronizar formatos, tratar valores ausentes e corrigir inconsistências.
- **Enriquecimento**: Calcular indicadores técnicos com bibliotecas Python, como:
- **Pandas** para manipulação de dados.
- **PySpark** para manipulação de dados.

---

### 3. **Armazenamento**
- **Banco de Dados em Tempo Real**: Utilizar **Apache Cassandra** ou **PostgreSQL** com extensão **TimescaleDB**.
- **Data Lake**: Utilizar **MinIO** como alternativa open source ao armazenamento de dados brutos.
- **Particionamento**: Estruturar os dados por data e hora.

---

### 4. **Visualização e Análise**
- **Dashboards**: Construir painéis interativos com **Apache Superset**.
- **Alertas**: Configurar notificações automáticas com **Prometheus Alertmanager**.
- **Relatórios**: Gerar relatórios com bibliotecas Python como **Matplotlib** e **Seaborn** para visualização personalizada.

---

## 🛠️ Tecnologias e Ferramentas

| **Categoria**          | **Tecnologia/Ferramenta**                                   |
|-------------------------|------------------------------------------------------------|
| Linguagens de Programação | Python (pandas, NumPy, Spark ), SQL                    |
| Frameworks de Streaming | Apache Kafka, Apache Spark Streaming, Apache Flink        |
| Bancos de Dados         | Apache Cassandra, PostgreSQL                |
| Ferramentas de Visualização | Apache Superset                              |
| Data Lake               | MinIO                                                     |
| Outras Ferramentas      | Prometheus, Airflow, Iceberg                                   |

---

## ⚠️ Desafios e Considerações

- **Latência**: Garantir baixa latência em todo o pipeline.
- **Escalabilidade**: Configurar o sistema para suportar aumento no volume de dados.
- **Confiabilidade**: Implementar tolerância a falhas com backups e replicação.

---

## 📊 Resultados Esperados

- **Monitoramento Contínuo**: Dados financeiros em tempo real disponíveis para análises.
- **Visualizações Interativas**: Dashboards configuráveis para exibir tendências e padrões.
- **Insights de Qualidade**: Dados limpos e enriquecidos para análises aprofundadas.

---

## 🚀 Como Executar

### Pré-requisitos
1. Instale as dependências necessárias listadas no `requirements.txt`.
2. Configure o Kafka e o Cassandra/PostgreSQL com os scripts fornecidos no repositório.
3. Configure as variáveis de ambiente para chaves de API e parâmetros de ingestão.
4. Execute o pipeline seguindo os comandos disponíveis no diretório principal.

---

## 🤝 Contribuições

Contribuições são bem-vindas! 🎉 Se você encontrar algum problema, quiser sugerir melhorias ou adicionar funcionalidades, abra uma [issue](#) ou envie um [pull request](#).
