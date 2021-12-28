# AzureDevOps-Postman-Newman-WorkItems-AzureFunctions-DotNet6_JurosCompostos
Pipeline do Azure DevOps para automação de testes (com Postman + Newman), build e deployment de uma Function App (Http Trigger + Azure Functions + Isolated Process) criada com .NET 6. Inclui a criação de Work Items no Azure Boards, caso os testes falhem, além da geração de relatório HTML com o resultados dos testes.

Projeto que serviu de base para a implementação deste Pipeline:

https://github.com/renatogroffe/DotNet6-AzureFunctions-Isolated-HttpTrigger-Postman_JurosCompostos

Task/Extensão para criação de Work Items:

https://marketplace.visualstudio.com/items?itemName=mspremier.CreateWorkItem