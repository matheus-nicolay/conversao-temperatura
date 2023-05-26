# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Funcionalidades:
- **src/Dockerfile**
  - Definição da imagem Docker para a aplicação

- **k8s/deployments.yaml**
    Arquivo de deployment Kubernetes
    
  - Deployment da aplicação (com imagem personalizado do Docker Hub) 
  - Service NodePort

### Observações do projeto
A aplicação é exposta usando a porta 8080
