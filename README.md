# Sabor Caseiro

Site institucional fictício de um restaurante, desenvolvido como parte da Prova 2 de Gerência de Configuração de Software (UFMS, 2026/1).

## Equipe

Beatriz Vieira, Maria Eduarda de Macedo, Isabela Garcia, Luciana Nunes, Reinaldo Hashioka, Miguel Paulo Rodrigues

## Objetivo

Aplicar na prática três modelos de ramificação Git (GitHub Flow, Git Flow e Trunk-Based Development), simulando cenários reais de equipes de engenharia de software.

## Estrutura do projeto

```
sabor-caseiro/
├── index.html       # Homepage do restaurante
├── login.md          # Especificação da área de login do admin
├── css/style.css      # Estilos
├── js/script.js       # Scripts
├── CONTRIBUTING.md    # Padrão de commits, branches e fluxo de PR
└── .github/
    └── PULL_REQUEST_TEMPLATE.md
```

## Cenários executados

- **Cenário 1 — GitHub Flow:** branch `nova-funcionalidade-homepage`, contribuições incrementais, PR e merge na `main`.
- **Cenário 2 — Git Flow:** branches `develop`, `feature/login`, `release/v1.0`, `hotfix/v1.0.1`, tags `v1.0` e `v1.0.1`.
- **Cenário 3 — Trunk-Based Development:** branches curtas `feature-*` integradas rapidamente à `main`.

Veja o padrão de commits e branches em [CONTRIBUTING.md](./CONTRIBUTING.md).
