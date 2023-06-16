# Projeto Curso de Python Impressionador da Hashtag Treinamentos - Site do Zero Utilizando flask
Este projeto foi criado a fim de mostrar a minha evolução no curso de Python Impressionador.
<br>
<br>
<br>

## Apresentação do Projeto<br>
Desenvolvi um site utilizando a linguagem Python e a biblioteca flask. Utilizei o PyCharm como ambiente de desenvolvimento.
<br>
<br>

## Importando a Biblioteca flask
Iniciamos o projeto criando um novo 'Projeto' no PyCharm. Clique em 'File" e depois em 'New Project'. Abrirá uma janela para criação do novo projeto, na qual deve ser escolhido o nome do projeto caminho da pasta para salvar o projeto.

![Captura de tela 2023-06-15 224342](https://github.com/Leticia-Souza94/Python_SiteDoZero/assets/112443902/2b253c7e-3b09-4630-a1a7-0c5aad541953)


Após criar o projeto, utilizei a pasta 'main'. O primeiro passo foi importar a biblioteca flask no terminal do PyCharm. 

![Captura de tela 2023-06-15 224627](https://github.com/Leticia-Souza94/Python_SiteDoZero/assets/112443902/9ee6fa86-f3d9-4567-9dbc-e07ed8e6ad11)

A estrutura simples do script para incicar um projeto no flask, pode ser encontrado na documentação do flask, acessando [esse link](https://flask.palletsprojects.com/en/2.3.x/quickstart/#a-minimal-application) 

'''

    from flask import Flask

    app = Flask(__name__)

    @app.route("/")
    def hello_world():
        return "<p>Hello, World!</p>"
'''


# ...EM CONSTRUÇÃO...
