# Is My Burguer Docs

Documentação dos requisitos da Fase 5 da Pós-Graduação em SOFTWARE ARCHITECTURE da FIAP 

Este repositório tem por objetivo centralizar as principais características do projeto em um único local.

## Estrutura na AWS

![alt text](/docs/is-my-burguer-api.drawio.png)

# Requisitos necessários para compilar o projeto

Ter o docker instalado na sua máquina:

* [Windows](https://docs.docker.com/windows/started)

* [OS X](https://docs.docker.com/mac/started/)

* [Linux](https://docs.docker.com/linux/started/)

Ter o Java 20 instalado na sua máquina:

[JDK 20](https://jdk.java.net/java-se-ri/20)

## Estrutura dos Repositórios:

Os repositórios de cada microserviço e criação de infra possuem suas próprias documentações com detalhes sobre as escolhas e os serviços disponibilizados para cada um.

São eles:

### Is My Burguer RDS 

Projeto responsável pela criação das databases e sua infraestrutura na AWS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-terraform-rds)

### Is My Burguer Cognito

Projeto responsável pela criação do Cognito, API Gateway, Lambdas de autenticação na infraestrutura na AWS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-cognito)

### Is My Burguer K8S

Projeto responsável pela criação do EKS e dos SQS na infraestrutura na AWS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-terraform-k8s)

### Is My Burguer SD

Projeto com o código-fonte do Service Discovery e seu deploy no EKS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-sd)

### Is My Burguer Auth

Projeto com o código-fonte da API de Autenticação e seu deploy no EKS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-auth)

### Is My Burguer Pedido

Projeto com o código-fonte da API de Produtos e Pedidos e seu deploy no EKS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-pedido)

### Is My Burguer Pagamento

Projeto com o código-fonte da API de Pagamento e seu deploy no EKS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-pagamento)

### Is My Burguer Controle de Pedido

Projeto com o código-fonte da API de Controle de Pedidos e seu deploy no EKS
 [(Clique aqui para mais)](https://github.com/ismaelgcosta/is-my-burguer-controle-pedido)






