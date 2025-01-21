# AzureIA_CognitiveSeach_ConfigResource
Objetivo é configurar o Recurso Repositorio onde será salvo nosso projeto, modelo, teste etc...


### Ferramentas utilizadas:

- Portal Azure: https://portal.azure.com/#home

### Pontos Importantes:

- Caso esteja realizando apenas um prática de estudo, no final excluir tudo que foi construído nesse laboratório. Desta forma, minimiza o risco de ser cobrado algum valor. Lembre-se você está em um ambiente real de produção.
- Documentação:
    + https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

### Resumo (Passo-a-passo): Configuração:

- Entrar no ambiente Azure
- Criar o serviço: "AI Search"
- Criar serviço: Azure AI services


### Detalhamento (Passo-a-passo): Configuração

01 - Selecionar o recurso ``` AI Search  ``` e no botão ``` Create  ``` 
![image](https://github.com/user-attachments/assets/2549278d-5252-4a0b-8581-f1d2d88746bd)

02 - Iniciar a configuração criando o repositório onde será salvo nosso projeto, modelo, laboratório. Fique a vontade para chamar do melhor padrão para sua necessidade.
   * Subscription: é a conta que você está logado. É como se você a sua empresa. Repositótorio geral de tudo que é criado, a Pasta principal. Já vem preenchido de padrão, Esse padrão é criado automaticamente quando realiza o cadastro. Mas pode ser criado outras opções.
   * Resource group: é uma sub-repositório do "Subscription".
Imagina uma gaveteiro onde o gaveteiro inteiro é Subscriptiom e uma gaveta desse gaveteiro é o Resource group.
   * Service Name: nome do seu projeto, modelo (Deve ser único)
   * Pricing tier: Selecionar a forma de cobrança. No item:  ``` Change Pricing Tier  ```, você seleciona a configuração desejavel. No nosso caso, vamos selecionar opção ``` Basic ```. 
![image](https://github.com/user-attachments/assets/bc2112c3-efb0-4cdf-ba8d-333e39c17feb)

03 - Demais Abas: vamos manter o padrão, pois estamos realizando uma configuração basica e iremos excluir esse modelo no final. Então, click no botão ``` Review + create ``` para validar as configurações e depois click novamente no botão ``` Create ``` 
   * Scale: resumo do método da cobrança e pode selecionar quantas de partições e reblicas gostaria.
   * Networking: configuração de privacidade do seu modelo(Publico/Privado)
   * Tags: muito usado para criar filtros. Por exemplo: Quero fazer rateio para lançamento de custo por Departamento, então, cria as tags por departamento. Conforme sua necessidade.
![image](https://github.com/user-attachments/assets/378fe24e-6509-4a50-bd82-daf94c239c3b)

04 - Voltar para tela principal do Azure e selecionar o recurso ``` Azure AI services  ```. Link abaixo demostrando como configurar esse SERVIÇO.

https://github.com/WanderBernardo/AzureIA_ServiceAzureAIservices

05 - 
