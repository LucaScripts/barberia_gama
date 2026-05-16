# Barbearia Gama

Sistema web da Barbearia Gama para apresentar serviços, centralizar agendamentos e oferecer um painel administrativo simples para gerenciamento do conteúdo.

## Visão geral

- Página principal para clientes com informações da barbearia e agendamento.
- Painel administrativo em `admin.html` para gestão de dados.
- Projeto estático, pronto para hospedagem no Firebase Hosting.

## Estrutura

- `index.html` - site principal
- `admin.html` - painel administrativo
- `firebase.json` - configuração de hospedagem
- `.firebaserc` - projeto Firebase padrão

## Como usar localmente

1. Abra `index.html` no navegador para acessar a página principal.
2. Abra `admin.html` no navegador para acessar o painel administrativo.

## Publicação no Firebase

O projeto já está configurado para o site `barbearia-gama-agenda` no Firebase Hosting, com projeto padrão `barbearia-gama-12841`.

Se precisar publicar novamente, use:

```bash
firebase deploy
```

## Observações

- O projeto usa HTML, CSS e JavaScript puro.
- As integrações com Firebase dependem da configuração do projeto no console do Firebase.