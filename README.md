# github-actions-dotnet-webapp
Introdução ao GitHub Actions
# Workflow Configuration

Este repositório contém um workflow configurado para:

1. Ser acionado por eventos de push na branch `main`.
2. Ser executado automaticamente a cada hora.

## Estrutura do Repositório

- `.github/workflows/workflow.yml`: Configuração do workflow.
- `scripts/custom_script.sh`: Script personalizado executado pelo workflow.

## Como Usar

1. Faça push para a branch `main` para acionar o workflow.
2. O workflow também será executado automaticamente a cada hora.