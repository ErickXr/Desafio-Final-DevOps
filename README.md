# 🚀 Desafio Final DevOps – GitHub Actions Workflow
 
![Last Commit](https://img.shields.io/github/last-commit/ErickXr/desafio-final-devops?style=flat)  
![License](https://img.shields.io/github/license/ErickXr/desafio-final-devops?style=flat)  
![Python Version](https://img.shields.io/badge/python-3.10+-blue?style=flat)  

📚 **Projeto acadêmico desenvolvido na faculdade Impacta, 3º semestre de ADS**  
💻 **API simples em Flask com CI/CD via GitHub Actions**  

Este repositório contém a solução do desafio final da formação DevOps. O objetivo deste projeto é demonstrar o domínio de ferramentas de automação, infraestrutura e deploy contínuo.

📋 Sobre o Projeto
O projeto consiste na automatização do ciclo de vida de uma aplicação, desde a escrita do código até o provisionamento em nuvem e monitoramento.

PARTE 2: Stack Tecnológica
(Copia e cola isto abaixo da Parte 1)

🛠 Tecnologias Utilizadas
Infraestrutura: Terraform / Ansible

Containers: Docker & Docker Compose

Orquestração: Kubernetes (K8s)

CI/CD: GitHub Actions

Cloud: AWS / Azure / GCP

PARTE 3: Guia de Instalação e Execução
(Copia e cola isto abaixo da Parte 2)

🚀 Como Executar o Projeto
1. Clonar o Repositório:
git clone https://github.com/ErickXr/Desafio-Final-DevOps.git

2. Subir o Ambiente Local (Docker):
docker-compose up -d

3. Provisionar Infraestrutura (IaC):
terraform init
terraform apply -auto-approve

PARTE 4: Pipeline CI/CD e Autor
(Copia e cola isto para finalizar o ficheiro)

⚙️ Fluxo de Trabalho (Pipeline)
A pipeline automática realiza as seguintes tarefas:

Verificação de erros no código (Linting).

Construção da imagem Docker.

Envio da imagem para o repositório (Docker Hub/ECR).

Deploy automático no servidor de produção.
