Sistema de Gerenciamento de Eventos desenvolvido na PYSTACK WEEK 6.0
==========================

Este é um projeto Django que foi desenvolvido para o Gerenciamento de Eventos com acompanhamento de usuários cadastrados e geração de ingressos. Neste arquivo, você encontrará instruções detalhadas sobre como rodar este projeto em sua máquina local.

Requisitos
----------

Antes de começar, certifique-se de ter os seguintes requisitos instalados em sua máquina:

*   Python 3.x
*   Django 4.2 ou superior

Configuração do Ambiente
------------------------

Siga os passos abaixo para configurar o ambiente do projeto:

1.  Clone este repositório em sua máquina local usando o seguinte comando:

`git clone https://github.com/thiagojordao98/sistema-gerenciamento-eventos.git`

2.  Acesse o diretório do projeto:

`cd sistema-gerenciamento-eventos`

3.  Crie um ambiente virtual para isolar as dependências do projeto (opcional, mas recomendado):

No Windows:

`python -m venv venv`

No macOS/Linux:

`python3 -m venv venv`


4.  Ative o ambiente virtual (se você optou por criar um):

No Windows:

`venv\Scripts\activate`

No macOS/Linux:

`source venv/bin/activate`

5.  Instale as dependências do projeto:

`pip install -r requirements.txt`

Executando o Projeto
--------------------

Você pode rodar o projeto localmente usando o seguinte comando:

`python manage.py runserver`

Isso iniciará o servidor de desenvolvimento do Django. Você pode acessar o projeto em seu navegador em `http://localhost:8000/` .

Contribuição
------------

Se quiser contribuir para este projeto, sinta-se à vontade para enviar pull requests ou abrir issues.

Divirta-se usando o projeto Django! :)