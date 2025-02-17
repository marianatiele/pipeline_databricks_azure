<h1 align="center">  Orquestrando Pipeline de dados na Databricks </h1>


## [Descrição do Projeto](#descrição-do-projeto)
  
Este projeto consiste em um pipeline de dados estruturado conforme a arquitetura Medallion. O fluxo percorre desde a camada Bronze até a Silver, enquanto a camada Gold foi ignorada por enquanto.

## [Status do Projeto](#status-do-Projeto)

  > :construction: Projeto em construção :construction:
  
## [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
Para sua implementação, foram utilizadas as seguintes tecnologias: Azure Data Lake Gen2, Azure Data Factory, Databricks e GitHub.
No Azure Data Lake Gen2, foram armazenados tanto os dados brutos quanto os dados processados. No Databricks, desenvolvi notebooks em Scala para realizar o tratamento dos dados. Já no Azure Data Factory, orquestrei a execução desses notebooks e configurei triggers para processar os dados automaticamente a cada hora.


  

## [Tecnologias utilizadas](#tecnologias-utilizadas)
  * Data Lake Gan 2 Azure
  * Databricks
  * Data Factory
  * Scala
  * Github
    


## [Referencias](#referencias)

Arquitetura medalion: https://learn.microsoft.com/pt-br/azure/databricks/lakehouse/medallion

Data Lake: https://learn.microsoft.com/en-us/azure/databricks/connect/storage/tutorial-azure-storage

Data Factory: https://learn.microsoft.com/pt-br/azure/data-factory/introduction

