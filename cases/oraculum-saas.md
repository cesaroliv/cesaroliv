# Oraculum SaaS

**Status:** release candidate local `0.9.0-rc.1`. **Não está em produção.** Código mantido privado.

## Objetivo
Construir uma aplicação SaaS full-stack com conta de usuário, conteúdo estruturado, regras de acesso e preparação de billing, mantendo gates explícitos antes de qualquer publicação em produção.

## Stack
- React, TypeScript e Vite
- Express
- PostgreSQL / PGlite em desenvolvimento
- Playwright e Vitest
- autenticação por cookie HttpOnly
- CSRF, CORS, CSP e autorização por roles
- integração de billing preparada para Mercado Pago
- scripts de backup, restore e validação

## O que já foi implementado
- autenticação e recuperação de conta
- autorização por perfil e APIs versionadas
- catálogo, entitlements e limites
- checkout fake/local para testes

- adapter de Mercado Pago com ativação externa bloqueada por configuração
- testes unitários, integração e E2E
- build de produção e smoke tests
- documentação de arquitetura e preparação de staging

## Estado real
O próprio projeto mantém um gate **NOT READY** para produção enquanto faltarem validações externas e de staging, como HTTPS/domínio reais, PostgreSQL gerenciado, sandbox de pagamentos, providers externos e revisões independentes.

## Competências demonstradas
- desenvolvimento full-stack
- QA de aplicação SaaS
- autenticação e autorização
- segurança por configuração
- integração de pagamentos
- arquitetura e documentação
- testes E2E
- preparação responsável para go-live

## Aplicação freelance
Relevante para **MVPs, dashboards, SaaS, APIs, autenticação, fluxos de assinatura, manutenção de aplicações React/Node e QA full-stack**.
