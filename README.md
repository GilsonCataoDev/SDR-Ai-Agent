# SDR-Ai-Agent

Esqueleto inicial de um backend em **NestJS (TypeScript)** para um agente de IA de pré-vendas (SDR).

## Estado atual

Este repositório está no começo. Hoje ele tem apenas:

- o projeto base gerado pelo NestJS em `backend/sdr-api`, com a rota `GET /` de exemplo;
- configuração de testes (unitário e e2e com Vitest), lint (oxlint) e formatação (Prettier).

**Ainda não há lógica de agente, integração com modelo de linguagem nem envio de mensagens.** Não o apresento como projeto de IA pronto.

## Próximos passos planejados

- Receber leads e registrar o histórico de cada conversa.
- Integrar uma API de LLM para qualificar o lead e sugerir a próxima mensagem.
- Registrar logs e permitir revisão humana antes de qualquer envio.

## Como rodar

```bash
cd backend/sdr-api
npm install
npm run start:dev
```
