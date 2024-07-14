Sistema de Gerenciamento de Eventos desenvolvido na PSW 6.0
===========================================================

Screenshots
-----------
![image1](https://github.com/user-attachments/assets/74079a25-bf38-4f2b-bf12-5b961af47cab)
![image2](https://github.com/user-attachments/assets/86e2457d-54b4-44bf-93e4-c693b0eef1e4)
![image3](https://github.com/user-attachments/assets/0a51c63a-edfa-4221-9620-8de99d9dfc28)
![image4](https://github.com/user-attachments/assets/e47b2385-fec7-4f9e-8573-0047c6fedef1)
<p align = "center">
  <img src= "https://github.com/user-attachments/assets/54b19b19-bd11-434c-8131-1ba333d2d712"></img>
</p>

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

5. Instale as dependências do projeto:

`pip install -r requirements.txt`

6. Execute a migração do banco de dados:

`python manage.py makemigrations && python manage.py migrate`

Executando o Projeto
--------------------

Você pode rodar o projeto localmente usando o seguinte comando:

`python manage.py runserver`

Isso iniciará o servidor de desenvolvimento do Django. Você pode acessar o projeto em seu navegador em `http://localhost:8000/` .

Contribuição
------------

Se quiser contribuir para este projeto, sinta-se à vontade para enviar pull requests ou abrir issues.

Divirta-se usando o projeto Django! :)

Contato
-------
[![Linkedin Badge](https://img.shields.io/badge/-thiagojordao98-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)](https://www.linkedin.com/in/thiagojordao98/) 
[![Gmail Badge](https://img.shields.io/badge/thiagojordao.dev@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:thiagojordao.dev@gmail.com)](mailto:thiagojordao.dev@gmail.com)
