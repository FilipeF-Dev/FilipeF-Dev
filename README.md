# Filipe Ferreira

Analista de TI em Juiz de Fora (MG). Desenvolvo software com IA: escrevo a especificação
(problema, regras de negócio, arquitetura e critério de pronto), conduzo agentes de código
na implementação e valido com testes antes de subir.

## O que estou construindo

- **Intranet corporativa** · *privada, uso interno*
  Painel modular com mais de 20 módulos em produção (tickets, RH, compras, inventário, SAC,
  estatísticas comerciais, chat). Inclui o **Remy**, um assistente com modelo de linguagem
  por API, desenhado para não enxergar dados internos e com teto de custo mensal.
  Também automatiza a operação: monitoramento de serviços ao vivo e relatório diário de
  infraestrutura por e-mail.
  `Next.js` `TypeScript` `Prisma` `PostgreSQL`

- **Petire** · [petire.vercel.app](https://petire.vercel.app)
  Cardápios das lojas do bairro, com o pedido fechado direto no WhatsApp da loja.
  Testes de ponta a ponta com Playwright e CI.
  `Next.js` `Supabase` `Vercel`

- **Lar**
  App colaborativo para famílias: tarefas, lista de compras e mural em tempo real.
  `Flutter` `NestJS` `PostgreSQL` `Redis`

- **[nvoip-java-backend-challenge](https://github.com/FilipeF-Dev/nvoip-java-backend-challenge)**
  API REST com autenticação JWT e integração de SMS e chamadas via Feign.
  `Java` `Spring Boot`

## Como trabalho

1. **Spec antes do código:** escopo, regras de negócio, arquitetura e decisões ficam
   escritos antes da implementação e são atualizados quando a decisão muda.
2. **Contexto para o agente:** cada repositório tem um `CLAUDE.md` / `AGENTS.md` com o
   projeto, as regras e os cuidados.
3. **Validação:** testes automatizados nas regras caras de errar e CI no GitHub Actions.
4. **Segurança e LGPD:** reviso permissões, segredos e exposição de dados nos módulos
   que tocam bancos e dados pessoais.

## Stack

TypeScript · Next.js · React · Prisma · PostgreSQL · Supabase · Python · Java / Spring Boot · Flutter · Claude Code

📫 [LinkedIn](https://www.linkedin.com/in/filipe-ferreira-72b24624b/)
