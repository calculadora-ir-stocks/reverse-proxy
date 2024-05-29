## stocks-reverse-proxy
Armazena o arquivo Docker Compose necessário para criar a configuração inicial do proxy reverso da API do Stocks.  
Para iniciá-lo, execute:  

`docker compose -f nginx-compose.yaml up -d`

A rede _my_network_ especificada no arquivo deve existir no Docker:  

`docker network create my_network`

O arquivo deve sempre ser executado antes da subida da API e do banco de dados.
