# 📋 Plano do projeto: Mini-SK-29-10-G (1)

_Gerado em 29/10/2026, 16:32:11 — sem IA, lendo os arquivos._

## 📊 Visão geral
| Item | Valor |
|---|---|
| Arquivos | 70 |
| Linhas | 14.735 |
| Telas/páginas | 1 |
| Rotas do backend | 3 |
| Chamadas do app | 1 |
| Tabelas do banco | 0 |
| Variáveis de ambiente | 8 |

**Linguagens:** JavaScript (63), Imagem (2), CSS (1), HTML (1), Outros (1), Markdown (1), JSON (1)

## 💡 O que fazer (em ordem)
1. 🧹 Tirar a Replit de 17 arquivo(s) (🏗️ Preparar → Fazer tudo)
2. 🖥️ O projeto tem backend próprio: para funcionar fora da Replit ele precisa ficar ligado num servidor (Render, Railway, Vercel) ou virar funções
3. 🔐 Criar um .env.example com: BASE_PATH, DADOS_EM, GITHUB_STEP_SUMMARY, LOCALAPPDATA, PONTE_BASE, PONTE_CODIGO, PONTE_PORTA, TESTE_SAIR (os valores você coloca no servidor, nunca no código)
4. 📝 Criar um README.md explicando como rodar
5. 🚫 Criar .gitignore (não mandar node_modules ao GitHub)

## 🚀 Por onde começa
- `index.html`

## 📱 Telas e páginas
| Endereço | Arquivo |
|---|---|
| `index.html` | index.html |

## 🖥️ Rotas do backend
| Método | Rota | Arquivo |
|---|---|---|
| USE | `/api/x` | js/98b-rotas.js |
| GET | `/y` | js/98b-rotas.js |
| GET | `/x` | js/98b-rotas.js |

## 📡 O que o app pede ao servidor
| Método | Endereço | Onde |
|---|---|---|
| POST | `/api/x` | js/98b-rotas.js |

## 🔌 O que falta no backend
✅ Tudo que o app chama tem rota no projeto (ou o app não usa servidor).

## 💤 Rotas que o app não usa
- GET `/y` — js/98b-rotas.js

## 🗄️ Banco de dados
_Nenhuma tabela encontrada._

## 🔐 Variáveis de ambiente (configurar no servidor)
- `BASE_PATH`
- `DADOS_EM`
- `GITHUB_STEP_SUMMARY`
- `LOCALAPPDATA`
- `PONTE_BASE`
- `PONTE_CODIGO`
- `PONTE_PORTA`
- `TESTE_SAIR`

_Só os nomes. Os valores (chaves, senhas) nunca vão no código nem no GitHub._

## 🤖 IA usada
- api.groq.com
- console.groq.com
- generativelanguage.googleapis.com
- openrouter.ai
- api.anthropic.com
- console.anthropic.com
- api.openai.com
- platform.openai.com

## 🌐 Serviços de fora que ele acessa
- aistudio.google.com
- api.allorigins.win
- api.anthropic.com
- api.deepseek.com
- api.exemplo.com
- api.expo.dev
- api.github.com
- api.groq.com
- api.npms.io
- api.openai.com
- api.perplexity.ai
- api.x.ai
- appassets.androidplatform.net
- cdn.jsdelivr.net
- cdn.tailwindcss.com
- console.anthropic.com
- console.groq.com
- console.x.ai
- duckduckgo.com
- esm.sh
- expo.dev
- generativelanguage.googleapis.com
- github.com
- html.duckduckgo.com
- lite.duckduckgo.com
- mail.google.com
- ollama.com
- openapi.monica.im
- openrouter.ai
- platform.monica.im
- platform.openai.com
- pt.wikipedia.org
- r.jina.ai
- raw.github.com
- registry.npmjs.org
- seu-usuario.github.io
- stuartk.com
- stuk.github.io
- u.expo.dev
- unpkg.com
- www.google.com
- www.npmjs.com
- www.perplexity.ai
- xxxx.supabase.co

