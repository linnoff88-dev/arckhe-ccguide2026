# Plano de ImplementaÃ§Ã£o: 3 Novas Trilhas Claude Code

## VisÃ£o Geral

CriaÃ§Ã£o de 3 novas trilhas baseadas em conteÃºdo existente:
- **Trilha 4**: MiniCurso18 (18 capÃ­tulos consolidados)
- **Trilha 5**: 95CC - AutomaÃ§Ã£o (WAT framework + deploy)
- **Trilha 6**: BeginCC - Guia do Iniciante (nÃ£o-tÃ©cnicos)

**Total de arquivos**: 27 novos HTML + ediÃ§Ã£o do index.html principal

---

## Trilha 4: MiniCurso18 ðŸŸ  (Amber)

**Fonte:** `doc/minicurso18capitulos/` (18 capÃ­tulos consolidados em 8 mÃ³dulos)
**Foco:** Curso completo e abrangente, do bÃ¡sico ao avanÃ§ado
**Cor:** `text-amber-400`, `bg-amber-500/20`, `border-amber-500/30`

### MÃ³dulos

| MÃ³dulo | CapÃ­tulos Base | TÃ­tulo | 6 TÃ³picos |
|--------|---------------|--------|-----------|
| 4.1 | Cap 1-2 | IntroduÃ§Ã£o ao Claude Code | PÃºblico-alvo, O que Ã©, Paradigma shift, DiferenÃ§as de outras ferramentas, Conceito de vibe coding, Posicionamento no mercado |
| 4.2 | Cap 3-4 | Diferencial e InstalaÃ§Ã£o | Subagentes paralelos, Context window 1M, ComparaÃ§Ã£o Cursor/Windsurf, PrÃ©-requisitos, Node.js, Conta Anthropic |
| 4.3 | Cap 5-6 | Primeiro Contato e Projeto | Terminal vs Warp vs Claudia, Comandos bÃ¡sicos, Modo dangerously, Estrutura HTML/CSS/JS, Feedback em tempo real, IteraÃ§Ãµes |
| 4.4 | Cap 7-8 | PRDs e Agentes | Modo Planning, PRDs automÃ¡ticos, Claude como PM, CriaÃ§Ã£o de agentes, subagents.cc, OrquestraÃ§Ã£o paralela |
| 4.5 | Cap 9-10 | MCP e Comandos | Conceito MCP, Playwright/Exa/Firecrawl, Slash commands, Modos think, CustomizaÃ§Ã£o, /security review |
| 4.6 | Cap 11-14 | OrganizaÃ§Ã£o e Custos | SessÃµes modulares, claude.md, ReduÃ§Ã£o de alucinaÃ§Ãµes, Tokens Sonnet vs Opus, RelatÃ³rios de uso, OtimizaÃ§Ã£o |
| 4.7 | Cap 15-16 | Hooks e SeguranÃ§a | Output style, NotificaÃ§Ãµes, PreToolUse/PostToolUse, settings.json, Auditoria de vulnerabilidades, Limites |
| 4.8 | Cap 17-18 | Casos AvanÃ§ados e Futuro | Sistema financeiro, AutomaÃ§Ã£o jurÃ­dica, E-learning adaptativo, Supply chain, DiagnÃ³stico mÃ©dico, TendÃªncias futuras |

---

## Trilha 5: 95CC - AutomaÃ§Ã£o ðŸ©µ (Teal)

**Fonte:** `doc/95cc/` (vÃ­deo 36 min + WAT framework)
**Foco:** Construir automaÃ§Ãµes prÃ¡ticas e deploy em produÃ§Ã£o
**Cor:** `text-teal-400`, `bg-teal-500/20`, `border-teal-500/30`

### MÃ³dulos

