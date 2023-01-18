# Clustering k-means, DBSCAN e mean shift

Neste curso, vamos:

- Conhecer o básico sobre análise exploratória;
- Criar visualização de dados utilizando a biblioteca plotly;
- Utilizar o método K-means, DBSCAN e Mean shift para agrupar dados sem classificação;
- Aprender a agrupar vinhos;
- Avaliar a qualidade de uma clusterização através da utilização do coeficiente de silhueta;
- Parametrizar métodos de clusterização através do máximo coeficiente de silhueta;

## Dataset

## Ambiente de desenvolvimento

1. Criar e ativar o ambiente virtual.

   - É muito importante que o ambiente virtual seja salvo em uma pasta com um nome DIFERENTE de .env. Uma sugestão é .venv.

    ```shell
    conda create -p .venv python=3.9.7
    ```

    - Ativando o ambiente virtual.

    ```shell
    conda activate ../.venv
    ```

2. Ativando o terminal python.

    ```shell
    python
    ```

Pronto! o ambiente está pronto!!!

## Requerimentos extras

- Instalar pacotes no projeto
  - Basta colocar no arquivo 'requeriments.txt' o nome do pacote quer instalar

    ```python
    pip install -r requirements.txt
    ```