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

Código da primeira dag

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Primeira_Dag_Codigo.png">

- Após a criação da Dag, atualizar o airflow

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Atualizar_Airflow.png">

- A dag será apresentada, selecionar a dag para verificar a estrutura.

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Apresentacao_Dag.png">

- Verificar em modo Graph para observar a sequencia das atividades.

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/sequencia_tasks.png">

- Realizar a execução da Dag utilizando a opção "Trigger Dag"

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Executar_Dag.png">

- A borda da DAG apresenta a cor do status em que a atividade se encontra.

Exemplo:

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Status_Dag.png">

- Apresentacao Grantt com resultado de execução

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/Apresentacao_Grant_Exec.png">

- Para verificar os logs das tasks, retornar para o modo grafico e selecionar a task, em seguida a opção log

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Selecionar_Task_Execute.png">

<img src="https://github.com/JosiTubaroski/Criar_DAG_Airflow/blob/main/img/Log_Execucao.png">


  

  

  





