# Guia Detalhado de Instalação

## Configuração do Ambiente

1. Crie um arquivo `.env` na raiz do projeto baseado no `.env.example`:
   ```env
   PORT=3000
   DATABASE_URL=postgres://usuario:senha@localhost:5432/healthconnect
   PAYMENT_GATEWAY_KEY=sua_chave_aqui
