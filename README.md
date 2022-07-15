# FIAP-FASE4

## ETAPA 1 - Entregáveis

- Imagem customizada, tagueada e publicada no registry do quay.io. 

    - quay.io/gmartinsss/rm343471-do180-custom-httpd (Repositório esta publico)

- Dockerfile que utiliza imagem customizada

- Docker commands para buildar a imagem

    - docker build -f dockerfile -t meu-blog .
    
    - docker run -d -p 8180:80 meu-blog

## ETAPA 2 - Entregáveis

Yamls baixados da plataforma openshift evidênciando o deployment de uma aplicação

- YAML do build de aplicação rodando no openshift
- YAML da rota criada para a aplicação
- YAML de serviço da aplicação
- YAML de HPA da aplicação

![image](https://user-images.githubusercontent.com/13898332/179131965-f7b29651-6756-4d8b-bb41-1648cf3c92d5.png)

YAMls baixados da plataforma openshift evidênciando a criação de um banco de dados com persistência de dados

- YAML do serviço do sample-database
- YAML do persistent volume claim

## ETAPA 3 - Entregaáeis

YAML de HPA criado para a aplicação


