# Plano de ImplementaêÂ§êÂ£o: 3 Novas Trilhas Claude Code

## VisêÂ£o Geral

CriaêÂ§êÂ£o de 3 novas trilhas baseadas em conteêÂºdo existente:
- **Trilha 4**: MiniCurso18 (18 capêÂ­tulos consolidados)
- **Trilha 5**: 95CC - AutomaêÂ§êÂ£o (WAT framework + deploy)
- **Trilha 6**: BeginCC - Guia do Iniciante (nêÂ£o-têÂ©cnicos)

**Total de arquivos**: 27 novos HTML + ediêÂ§êÂ£o do index.html principal

---

## Trilha 4: MiniCurso18 ê°Å¸Å¸Â  (Amber)

**Fonte:** `doc/minicurso18capitulos/` (18 capêÂ­tulos consolidados em 8 mêÂ³dulos)
**Foco:** Curso completo e abrangente, do bêÂ¡sico ao avanêÂ§ado
**Cor:** `text-amber-400`, `bg-amber-500/20`, `border-amber-500/30`

### MêÂ³dulos

| MêÂ³dulo | CapêÂ­tulos Base | TêÂ­tulo | 6 TêÂ³picos |
|--------|---------------|--------|-----------|
| 4.1 | Cap 1-2 | IntroduêÂ§êÂ£o ao Claude Code | PêÂºblico-alvo, O que êÂ©, Paradigma shift, DiferenêÂ§as de outras ferramentas, Conceito de vibe coding, Posicionamento no mercado |
| 4.2 | Cap 3-4 | Diferencial e InstalaêÂ§êÂ£o | Subagentes paralelos, Context window 1M, ComparaêÂ§êÂ£o Cursor/Windsurf, PrêÂ©-requisitos, Node.js, Conta Anthropic |
| 4.3 | Cap 5-6 | Primeiro Contato e Projeto | Terminal vs Warp vs Claudia, Comandos bêÂ¡sicos, Modo dangerously, Estrutura HTML/CSS/JS, Feedback em tempo real, IteraêÂ§êÂµes |
| 4.4 | Cap 7-8 | PRDs e Agentes | Modo Planning, PRDs automêÂ¡ticos, Claude como PM, CriaêÂ§êÂ£o de agentes, subagents.cc, OrquestraêÂ§êÂ£o paralela |
| 4.5 | Cap 9-10 | MCP e Comandos | Conceito MCP, Playwright/Exa/Firecrawl, Slash commands, Modos think, CustomizaêÂ§êÂ£o, /security review |
| 4.6 | Cap 11-14 | OrganizaêÂ§êÂ£o e Custos | SessêÂµes modulares, claude.md, ReduêÂ§êÂ£o de alucinaêÂ§êÂµes, Tokens Sonnet vs Opus, RelatêÂ³rios de uso, OtimizaêÂ§êÂ£o |
| 4.7 | Cap 15-16 | Hooks e SeguranêÂ§a | Output style, NotificaêÂ§êÂµes, PreToolUse/PostToolUse, settings.json, Auditoria de vulnerabilidades, Limites |
| 4.8 | Cap 17-18 | Casos AvanêÂ§ados e Futuro | Sistema financeiro, AutomaêÂ§êÂ£o jurêÂ­dica, E-learning adaptativo, Supply chain, DiagnêÂ³stico mêÂ©dico, TendêÂªncias futuras |

---

## Trilha 5: 95CC - AutomaêÂ§êÂ£o ê°Å¸Â©Âµ (Teal)

**Fonte:** `doc/95cc/` (vêÂ­deo 36 min + WAT framework)
**Foco:** Construir automaêÂ§êÂµes prêÂ¡ticas e deploy em produêÂ§êÂ£o
**Cor:** `text-teal-400`, `bg-teal-500/20`, `border-teal-500/30`

### MêÂ³dulos

| MêÂ³dulo | TêÂ­tulo | 6 TêÂ³picos |
|--------|--------|-----------|
| 5.1 | Interface e Ambiente | VS Code + extensêÂ£o Claude Code, Estrutura de projetos, Explorer, Bypass permissions, Plan mode, Agente vs arquivos |
| 5.2 | Framework WAT | Workflows (instruêÂ§êÂµes MD), Agents (decisêÂ£o), Tools (execuêÂ§êÂ£o .py), Self-improvement loop, Estrutura de pastas, Sistema .env |
| 5.3 | Planejamento com IA | claude.md como system prompt, Plan mode detalhado, Perguntas do agente, Auto-accept changes, To-do list visual, IteraêÂ§êÂ£o de planos |
| 5.4 | Construindo Tools | Python scripts executêÂ¡veis, API integrations, Data transformations, DependêÂªncias e instalaêÂ§êÂ£o, Erro e correêÂ§êÂ£o, Tool validation |
| 5.5 | MCP Servers AvanêÂ§ados | Exa para pesquisa web, Playwright (Microsoft), InstalaêÂ§êÂ£o via CLI, Testes de conexêÂ£o, Combinando MCPs, SeguranêÂ§a de MCPs |
| 5.6 | Skills Personalizados | DiferenêÂ§a Skills vs MCP, Skills globais vs projeto, Canvas design skill, InstalaêÂ§êÂ£o de skills, Criando skills prêÂ³prios, cloudcode-templates |
| 5.7 | Deploy no Modal | Modal.com infraestrutura, Cron triggers, Webhook triggers, Secrets management, Security review, Logs e monitoramento |
| 5.8 | Workflow Completo | YouTube Analytics exemplo, Scraping + anêÂ¡lise + slides, PDF geraêÂ§êÂ£o, Email sending, Google Sheets export, ProduêÂ§êÂ£o automatizada |

---

