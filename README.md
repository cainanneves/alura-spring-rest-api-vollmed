# alura-spring-rest-api-vollmed

Para simular um deploy na propria máquina, rode no terminal: 
java "-Dspring.profiles.active=prod" "-DDATASOURCE_URL=jdbc:mysql://localhost:3306/vollmed_api" "-DDATASOURCE_USERNAME=admin" "-DDATASOURCE_PASSWORD=12345" -jar .\target\api-0.0.1-SNAPSHOT.jar

Usando o dockerfile o docker sobe a imagem e nao rpecisa fazer isso.
