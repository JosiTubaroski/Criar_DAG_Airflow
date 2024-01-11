# Criar DAG Airflow

### Estrutura de uma dag

O sinonimo de uma dag seria um workflow, e uma dag é feita em python.

Para contruir uma dag será necessário desenvolver um código python.

### Configurações - Melhore o Airflow

Como vamos criar nossas próprias dags, vamos fazer uma configuração para desabilitar as dags de exemplos.

Para isso abrir o arquivo docker-compose.yaml que está salvo no pacote do airflow.

Procurar pela linha AIRFLOW_COR_LOAD_EXAMPLES: e substituir 'true' por 'false'.

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Suibstituir_Load_Example.png">

- Após a alteração é necessário reiniciar o Airflow
- Para isso abrir o cmd e acessar o diretorio do airflow
- Parar o docker

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Docker_Down.png">

- Em seguida executar o comando Docker-compose up -d


<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Docker_UP.png">

A lista foi corretamente ajustada

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Lista_Dags.png">

As dags devem ser criadas dentro do container do docker.

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Docker_Airflow.png">

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/PrimeiraDag.png">



