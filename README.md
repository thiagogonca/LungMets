# Notebooks
Notebooks para Introdução a Pesquisa.

# Recomendações
- Python 3.10.4;
- Instalar bibliotecas necessárias em `requirements.txt`;
- Utilize ambiente virtual `vitualenv`.

## Instruções
Tutorial para preparar o ambiente e executar os notebooks.

### Linux
- Instale o `virtualenv`;
    ```bash
    pip install virtualenv
    ```
- Crie um ambiente virtual;
    ```bash
    virtualenv -p python3.10 AC4UFPR 
    ```
- Ative o ambiente virtual;
    ```bash
    source AC4UFPR/bin/activate
    ```
- Instale requirimentos do repositório
    ```bash
    pip install -r path/to/requirements.txt
    ```
    note que se 
- Adicionar ambiente no Jupyter,
    ```bash
    python -m ipykernel install --user --name=AC4UFPR
    ```
- Verifique que a presença do kernel no jupyter
    ```bash
    jupyter-kernelspec list
    ```
    deve aparecer o kernel que criou.