| MÃ³dulo | TÃ­tulo | 6 TÃ³picos |
|--------|--------|-----------|
| 5.1 | Interface e Ambiente | VS Code + extensÃ£o Claude Code, Estrutura de projetos, Explorer, Bypass permissions, Plan mode, Agente vs arquivos |
| 5.2 | Framework WAT | Workflows (instruÃ§Ãµes MD), Agents (decisÃ£o), Tools (execuÃ§Ã£o .py), Self-improvement loop, Estrutura de pastas, Sistema .env |
| 5.3 | Planejamento com IA | claude.md como system prompt, Plan mode detalhado, Perguntas do agente, Auto-accept changes, To-do list visual, IteraÃ§Ã£o de planos |
| 5.4 | Construindo Tools | Python scripts executÃ¡veis, API integrations, Data transformations, DependÃªncias e instalaÃ§Ã£o, Erro e correÃ§Ã£o, Tool validation |
| 5.5 | MCP Servers AvanÃ§ados | Exa para pesquisa web, Playwright (Microsoft), InstalaÃ§Ã£o via CLI, Testes de conexÃ£o, Combinando MCPs, SeguranÃ§a de MCPs |
| 5.6 | Skills Personalizados | DiferenÃ§a Skills vs MCP, Skills globais vs projeto, Canvas design skill, InstalaÃ§Ã£o de skills, Criando skills prÃ³prios, cloudcode-templates |
| 5.7 | Deploy no Modal | Modal.com infraestrutura, Cron triggers, Webhook triggers, Secrets management, Security review, Logs e monitoramento |
| 5.8 | Workflow Completo | YouTube Analytics exemplo, Scraping + anÃ¡lise + slides, PDF geraÃ§Ã£o, Email sending, Google Sheets export, ProduÃ§Ã£o automatizada |

---

## Trilha 6: BeginCC - Guia do Iniciante ðŸŒ¹ (Rose)

**Fonte:** `doc/begincc/` (guia completo para iniciantes)
**Foco:** Pessoas nÃ£o-tÃ©cnicas, conceitos acessÃ­veis
**Cor:** `text-rose-400`, `bg-rose-500/20`, `border-rose-500/30`

### MÃ³dulos

| MÃ³dulo | TÃ­tulo | 6 TÃ³picos |
|--------|--------|-----------|
| 6.1 | Por que Claude Code? | Hype explicado, Superhumano com IA, Paradigma shift, Cursor vs Claude Code, NÃ£o precisa saber programar, Investimento vs Resultado |
| 6.2 | Subagentes e Poder | Conceito de subagentes, Paralelo vs sequencial, Context window 1 milhÃ£o, Ramming de codebase, Shelf life de conversas, Fresh slate |
| 6.3 | InstalaÃ§Ã£o Passo a Passo | Node.js download, npm install claude, Warp como alternativa, Primeiro comando "claude", Planos Anthropic ($20 vs $100-200), Login e autenticaÃ§Ã£o |
| 6.4 | Cursor + Claude Code | VS Code/Cursor integraÃ§Ã£o, ExtensÃ£o Claude Code, Terminal dentro do editor, Dois AIs lado a lado, Run Cloud Code button, MÃºltiplas sessÃµes |
| 6.5 | Seu Primeiro Site | claude dangerously skip, Prompt para website, Auto-building de arquivos, @ para targets especÃ­ficos, Ask mode (shift+tab), Planning mode com Opus |
| 6.6 | MCPs Explicados | MCP como portas/senhas, Servidor Ãºnico = mÃºltiplas aÃ§Ãµes, Playwright para browser, Exa para pesquisa, Cipher para memÃ³ria, Importar do Claude Desktop |
| 6.7 | Agentes Especializados | /agents comando, Gerar vs configurar manual, subagents.cc repositÃ³rio, Designer, QA, PM agentes, OrquestraÃ§Ã£o multi-agente, Cores de identificaÃ§Ã£o |
| 6.8 | Dominando o Workflow | Slash commands (/clear, /compact, /resume), Output style, Security review, Think modes, Hooks para sons, settings.json, Claudia wrapper, Modular building |

---

## Estrutura de Arquivos

