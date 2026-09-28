# 🤖 Claude Code — Infrasphere

> Automações, integrações e sistemas web construídos com arquitetura ágil, segurança DevSecOps e foco em alta conversão.

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square)](https://github.com/THGENGSOFT/claude-code)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-privado-red?style=flat-square)](https://github.com/THGENGSOFT/claude-code)
[![Stack](https://img.shields.io/badge/stack-Python%20%7C%20JS%20%7C%20n8n%20%7C%20Gemini-blue?style=flat-square)](https://github.com/THGENGSOFT/claude-code)

---

## 📋 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [Ecossistema Infrasphere](#-ecossistema-infrasphere)
- [Stack Tecnológico](#-stack-tecnológico)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Como Começar](#-como-começar)
- [Segurança](#-segurança)
- [Fluxo de Trabalho Git](#-fluxo-de-trabalho-git)
- [Changelog](#-changelog)

---

## 🎯 Sobre o Projeto

O **Claude Code** é o repositório central de automações, sistemas web, landing pages e integrações do ecossistema **Infrasphere**. Desenvolvido com foco em:

- ⚡ **Performance extrema** — Core Web Vitals otimizados, carregamento em milissegundos
- 🔒 **Segurança blindada** — Arquitetura Zero Trust, DevSecOps nativo
- 📈 **Alta conversão** — CRO integrado, rastreamento multi-plataforma
- 🤖 **IA nativa** — Integração com API Gemini para automações inteligentes

---

## 🌐 Ecossistema Infrasphere

As frentes de desenvolvimento e integrações ativas:

### 🛒 E-commerce & Marketplaces
| Plataforma | Status | Descrição |
|---|---|---|
| Mercado Livre | 🔄 Planejado | Gestão de anúncios e pedidos |
| Shopee | 🔄 Planejado | Sincronização de catálogo |
| Nuvemshop | 🔄 Planejado | Loja virtual integrada |
| iFood | 🔄 Planejado | Automação de operações |

### 📊 CRM & ERP
| Sistema | Status | Descrição |
|---|---|---|
| SellFlux | 🔄 Planejado | Automação de vendas |
| HELENACRM | 🔄 Planejado | Gestão de clientes |
| BOLTEN.IO | 🔄 Planejado | Integrações diversas |
| Agendor | 🔄 Planejado | Pipeline de vendas |
| VHSYS | 🔄 Planejado | ERP integrado |
| Mautic | 🔄 Planejado | E-mail marketing |
| DKW | 🔄 Planejado | Gestão de rede |

### 💹 Mercado Financeiro
| Módulo | Status | Descrição |
|---|---|---|
| B3 — Opções | 🔄 Planejado | Estratégias e cálculos automatizados |
| Apuração Tributária | 🔄 Planejado | Cálculo mensal de impostos |

---

## 🛠 Stack Tecnológico

```
Linguagens:     Python · JavaScript (ES6+) · TypeScript · Google Apps Script
Automação:      n8n (Docker) · Webhooks · APIs REST
IA:             Google Gemini API
Deploy:         Netlify · Cloudflare Pages
Controle:       Git · GitHub
OS:             Linux Pop!_OS (x86_64)
```

---

## 📁 Estrutura do Repositório

```
claude-code/
├── automations/        # Fluxos n8n e scripts de automação
├── integrations/       # Conectores com APIs externas (ML, Shopee, CRMs...)
├── web/                # Sites, landing pages e aplicativos web
├── finance/            # Módulos de mercado financeiro e apuração fiscal
├── scripts/            # Utilitários e scripts avulsos
├── docs/               # Documentação técnica
├── .env.example        # Variáveis de ambiente (modelo)
├── .gitignore          # Arquivos ignorados pelo Git
└── README.md           # Este arquivo
```

> ⚠️ **Nota:** A estrutura acima é o target de organização. Pastas são criadas conforme os módulos são desenvolvidos.

---

## 🚀 Como Começar

### Pré-requisitos

- Git instalado
- Node.js 18+ (para projetos web)
- Python 3.10+ (para automações)
- Docker (para n8n local)
- GitHub CLI `gh` (opcional)

### Instalação

```bash
# 1. Clone o repositório
git clone git@github.com:THGENGSOFT/claude-code.git
cd claude-code

# 2. Copie o arquivo de variáveis de ambiente
cp .env.example .env
# Edite o .env com suas chaves reais (NUNCA commite o .env)

# 3. Instale dependências conforme o módulo desejado
# Para projetos Node.js:
npm install
# Para projetos Python:
pip install -r requirements.txt
```

---

## 🔒 Segurança

Este projeto segue práticas **DevSecOps** rigorosas:

- ❌ **Nunca** commite arquivos `.env`, chaves de API ou senhas
- ✅ Use sempre variáveis de ambiente via `.env` (veja `.env.example`)
- ✅ O `.gitignore` já está configurado para bloquear arquivos sensíveis
- ✅ Dados de entrada sempre validados e sanitizados (prevenção de XSS, SQLi, CSRF)
- ✅ Rate limiting implementado em rotas críticas

```bash
# Arquivos protegidos pelo .gitignore:
.env
.env.local
.env.production
*.pem
*.key
node_modules/
__pycache__/
```

---

## 🔄 Fluxo de Trabalho Git

```bash
# Sincronizar novos arquivos com o GitHub
git add .
git commit -m "feat: descrição da mudança"
git push

# Padrão de commits (Conventional Commits):
# feat:     nova funcionalidade
# fix:      correção de bug
# docs:     atualização de documentação
# chore:    tarefas de manutenção
# refactor: refatoração de código
# style:    formatação e estilo
```

---

## 📝 Changelog

### [Não lançado]

- Estrutura inicial do repositório
- Configuração do README principal
- Definição da arquitetura Infrasphere

---

### v0.1.0 — 2026-09-28

- 🎉 Repositório criado e publicado no GitHub
- 🔧 Configuração inicial do Git com remote SSH
- 📄 README.md criado

---

<div align="center">

**Desenvolvido por [THGENGSOFT](https://github.com/THGENGSOFT) · Ecossistema Infrasphere**

</div>