## Trilha 6: BeginCC - Guia do Iniciante ê°Å¸ÅÂ¹ (Rose)

**Fonte:** `doc/begincc/` (guia completo para iniciantes)
**Foco:** Pessoas nêÂ£o-têÂ©cnicas, conceitos acessêÂ­veis
**Cor:** `text-rose-400`, `bg-rose-500/20`, `border-rose-500/30`

### MêÂ³dulos

| MêÂ³dulo | TêÂ­tulo | 6 TêÂ³picos |
|--------|--------|-----------|
| 6.1 | Por que Claude Code? | Hype explicado, Superhumano com IA, Paradigma shift, Cursor vs Claude Code, NêÂ£o precisa saber programar, Investimento vs Resultado |
| 6.2 | Subagentes e Poder | Conceito de subagentes, Paralelo vs sequencial, Context window 1 milhêÂ£o, Ramming de codebase, Shelf life de conversas, Fresh slate |
| 6.3 | InstalaêÂ§êÂ£o Passo a Passo | Node.js download, npm install claude, Warp como alternativa, Primeiro comando "claude", Planos Anthropic ($20 vs $100-200), Login e autenticaêÂ§êÂ£o |
| 6.4 | Cursor + Claude Code | VS Code/Cursor integraêÂ§êÂ£o, ExtensêÂ£o Claude Code, Terminal dentro do editor, Dois AIs lado a lado, Run Cloud Code button, MêÂºltiplas sessêÂµes |
| 6.5 | Seu Primeiro Site | claude dangerously skip, Prompt para website, Auto-building de arquivos, @ para targets especêÂ­ficos, Ask mode (shift+tab), Planning mode com Opus |
| 6.6 | MCPs Explicados | MCP como portas/senhas, Servidor êÂºnico = mêÂºltiplas aêÂ§êÂµes, Playwright para browser, Exa para pesquisa, Cipher para memêÂ³ria, Importar do Claude Desktop |
| 6.7 | Agentes Especializados | /agents comando, Gerar vs configurar manual, subagents.cc repositêÂ³rio, Designer, QA, PM agentes, OrquestraêÂ§êÂ£o multi-agente, Cores de identificaêÂ§êÂ£o |
| 6.8 | Dominando o Workflow | Slash commands (/clear, /compact, /resume), Output style, Security review, Think modes, Hooks para sons, settings.json, Claudia wrapper, Modular building |

---

## Estrutura de Arquivos

```
curso/
ê¢âÅê¢ââ¬ê¢ââ¬ trilha4/
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ index.html          # Landing da Trilha 4 (MiniCurso18)
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-4-1.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-4-2.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-4-3.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-4-4.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-4-5.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-4-6.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-4-7.html
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ modulo-4-8.html
ê¢âÅê¢ââ¬ê¢ââ¬ trilha5/
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ index.html          # Landing da Trilha 5 (95CC AutomaêÂ§êÂ£o)
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-5-1.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-5-2.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-5-3.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-5-4.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-5-5.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-5-6.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-5-7.html
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ modulo-5-8.html
ê¢âÅê¢ââ¬ê¢ââ¬ trilha6/
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ index.html          # Landing da Trilha 6 (BeginCC)
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-6-1.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-6-2.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-6-3.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-6-4.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-6-5.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-6-6.html
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ modulo-6-7.html
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ modulo-6-8.html
ê¢ââê¢ââ¬ê¢ââ¬ index.html (principal - atualizar com 3 novos cards)
```

---

## PadrêÂµes TêÂ©cnicos

### Cores por Trilha

| Trilha | Cor | Text Class | Background Class | Border Class |
|--------|-----|------------|------------------|--------------|
| T4 MiniCurso18 | Amber | `text-amber-400` | `bg-amber-500/20` | `border-amber-500/30` |
| T5 95CC | Teal | `text-teal-400` | `bg-teal-500/20` | `border-teal-500/30` |
| T6 BeginCC | Rose | `text-rose-400` | `bg-rose-500/20` | `border-rose-500/30` |

### Checklist de PêÂ¡gina (ref/CHECKLIST_REVISAO.md)

- [ ] ARCKHê AI link com `text-sky-400` ao lado do logo
- [ ] Light mode CSS override block em `<style>`
- [ ] Theme toggle funcionando
- [ ] BotêÂµes alinhados êÂ  esquerda (`justify-start`)
- [ ] NêÂºmeros de têÂ³picos em badges circulares (`w-6 h-6 rounded-full`)
- [ ] 3 seêÂ§êÂµes por têÂ³pico: "O que êÂ©", "Por que aprender", "Conceitos-chave"
- [ ] JavaScript para toggleTopic, theme toggle, modais

### Template Base

Usar `ref/MASTER_COMPLETO.md` como referêÂªncia para componentes HTML/CSS/JS.

---

## Fontes de ConteêÂºdo

| Trilha | Pasta | Arquivos Principais |
|--------|-------|---------------------|
| T4 | `doc/minicurso18capitulos/` | 18 arquivos .md (CapêÂ­tulo 1-18) |
| T5 | `doc/95cc/` | 95CC.txt, CLAUDE (2) (1).md |
| T6 | `doc/begincc/` | (369) The Complete Beginner's Guide.txt |

---

## EstratêÂ©gia de ImplementaêÂ§êÂ£o

1. **Criar diretêÂ³rios**: trilha4/, trilha5/, trilha6/
2. **Criar index.html** de cada trilha (3 arquivos)
3. **Criar mêÂ³dulos em paralelo** usando 3 agentes
4. **Atualizar index.html principal** com novos cards
5. **QA final** para validar links, navegaêÂ§êÂ£o, conteêÂºdo

**Estimativa**: 27 arquivos HTML novos + 1 ediêÂ§êÂ£o
