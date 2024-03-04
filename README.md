# Django

#####


#### Como iniciar?
>OBS: A ideia é criar um ambiente para usar o django e antes de qualquer alteração acessar esse ambiente com o comando abaixo.
```shell
.\env\scripts\activate
```
1. **Configurar o ambiente**
    1. Instalar o virtualenv:
        ```shell
        pip install virtualenv
        ```
    1. Configurar o env: 
    ```shell
        py -m venv <nome do ambiente>
    ```
    1. Ativar o script do env:
     ```shell
        \<nome do ambiente>\scripts\activate
    ```
    > Obs: use a barra invertida msm

1. **Configurar o Django**
    1. Instalar o Django
    ```shell
        pip install django
    ```
    2. Criar o projeto django
    ```shell
        django-adm startproject <nome do projeto>
    ```
    3. Criar uma aplicação
    ```shell
        py manage.py startapp <nome do app>
    ```
1. **Migrate ( tabelas )**
    1. Migrate
    ```shell
        py manage.py migrate
    ```
1. **Criando super usuário**
    1. Super usuário
    ```shell
        py manage.py createsuperuser
    ```
   
#### Padrões do DJANGO
- Banco padrão: **SQLITE3**

#### Conceitos
**Projeto** VS **aplicação**
* Projeto:
    Padrão do django, é possível ter vários apps ( Tronco )
* App: 
    ( Galhos ) 

#### Funções de cada arquivo
* **manage.py**:  gerenciador de arquivos



