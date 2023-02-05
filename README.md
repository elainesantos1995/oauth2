# oauth2

# oauth2

* Para utilizar o H2, basta descomentar as configs do H2 e comentar as do postgres em application.properties

* Para utilizar o banco postgres, basta descomentar e comentar as configs do H2
    * editar o docker-compose.yml substituindo o endereço de e-mail
    * executar: $ docker-compose up -d 
    * abrir no navegador o endereço: http://localhost:15432/
        * logar com o endereço de e-mail e com a senha cadastrada no arquivo .yml
        * já na tela do pgadmin, criar um server 
            * no pop-up de criar server, na aba General, adicionar o nome 'localhost'
            * na aba Connection do mesmo pop-up, adicionar o nome hostname 'postgres', 
            username 'postgres' e a senha cadastrada para p postgres

* Após executar o banco, rodar o aplicação a partir da classe: Oauth2Application.java
