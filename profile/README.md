# FIAP Pós Tech · Software Architecture

Organização usada para a entrega do **Tech Challenge** da pós-graduação em Software Architecture (FIAP, 14SOAT).

## Grupo: Integradores

| Nome Completo | RM |
| --- | --- |
| Lucas Gardini Dias | 372237 |
| Thiago Aio | 372238 |

## Microsserviços

| Repositório | Descrição |
| --- | --- |
| [`tc-oficina-os-service`](https://github.com/FIAP-POS-TECH-SOFTWARE-ARCHITECTURE/tc-oficina-os-service) | Ordens de serviço, cadastros e orquestração do fluxo da OS (Saga orquestrada) — PostgreSQL |
| [`tc-oficina-billing-service`](https://github.com/FIAP-POS-TECH-SOFTWARE-ARCHITECTURE/tc-oficina-billing-service) | Orçamentos e pagamentos (Mercado Pago) — DynamoDB |
| [`tc-oficina-execution-service`](https://github.com/FIAP-POS-TECH-SOFTWARE-ARCHITECTURE/tc-oficina-execution-service) | Filas de diagnóstico e reparo — PostgreSQL |

## Plataforma e borda

| Repositório | Descrição |
| --- | --- |
| [`tc-oficina-lambda-auth`](https://github.com/FIAP-POS-TECH-SOFTWARE-ARCHITECTURE/tc-oficina-lambda-auth) | API Gateway + autenticação de clientes via CPF (AWS Lambda) |
| [`tc-oficina-infra-k8s`](https://github.com/FIAP-POS-TECH-SOFTWARE-ARCHITECTURE/tc-oficina-infra-k8s) | VPC, EKS, ECR e mensageria (SNS/SQS) — Terraform |
| [`tc-oficina-infra-db`](https://github.com/FIAP-POS-TECH-SOFTWARE-ARCHITECTURE/tc-oficina-infra-db) | Bancos de dados dos microsserviços (RDS PostgreSQL, DynamoDB) — Terraform |
