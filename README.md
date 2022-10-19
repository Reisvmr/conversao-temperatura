# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

#### Instrucao apois copiar o repo execute os comandos:
```
# Acesse o diretorio do Dockerfile
cd src
# Rode o comando para criar a imagem
sudo docker build -t reisvmr/conversao-temperatura:v1 .
#Executar o App
sudo docker container run -d -p 8080:8080 reisvmr/conversao-temperatura:v1 
```
