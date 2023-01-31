## Docker-compose 

Arquivo docker-compose que ira fornecer 3 containers sendo { wordpress (appWeb) + banco mysql (webDB) + adminer }

1. Apos fazer o clone desse projeto, executar o comando dentro do diretorio que contem o arquivo docker-compose.yml
```
docker compose up -d
```

2. Acessar pelo navegador o endereço, para configurar o wordpress
```
http://localhost:8000
```

3. Para conectar ao banco pelo navegador acesse
```
http://localhost:9000
```
 - E conectar com o banco com as credenciais descritas no docker-compose.yml 
   - container_name = webDB
   - MYSQL_USER = usuário do banco
   - MYSQL_PASSWORD = senha do usuário
   - MYSQL_DATABASE = base de dados
