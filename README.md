# AWS Static Website - S3 + CloudFront

## Descrição do Projeto

Este projeto demonstra a criação de um **site estático** hospedado na **AWS** utilizando **Amazon S3** e **CloudFront**, sem a necessidade de servidores.  
O objetivo é entregar um site **rápido**, **seguro** e de **baixo custo**, aplicando **boas práticas de segurança** e **arquitetura em nuvem**.

##  

##Tecnologias e Serviços AWS Utilizados

- **Amazon S3** – Armazenamento de arquivos do site
- **Amazon CloudFront** – Distribuição global de conteúdo
- **AWS Pricing Calculator** – Estimativa de custos

##  Funcionalidades Implementadas

- [x] Bucket S3 para hospedagem de site estático
- [x] Política de acesso restrita (OAI) para proteger o conteúdo
- [x] Distribuição CloudFront para acelerar a entrega
- [x] Estimativa de custos no AWS Pricing Calculator
- [x] Diagrama da arquitetura
- [x] Prints detalhados das configurações

##  Estrutura do Projeto

- `/screenshots` – Prints de tela das configurações
- `/architecture` – Diagrama da arquitetura do projeto
- `/pricing` – Estimativa de custos (PDF ou captura de tela)

## Como Executar o Projeto

1. Acesse o bucket configurado no S3
2. Faça o upload do `index.html` e `error.html`
3. Configure a distribuição no CloudFront apontando para o bucket
4. Aguarde a propagação do DNS e teste a URL do CloudFront

##  Estrutura do Site

**Configuração no S3:**
- `index document`: index.html
- `error document`: error.html

##  Acesso ao Site

- **URL CloudFront**: [https://d12j1dzf1gzor.cloudfront.net] 
   *link removido* (serviço foi desativado para evitar custos na AWS)


##  Prints de Tela

Todos os prints das configurações estão disponíveis na pasta `/screenshots`.

##  Diagrama de Arquitetura

O diagrama do projeto está disponível na pasta `/architecture`.

##  Cálculo de Custos

A estimativa de custos gerada no **AWS Pricing Calculator** está na pasta `/pricing`.

##  Aprendizados

- Criação de site estático na AWS sem servidor
- Configuração segura de acesso com CloudFront e S3
- Boas práticas de segurança na AWS (OAI, restrição de acesso)
- Distribuição global de conteúdo com baixo custo

##  Autor

- **Pablo Henrique Lehmam Leme**  
  [LinkedIn](https://www.linkedin.com/in/pablo-lehmam-16b309272/) |
  [GitHub](https://github.com/pablolehmam)
