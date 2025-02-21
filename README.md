# LandingPage-RestrictArea


# Linguagem Utilizada
*	Frontend: HTML, CSS, JavaScript
*	Backend: Java (Servlets)

# Banco de Dados
Acessado pelo java usando JDBC, o banco de dados utilizado é um banco de dados relacional Postgre.

# Framework Utilizado
* Não foram utilizados Frameworks

# Como Executar a Instalação no Notebook
1.	Instale o Docker em seu notebook.
2.	Clone o repositório: 
3.	git clone https://github.com/Peticos/LandingPage-RestrictArea
4.	Navegue até o diretório do projeto: 
5.	cd LandingPage-RestrictArea
6.	Construa e inicie o container usando o Docker: 
7.	docker-compose up --build
8.	Acesse o site em http://localhost:8080.

# Informações de Licença
Este projeto está licenciado sob a MIT License. 

# Informações de Copyright
“Copyright (c) 2024 isaacnewton-tech”, se trata do perfil criador do repositório.

# Acesse o site por:
  * https://peticos.onrender.com

# Como configurar o tomcat para rodar o projeto:
  * Adicione o tomcat ao projeto (Tomcat Local)
  * Nas configurações do Tomcat, deixe a URL em: 'http://localhost:8080/'
  * Em cima, nas abas, clique em 'Deployment' e clique para adicionar um Artefato;
  * Selecione a opção 'Peticos: war exploded';
  * Em 'Application Context' deixe apenas uma barra '/';
  * Vá para a aba EnvFile, e se estiver desabilidato, abilite;
  * Clique para adicionar um .env e selecione o .env na raiz do projeto (fornecido por alguém)
  * Pronto! Está tudo configurado.. Se algo não der certo, entre em contato.
