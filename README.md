# Projeto_simula-o_AWS_com_Localstack
Este projeto tem como objetivo simular recursos da AWS localmente usando Localstack, permitindo testar integrações de serviços sem precisar usar ambiente real da AWS.

# 🧪 Projeto — Simulação AWS com Localstack

Este projeto tem como objetivo simular recursos da AWS localmente usando Localstack, permitindo testar integrações de serviços sem precisar usar ambiente real da AWS.

O foco deste desafio é criar um fluxo completo envolvendo serviços essenciais do ecossistema AWS.



## 🔧 Serviços usados neste projeto

Neste laboratório nós iremos:

- Criar um Bucket S3 para receber arquivos (upload de notas fiscais)
- Criar uma tabela DynamoDB para armazenar os dados processados
- Criar uma função Lambda que processa os arquivos enviados ao S3
- Configurar um trigger do S3 → Lambda para processamento automático
- Criar uma API Gateway para acessar os dados de forma via endpoint HTTP



## 🎯 Objetivo do fluxo

> Arquivos JSON serão enviados ao S3 → a Lambda será executada → e salvará as informações no DynamoDB.  
Além disso, uma API será exposta via API Gateway para consultas/testes.


## Como Resultado teremos:

Uma arquitetura serverless simulada localmente que representa: S3 Upload → Lambda → DynamoDB → API Gateway. Tudo rodando local, totalmente offline, sem custos.


