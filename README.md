## Docker-compose 

Arquivo docker-compose que ira fornecer 3 containers sendo { wordpress (appWeb) + banco mysql (webDB) + adminer }

1. Apos fazer o clone desse projeto, acesse o diretorio onde o arquivo docker-compose.yml se encontra e crie as pastas
   - wp
   - database
   
   e em seguida execute o comando abaixo e aguarde finalizar, automaticamente os containers ficarão ativos:
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
