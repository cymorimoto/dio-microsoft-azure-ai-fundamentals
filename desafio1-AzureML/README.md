# Trabalhando com Machine Learning na Prática no Azure ML
1. Acessar o portal da Azure (com uma conta/subscrição): https://portal.azure.com/ 
2. Criar grupo de recursos
3. Acessar os serviços e aprendizado de máquina no "Azure Machine Learning" (buscar pelo portal Azure)
4. Acessar o Azure Machine Learning studio: https://ml.azure.com/
5. Criar um trabalho de ML automatizado
   - Escolher o tipo de tarefa (Regressão)
   - Criar ativo de dados (configuração e formatação)
   - Configurar a tarefa
   - Executar a tarefa
6. Deploy e teste do modelo
   
## Teste do Modelo
  ```{
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }
```
## Saída
A previsão gerada foi: 352,29

## Referências
Passo a passo do laboratório: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html
Conceitos de endpoint: https://learn.microsoft.com/pt-br/azure/machine-learning/concept-endpoints?view=azureml-api-2