## 🧹 Arquivos com coisa da Replit
- js/20-zip.js
- js/50-tree.js
- js/70-search.js
- js/80-ai.js
- js/86-terminal.js
- js/86c-termux.js
- js/88-inventario.js
- js/90-github.js
- js/95-pwa.js
- js/96b-eas.js
- js/96c-preparar.js
- js/97-analise.js
- js/97d-faxina.js
- js/lib/expo-core.js
- js/lib/guia-maikon.js
- js/lib/plano-core.js
- js/lib/receita-core.js

## 🔁 Roteiro para recriar fora da Replit
1. Importar o projeto no Mini SK e tocar em 🏗️ Preparar → ✅ Fazer tudo (tira a Replit, cria os arquivos que faltam).
2. Backend: escolher onde ele vai ficar ligado (Render/Railway grátis) — ou pedir à IA para transformar as rotas em funções do Netlify/Vercel, usando a tabela "O que falta no backend".
3. Variáveis: cadastrar 8 variável(is) no servidor (lista acima).
4. Testar a prévia; se der erro, 🤖 Mandar os erros para a IA.
5. App: 📲 Instalável (PWA), 📦 APK ou 🖥️ Desktop (.exe) pelo 🏗️ Preparar.

## 🌳 Árvore de arquivos
```
├─ 📁 css/
│  └─ app.css
├─ 📁 icons/
│  ├─ icon-192.png
│  └─ icon-512.png
├─ 📁 js/
│  ├─ 📁 lib/
│  │  ├─ 📁 lab/
│  │  │  ├─ 30-analise.js
│  │  │  └─ 50-comparar.js
│  │  ├─ 📁 picotador/
│  │  │  ├─ 00-base.js
│  │  │  ├─ 10-ler.js
│  │  │  ├─ 20-projetos.js
│  │  │  └─ 30-mensagens.js
│  │  ├─ acorn.min.js
│  │  ├─ cofre-arquivo.js
│  │  ├─ expo-core.js
│  │  ├─ guia-maikon.js
│  │  ├─ jszip.min.js
│  │  ├─ nacl-fast.min.js
│  │  ├─ plano-core.js
│  │  ├─ ponte-termux.cjs.txt
│  │  ├─ receita-core.js
│  │  └─ selar.js
│  ├─ 00-core.js
│  ├─ 04-conta.js
│  ├─ 10-fs.js
│  ├─ 20-zip.js
│  ├─ 30-highlight.js
│  ├─ 40-editor.js
│  ├─ 50-tree.js
│  ├─ 60-preview.js
│  ├─ 61-tsx.js
│  ├─ 70-search.js
│  ├─ 80-ai.js
│  ├─ 80b-web.js
│  ├─ 81-gasto.js
│  ├─ 83-voz.js
│  ├─ 84-ponte.js
│  ├─ 85-checkpoints.js
│  ├─ 86-terminal.js
│  ├─ 86b-node.js
│  ├─ 86c-termux.js
│  ├─ 86e-atalhos.js
│  ├─ 86f-pasta-viva.js
│  ├─ 86g-largura.js
│  ├─ 86h-node-extra.js
│  ├─ 87-links.js
│  ├─ 88-inventario.js
│  ├─ 89-config.js
│  ├─ 89b-cacador.js
│  ├─ 90-github.js
│  ├─ 91-acoes.js
│  ├─ 91b-publicar.js
│  ├─ 92-playground.js
│  ├─ 92c-importar.js
│  ├─ 93-conversa.js
│  ├─ 94-fatiador.js
│  ├─ 95-pwa.js
│  ├─ 96-apk.js
│  ├─ 96b-eas.js
│  ├─ 96c-preparar.js
│  ├─ 96d-exe-minisk.js
│  ├─ 96e-exe-python.js
│  ├─ 97-analise.js
│  ├─ 97b-cacabug.js
│  ├─ 97c-modularizar.js
│  ├─ 97d-faxina.js
│  ├─ 98-api.js
│  ├─ 98b-rotas.js
│  └─ 99-app.js
├─ index.html
├─ LEIA-ME.md
├─ manifest.json
└─ sw.js
```
