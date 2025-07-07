# Projeto de Microserviços com Docker Compose e Docker Hub

Este repositório contém um sistema simples baseado em **microserviços** usando `Docker Compose`, com deploy de imagens no **Docker Hub**. O sistema é composto por:

- `ms-pessoas-aleatorias`: microserviço que retorna nomes aleatórios
- `ms-saudacoes-aleatorias`: microserviço que retorna saudações
- `site-gerador-saudacoes`: site que consome os dois serviços e exibe uma saudação completa
