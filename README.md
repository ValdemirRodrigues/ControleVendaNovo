# ControleVendaNovo
 Controla Vendas 
 Segue a lista de tarefas a serem desenvolvidas no projeto:
- [X] Pré-requisitos
    - [X] Instalar o Python
    - [X] Instalar Visual Studio Code
- [X] Pré-requisitos
    - [X] Instalar o Python
    - [X] Instalar Visual Studio Code
- [X] Criar e ativar o ambiente virtual
```
 python -m venv .\venv\
    venv\Scripts\activate 
```
- [X] Inatalar Django
```
    python -m pip install django==3.2
```
- [X] Criar o projeto Controle_Venda_Project
```
    django-admin.py startproject Controle_Venda_VCR_Project
```
- [X] Subir o servidor e testar o projeto
```
    abrir pasta projeto
        cd Controlevendaproject
    executtar projeto no servidor
        python manager.py runserver

```
- [X] Alterar o idioma do projeto `pt-br`
    - Abrir o arquivo settings.py e na linha 106 LANGUAGE_CODE = `en-us` alterar para `pt-br`
- [X] Alterear timexone do projeto para `America/Sao_Paulo`
    - Abrir o arquivo settings.py e na linha 108 TIME_ZONE = 'America/Sao_Paulo'
- [] Criar o APP Controle_de_Vendas
- [] Registrar o APP
- [] Configurar rota Inicial (index)
- [] Criar a view para a rota inicial 
- [] Cria o  arquivo index.html
