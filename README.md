# Projeto-de-Bloco-Big-Data-2025
Projeto de Bloco de Big Data da Graduação em Ciência de Dados - Instituto INFNET

# Data Lake com Arquitetura Lambda
![videogames](https://github.com/user-attachments/assets/40027e9c-d885-46e9-b008-f47f40ff6703)
Este projeto de Data Lake em arquitetura Lambda foi desenvolvido com o objetivo de realizar análises integradas entre dados históricos de vendas de videogames e dados atuais de visualizações de jogos na plataforma Twitch.tv. A camada batch do sistema é responsável por processar dados estáticos provenientes de um dataset contendo informações de títulos com mais de 100.000 unidades vendidas até o ano de 2020. Já a camada speed realiza a ingestão e processamento contínuo de dados obtidos em tempo real via API da Twitch, permitindo o monitoramento dinâmico da popularidade dos jogos junto à comunidade de espectadores de livestreams.

A solução proposta visa identificar possíveis correlações entre o desempenho comercial dos jogos ao longo dos anos e seu nível atual de engajamento nas plataformas digitais, oferecendo suporte a análises preditivas, estratégias de marketing e decisões de negócio no setor de games. O uso da arquitetura Lambda proporciona escalabilidade, flexibilidade e a capacidade de lidar com diferentes velocidades e formatos de dados, assegurando um ambiente robusto para o tratamento e análise de grandes volumes de informação.

## Tecnologia
Tecnologias usadas no desenvolvimento deste projeto:
- Azure
- Azure Data Factory
- Databricks Notebooks
- Python
- Apache Spark

## Arquitetura proposta
![Datalake_Matheus drawio](https://github.com/user-attachments/assets/d8ee3c89-1d9e-4dcf-97ac-905d0a80e94b)



## Utilizando o projeto
- Crie uma Storage Account na sua conta da Azure
- Utilize os Arm Templates incluídos na pasta IaC
- Crie um arquivo '.env' com as credenciais da API da Twitch.tv como citado neste [Link](https://dev.twitch.tv/docs/authentication/)
