# Olá! Eu sou Thiago Oliveira 👋

### Software Engineering Student | Full-Stack & Software Developer

Sou estudante de Engenharia de Software na UNINTER e desenvolvedor em formação, interessado na construção de aplicações web, desktop e mobile, APIs, sistemas distribuídos, automação e soluções que resolvam problemas reais.

Desenvolvo projetos práticos utilizando **Go, C#, TypeScript, JavaScript, PHP, Python e Dart**, explorando diferentes arquiteturas, frameworks, bancos de dados, integrações e práticas de qualidade de software.

Meu portfólio reúne aplicações de gestão empresarial, suporte técnico, agendamento, operações com webhooks, produtividade no Windows, cardápios digitais, planejamento financeiro, gestão de orçamentos e automação de relatórios.

---

## 🛠️ Tecnologias e ferramentas

### Linguagens
- Go
- C#
- TypeScript e JavaScript
- PHP
- Python
- Dart
- SQL

### Frontend, desktop e mobile
- React, Next.js e Vue
- Vite e Tailwind CSS
- WPF e Windows desktop
- Flutter
- React Router, Vue Router e TanStack Query
- React Hook Form, Zod, Pinia e Riverpod

### Backend e APIs
- Node.js, Express e NestJS
- ASP.NET Core / .NET
- Laravel
- APIs REST e OpenAPI
- Webhooks, processamento assíncrono e workers
- Autenticação, autorização e validação de dados

### Bancos de dados e mensageria
- PostgreSQL
- SQLite
- Redis
- NATS JetStream
- Supabase
- Prisma ORM
- Entity Framework Core
- SQLAlchemy

### Testes, qualidade e infraestrutura
- Vitest, Jest, Pytest, PHPUnit e xUnit
- Supertest, Playwright e Testing Library
- Git e GitHub
- GitHub Actions
- Docker e Docker Compose
- Nginx

---

## 🚀 Projetos em destaque

### 🔗 RelayForge — Webhook Infrastructure Platform

Plataforma de infraestrutura para receber, persistir, processar, entregar, repetir e monitorar eventos de webhook. A arquitetura utiliza um monólito modular com processos workers independentes.

**Destaques:**
- Ingestão de eventos com validação HMAC e idempotência.
- Persistência transacional de eventos e registros de outbox.
- Workers independentes para publicação e entrega.
- Mensageria durável com NATS JetStream.
- PostgreSQL como fonte de verdade e Redis para cache/coordenação.
- Organizações, memberships, RBAC, sessões e trilha de auditoria.
- API versionada e console web em desenvolvimento.

**Tecnologias:** Go, PostgreSQL, Redis, NATS JetStream, React, TypeScript, Vite, Docker Compose e Node.js.

