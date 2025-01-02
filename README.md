<div> 
<p><a href="https://github.com/JosiTubaroski/Introducao_Engenharia_Dados/blob/main/README.md">Introdução a Engenharia de Dados</a></p>
</div> 

# Análise de Dados de Vendas Globais com Microsoft Azure

## Cenário:

Uma empresa multinacional de varejo precisa analisar grandes volumes de dados de vendas gerados diariamente em diferentes regiões do mundo. Os dados incluem:

- Transação de ponto de venda (POS).
- Informações de inventário.
- Dados de clientes e promoções.
- Tendencias de mercado em diferentes regiões.

A análise precisa ser escalável, em tempo quase real, e oferecer insights detalhados para ajudar na tomada de decisões estratégicas, como otimização de estoque e definição de preços.

## Objetivo:

Criar um pipeline robusto de processamento de Big Data utilizando ferramentas do Microsoft Azure, integrando dados em tempo real e históricos para fornecer relatórios dinâmicos e insights preditivos.

## Arquitetura e Ferramentas Utilizadas:

1. Azure Event Hubs: Ingestão de dados em tempo real.
2. Azure Data Factory: Orquestração de pipelines de ETL/ELT
3. Azure Databricks: Processamento de dados em grande escala.
4. Azure Synapse Analytics: Análise e consulta de dados estruturados e semiestruturados.
5. Azure Machine Learning: Modelagem preditiva e análise avançada.
6. Power BI: Visualização de dados e relatórios interativos.

## Passo a Passo:

1. Ingestão de Dados com Azure Event Hubs

   - Os dados de vendas em tempo real de sistemas POS, APIs externas IoT são enviados para o Azure Event Hubs, que atua como um barramento de mensagens de alta taxa de transferência.
   - Exemplo de mensagem JSON enviada para o Event Hub:
  
      <img src="https://github.com/JosiTubaroski/Processo_Dados_Microsoft/blob/main/img/01_Azure_JSON.png">
     