```
curso/
â”œâ”€â”€ trilha4/
â”‚   â”œâ”€â”€ index.html          # Landing da Trilha 4 (MiniCurso18)
â”‚   â”œâ”€â”€ modulo-4-1.html
â”‚   â”œâ”€â”€ modulo-4-2.html
â”‚   â”œâ”€â”€ modulo-4-3.html
â”‚   â”œâ”€â”€ modulo-4-4.html
â”‚   â”œâ”€â”€ modulo-4-5.html
â”‚   â”œâ”€â”€ modulo-4-6.html
â”‚   â”œâ”€â”€ modulo-4-7.html
â”‚   â””â”€â”€ modulo-4-8.html
â”œâ”€â”€ trilha5/
â”‚   â”œâ”€â”€ index.html          # Landing da Trilha 5 (95CC AutomaÃ§Ã£o)
â”‚   â”œâ”€â”€ modulo-5-1.html
â”‚   â”œâ”€â”€ modulo-5-2.html
â”‚   â”œâ”€â”€ modulo-5-3.html
â”‚   â”œâ”€â”€ modulo-5-4.html
â”‚   â”œâ”€â”€ modulo-5-5.html
â”‚   â”œâ”€â”€ modulo-5-6.html
â”‚   â”œâ”€â”€ modulo-5-7.html
â”‚   â””â”€â”€ modulo-5-8.html
â”œâ”€â”€ trilha6/
â”‚   â”œâ”€â”€ index.html          # Landing da Trilha 6 (BeginCC)
â”‚   â”œâ”€â”€ modulo-6-1.html
â”‚   â”œâ”€â”€ modulo-6-2.html
â”‚   â”œâ”€â”€ modulo-6-3.html
â”‚   â”œâ”€â”€ modulo-6-4.html
â”‚   â”œâ”€â”€ modulo-6-5.html
â”‚   â”œâ”€â”€ modulo-6-6.html
â”‚   â”œâ”€â”€ modulo-6-7.html
â”‚   â””â”€â”€ modulo-6-8.html
â””â”€â”€ index.html (principal - atualizar com 3 novos cards)
```

---

## PadrÃµes TÃ©cnicos

### Cores por Trilha

| Trilha | Cor | Text Class | Background Class | Border Class |
|--------|-----|------------|------------------|--------------|
| T4 MiniCurso18 | Amber | `text-amber-400` | `bg-amber-500/20` | `border-amber-500/30` |
| T5 95CC | Teal | `text-teal-400` | `bg-teal-500/20` | `border-teal-500/30` |
| T6 BeginCC | Rose | `text-rose-400` | `bg-rose-500/20` | `border-rose-500/30` |

### Checklist de PÃ¡gina (ref/CHECKLIST_REVISAO.md)

- [ ] ARCKHÉ AI link com `text-sky-400` ao lado do logo
- [ ] Light mode CSS override block em `<style>`
- [ ] Theme toggle funcionando
- [ ] BotÃµes alinhados Ã  esquerda (`justify-start`)
- [ ] NÃºmeros de tÃ³picos em badges circulares (`w-6 h-6 rounded-full`)
- [ ] 3 seÃ§Ãµes por tÃ³pico: "O que Ã©", "Por que aprender", "Conceitos-chave"
- [ ] JavaScript para toggleTopic, theme toggle, modais

### Template Base

Usar `ref/MASTER_COMPLETO.md` como referÃªncia para componentes HTML/CSS/JS.

---

## Fontes de ConteÃºdo

| Trilha | Pasta | Arquivos Principais |
|--------|-------|---------------------|
| T4 | `doc/minicurso18capitulos/` | 18 arquivos .md (CapÃ­tulo 1-18) |
| T5 | `doc/95cc/` | 95CC.txt, CLAUDE (2) (1).md |
| T6 | `doc/begincc/` | (369) The Complete Beginner's Guide.txt |

---

## EstratÃ©gia de ImplementaÃ§Ã£o

1. **Criar diretÃ³rios**: trilha4/, trilha5/, trilha6/
2. **Criar index.html** de cada trilha (3 arquivos)
3. **Criar mÃ³dulos em paralelo** usando 3 agentes
4. **Atualizar index.html principal** com novos cards
5. **QA final** para validar links, navegaÃ§Ã£o, conteÃºdo

**Estimativa**: 27 arquivos HTML novos + 1 ediÃ§Ã£o