🔗 [Acessar o RelayForge](https://github.com/Thiago-tods/relayforge)

### 🪟 DynamicIsland — Dynamic Island for Windows

Aplicação desktop para Windows inspirada na Dynamic Island, com uma interface flutuante que reúne informações e controles rápidos.

**Destaques:**
- Relógio, cronômetro e controles de mídia.
- Monitoramento de CPU, memória e GPU NVIDIA compatível.
- Notificações do Windows e histórico de alertas.
- Clima, downloads e acompanhamento de progresso.
- Temas claro/escuro, atalhos globais e integração com a bandeja do sistema.
- Suporte a múltiplos monitores e empacotamento em instalador Windows.

**Tecnologias:** C# 13, .NET 10, WPF, CommunityToolkit.Mvvm, WinRT, Inno Setup e xUnit.

🔗 [Acessar o DynamicIsland](https://github.com/Thiago-tods/DynamicIsland)

### 📦 StockWise — Gestão de Estoque e Operações Comerciais

Sistema web para pequenos negócios que centraliza catálogo, compras, recebimentos, vendas, devoluções e movimentações de estoque, mantendo histórico operacional e trilha de auditoria.

**Destaques:**
- Controle de produtos, categorias, fornecedores e clientes.
- Compras, recebimentos parciais, vendas, cancelamentos e devoluções.
- Atualização transacional do estoque e histórico de movimentações.
- Dashboard e relatórios com exportação CSV, XLSX e PDF.
- Autenticação por sessão, papéis de acesso, proteção CSRF e auditoria.

**Tecnologias:** React 19, TypeScript, Vite, Node.js 22+, Express 5, PostgreSQL 17+, Prisma 7, Vitest, Supertest, Testing Library, Docker Compose e Nginx.

🔗 [Acessar o StockWise](https://github.com/Thiago-tods/StockWise)

### 🎫 HelpDeskPro — Sistema de Gerenciamento de Chamados

Aplicação full-stack de suporte técnico, com fluxos específicos para solicitantes, agentes e administradores.

**Destaques:**
- Abertura, atribuição, acompanhamento e resolução de chamados.
- Kanban, mensagens, notas internas e histórico de alterações.
- SLA calculado no backend, relatórios e auditoria.
- Atualizações em tempo real com SignalR.
- Autenticação, permissões por papel e interface responsiva.

**Tecnologias:** C#, .NET 10, ASP.NET Core Web API, Entity Framework Core, PostgreSQL, React, TypeScript, Vite, Tailwind CSS, SignalR, xUnit, Vitest e Playwright.

🔗 [Acessar o HelpDeskPro](https://github.com/Thiago-tods/HelpDeskPro)

### 🛠️ ServiceCheck — Ordens de Serviço para Equipes de Campo

Aplicação mobile-first para técnicos e equipes externas, com operação offline-first e sincronização posterior com o servidor.

**Destaques:**
- Gestão de ordens, agenda, clientes, equipes e serviços.
- Checklists, fotos, observações e assinatura na tela.
- Sincronização offline com operações idempotentes e tratamento de conflitos.
- Relatórios PDF, notificações e auditoria.
- Interface em português e inglês.

**Tecnologias:** Flutter, Dart, Riverpod, GoRouter, Drift/SQLite, NestJS, TypeScript, PostgreSQL, Prisma, Jest e Flutter Test.

🔗 [Acessar o ServiceCheck](https://github.com/Thiago-tods/ServiceCheck)

### 📅 AgendaPro — Agendamento e Gestão de Serviços

Plataforma multiempresa para clínicas, barbearias, consultorias, estúdios e outros negócios de serviços.

**Destaques:**
- Agenda com visões diária, semanal e mensal.
- Gestão de agendamentos, clientes, profissionais e serviços.
- Regras de disponibilidade e prevenção de conflitos de horário.
- Painel com indicadores operacionais.
- Controle de acesso e isolamento entre empresas.

**Tecnologias:** PHP 8.4, Laravel 13, PostgreSQL, Vue 3, TypeScript, Vite, Pinia, Tailwind CSS, PHPUnit e Vitest.

🔗 [Acessar o AgendaPro](https://github.com/Thiago-tods/agendapro)

### 🍽️ MenuQR — Cardápio Digital e Pedidos por QR Code

Aplicação demonstrativa para restaurantes, permitindo que clientes acessem o cardápio pelo QR Code, montem pedidos e acompanhem seu andamento.

**Destaques:**
- Cardápio digital com categorias, busca e complementos.
- Carrinho e checkout para retirada ou consumo no local.
- Painel administrativo para produtos, pedidos, mesas e QR Codes.
- Atualização do status dos pedidos e acompanhamento por link.
- Supabase Auth e políticas de acesso no banco de dados.

**Tecnologias:** Next.js 16, React 19, TypeScript, Tailwind CSS, Supabase (PostgreSQL, Auth, Storage e RLS), Zod, Vitest e Playwright.

🔗 [Acessar o MenuQR](https://github.com/Thiago-tods/MenuQR)

### 💰 FinPlan — Planejamento Financeiro Pessoal

Aplicação mobile para organização financeira, com API backend e persistência em banco de dados relacional.

**Destaques:**
- Autenticação com JWT e rotação de refresh tokens.
- Cadastro e gerenciamento de contas bancárias.
- Registro de receitas e despesas por categoria.
- Controle de contas a pagar e pagamentos.
- Isolamento dos dados por usuário e proteção contra atualizações concorrentes.

**Tecnologias:** Flutter, Dart, NestJS, TypeScript, PostgreSQL, Prisma, Vitest, Supertest e Flutter Test.

🔗 [Acessar o FinPlan](https://github.com/Thiago-tods/FinPlan)

### 📋 QuoteMaster — Gestão de Orçamentos Comerciais

Aplicação web local para cadastro de clientes, produtos e serviços, criação de orçamentos e geração de documentos PDF.

**Destaques:**
- Gerenciamento de clientes e catálogo.
- Orçamentos com cálculos financeiros no servidor e fluxo de status.
- Geração de PDF A4 com itens, condições e logotipo.
- Configurações da empresa e persistência local.
- Organização em camadas e migrations.

**Tecnologias:** C#, .NET 10, ASP.NET Core MVC, Entity Framework Core, SQLite e QuestPDF.

🔗 [Acessar o QuoteMaster](https://github.com/Thiago-tods/QuoteMaster)

### 📊 Automação de Relatórios Comerciais

Sistema em Python para importar, validar e processar dados comerciais, consultar o PostgreSQL e gerar relatórios gerenciais.

**Destaques:**
- Importação e validação de arquivos Excel e CSV.
- Cálculo de indicadores de desempenho por loja.
- Geração de planilhas e rankings.
- Criação e envio de e-mails personalizados com relatórios.
- Logs, tratamento de falhas e modo de simulação.
- Testes automatizados para cálculos, importação, banco e fluxo de relatórios.

**Tecnologias:** Python, Pandas, openpyxl, PostgreSQL, SQLAlchemy, psycopg, python-dotenv, smtplib e Pytest.

🔗 [Acessar o projeto](https://github.com/Thiago-tods/projeto-analise-planilhas-py)

---

## 🎓 Formação acadêmica

**Engenharia de Software — UNINTER**  
Bacharelado | 2026 – 2030

---

## 🌎 Idiomas

- Português: Nativo
- Inglês: Avançado

---

## 🎯 Objetivo profissional

Busco oportunidades de estágio ou posições júnior em desenvolvimento de software, com interesse em backend e full-stack, APIs, sistemas web, desktop e mobile, bancos de dados, integrações e automação.

Gosto de aprender novas tecnologias, compreender problemas e desenvolver soluções funcionais, mantendo atenção à organização, segurança, qualidade e manutenção do software.

---

## 📫 Contato

- **LinkedIn:** [Thiago Oliveira](https://www.linkedin.com/in/thiago-oliveira-91a4851b2/)
- **GitHub:** [Thiago-tods](https://github.com/Thiago-tods)

---

<p align="center">
  <i>Construindo, aprendendo e evoluindo um projeto de cada vez. 🚀</i>
</p>
