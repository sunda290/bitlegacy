# ⛓ BitLegacy

**Protocolo de herança Bitcoin para o mercado brasileiro.**

Integrando custódia técnica, sucessão patrimonial e direito de forma acessível.

---

## O problema

Bitcoin resolve o risco de contraparte. Mas quem cuida da continuidade?

- **3–4 milhões de BTC** estimados perdidos para sempre por falta de plano de herança
- Advogados de sucessão não entendem custódia e chaves privadas
- Advogados de cripto não entendem direito sucessório
- Famílias ficam sem acesso após o falecimento do titular

## A solução

BitLegacy é uma camada de orquestração sobre a [Liana Wallet](https://wizardsardine.com/liana) que adiciona:

| Camada | O que resolve |
|--------|--------------|
| **Técnica** | Timelocks, multisig, chaves de recuperação (Liana) |
| **Jurídica** | Protocolo de documentação, testamento, IR |
| **Familiar** | Kit do Herdeiro, instruções step-by-step |
| **Software** | Painel do consultor, alertas, relatórios |
| **Marketplace** | Rede de advogados especializados |

---

## Protótipos

| Produto | Descrição | Demo |
|---------|-----------|------|
| **SentinelMail** | Dead Man Switch por email escalonado | [Ver demo](./sentinelmail/) |
| **Project Hub** | Dashboard de gestão do projeto | [Ver demo](./project-hub/) |
| **BitLegacy App** | Análise de oportunidade completa | [Ver demo](./docs/analise-bitlegacy.html) |

---

## Stack

- **Backend:** Node.js + Express + PostgreSQL
- **Frontend:** React / Next.js
- **IA:** Claude API (Anthropic)
- **Motor técnico:** Liana Wallet (open-source, BSD 3-Clause)
- **Automação:** Google Apps Script

---

## Sobre o SentinelMail

Sistema de email escalonado que dispara automaticamente se o titular parar de responder ao ping periódico.

```
3 meses  → Amigos investigam
6 meses  → Cônjuge recebe Parte 1
12 meses → Protocolo completo + advogado
24 meses → Herdeiros secundários
```

Validação de vida: ping periódico por email. O titular clica "estou vivo" para reiniciar o contador.

---

## Fundamentos técnicos

- **BIP 65** — OP_CHECKLOCKTIMEVERIFY: timelocks nativos do Bitcoin
- **Miniscript** — contratos Bitcoin complexos de forma auditável
- **Liana Wallet** — open-source, sem custódia, sem terceiros

---

## Equipe

- **André Oliveira** — Desenvolvimento · Hamilton, Canadá
- **Thiago** — Estratégia e negócios
- **Filipe Iorio** — CriptoVerso · Especialista Bitcoin
- **Jeff Bernar** — Revista Pleb's · Conteúdo e OPSEC

---

## Filosofia

> *"Not your keys, not your coins.*
> *Not your plan, not your legacy."*

Bitcoin foi criado para soberania individual. O BitLegacy garante que essa soberania sobreviva ao seu titular.

---

## Licença

Protótipos e documentação: MIT  
Motor técnico (Liana Wallet): BSD 3-Clause

---

*Projeto em desenvolvimento ativo · Abril 2026*
