# Olá! Eu sou o Filipe

Sou psicólogo de formação e analista de sistemas. Atuo como **fundador técnico solo**: concebo o produto, modelo o domínio, defino arquitetura e conduzo a entrega de software — incluindo orquestração de agentes de IA como acelerador de implementação.

Meu primeiro produto nasceu da própria prática clínica. Em 2021, entre agendas de papel, planilhas e apps genéricos, comecei a programar para construir o que faltava. O resultado foi o **AgenPsi**, ainda em uso por colegas psicólogos. Quando o projeto deixou de ser hobby, iniciei a graduação em Análise e Desenvolvimento de Sistemas.

Hoje construo o **Sinclin**: a evolução dessa trajetória — um SaaS multi-tenant de agenda e gestão financeira para clínicas não médicas e profissionais de saúde, com isolamento de dados sob a LGPD.

## Como trabalho

Não me limito a “escrever código”. Meu foco está no ciclo completo de engenharia de produto:

- Análise de requisitos e regras de negócio reais (clínica, financeiro, assinatura)
- Modelagem de domínio e banco de dados
- Arquitetura de software (módulos, papéis, multi-tenant, segurança)
- Planejamento de entrega (backlog, sprints, decisões documentadas)
- Revisão, validação e iteração contínua com agentes de código

Sou uma equipe de uma pessoa: eu defino o *o quê* e o *porquê*; agentes aceleram o *como* — sob minha responsabilidade técnica.

## Projeto em destaque: Sinclin

SaaS web de **agendamento + gestão financeira** para clínicas (foco inicial em psicologia) e profissionais autônomos.

### O que o produto entrega

- Agenda do profissional integrada à agenda da clínica, com papéis e permissões distintos
- Isolamento LGPD: prontuário/anotações do profissional não ficam sob controle da organização
- Fluxos financeiros clínicos: recebimentos, repasses, despesas e relatórios
- Modelo SaaS de contratação e cobrança (profissional, organização e assinatura assumida pela clínica)
- Integração de billing (Asaas), autenticação, segurança perimetral e operação em nuvem

### Stack

| Camada | Tecnologia |
| :--- | :--- |
| Backend | NestJS, TypeScript, Express |
| Views / SSR | EJS, HTML, CSS, JavaScript |
| Banco | PostgreSQL + Prisma |
| Auth | JWT (cookie HTTP-only), Passport |
| Qualidade | Jest (unitário / e2e) |
| Operação | Deploy com PM2, documentação e runbooks |

### Competências que este projeto evidencia

- Arquitetura multi-tenant e matriz de permissões por papel
- Modelagem relacional complexa (domínio clínico + financeiro + billing)
- Segurança de aplicação (CSRF, rate limit, Helmet, sessão, controles de acesso)
- Conformidade e privacidade (LGPD, mapa de dados, isolamento entre contextos)
- Integração com serviços externos de pagamento e faturamento
- Engenharia de produto: requisitos, ADRs, sprints e critérios de qualidade

> Código e documentação técnica disponíveis sob solicitação (repositório privado).

## Projeto anterior: [AgenPsi](https://agenpsi.app.br)

Sistema online de gestão de agenda clínica para psicólogos, nascido da minha experiência como profissional de saúde. Continua em produção, com clientes reais.

### Filosofia e funcionalidades

Autonomia profissional, controle dos dados e simplicidade. Evita automatizar interações clínicas centrais (como cobrança automática do paciente e lembretes de sessão), preservando a relação terapêutica.

- Agenda personalizada (duração, horários e turnos)
- Gestão visual de presença, faltas, cancelamentos, remarcações e pagamentos
- Anotações livres de sessão, com suporte a ditado por voz no celular
- Abertura rápida de conversa no WhatsApp
- Acompanhamento de pagamentos e convênios
- Insights de produtividade (gráficos mensais e anuais)
- App web responsivo, acessível de qualquer dispositivo

### Stack (AgenPsi)

- **Frontend:** HTML5, CSS, JavaScript  
- **Backend:** Node.js, Express.js, EJS  
- **Banco:** MongoDB  

**Aplicação ao vivo:** [agenpsi.app.br](https://agenpsi.app.br)

## Stack e competências

| Tecnologia | Nível | Contexto |
| :--- | :--- | :--- |
| **TypeScript / Node.js** | Avançado | Runtime e tipagem no Sinclin (NestJS) e no AgenPsi (JS/Node) |
| **NestJS** | Avançado | Arquitetura modular SSR + API, guards, DTOs, serviços de domínio |
| **Express.js** | Avançado | Base do AgenPsi e camada HTTP do Sinclin |
| **PostgreSQL + Prisma** | Intermediário–avançado | Modelagem relacional, migrations e regras de persistência |
| **MongoDB** | Intermediário | Persistência do AgenPsi em produção |
| **HTML / CSS / JavaScript** | Avançado | Interfaces SSR, UX clínica e scripts de front |
| **Auth & segurança web** | Intermediário–avançado | JWT, cookies, CSRF, rate limit, Helmet, papéis |
| **Billing / integrações** | Intermediário | Fluxos de assinatura e integração Asaas |
| **Engenharia de produto** | Avançado | Requisitos, domínio, ADRs, backlog e validação com usuários |
| **Orquestração com IA** | Avançado | Especificação, revisão e entrega acelerada com agentes de código |
| **C# / .NET** | Familiar | Estudos e pequenos projetos de console / OOP |
| **Rust** | Em aprendizado | Sintaxe e conceitos fundamentais (ownership, borrowing) |

## Formação e perfil

- Graduação em **Psicologia** — domínio do problema clínico e do usuário final  
- Graduação em **Análise e Desenvolvimento de Sistemas** — formalização técnica da engenharia  
- Perfil: **fundador técnico solo / analista de sistemas orientado a produto**

## Onde encaixo bem

- Startups early-stage e produtos digitais B2B  
- Papéis de análise de sistemas, product owner técnico ou full stack com visão de domínio  
- Times enxutos que valorizam quem traduz regra de negócio em arquitetura e entrega  
- Ambientes abertos a engenharia assistida por IA, com ownership humano do resultado  

## Estatísticas públicas

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=filipechgs&show_icons=true&theme=radical&hide_rank=true)](https://github.com/filipechgs)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=filipechgs&layout=compact&theme=radical)](https://github.com/filipechgs)
