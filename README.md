# fabiodevito.com.br

Portfolio pessoal de Fábio Devito — jornalista e estrategista de conteúdo digital.

## Tecnologia

Site estático em HTML/CSS/JS puro, hospedado via **GitHub Pages** com domínio customizado (`fabiodevito.com.br`).

- Sem framework, sem build step
- Fontes: Roboto + Roboto Slab + Roboto Mono (Google Fonts) + FIT (Adobe Fonts / Typekit)
- CSS custom properties para paleta brutalista: `--ink`, `--paper`, `--accent`
- JavaScript vanilla para: troca de idioma (PT/EN/ES), animação de sprite, menu mobile

## Estrutura

```
/
├── index.html          # Página principal do portfólio
├── dicas-de-ia/
│   └── index.html      # Guia prático de IA para criativos e jornalistas
├── imagens/            # Assets estáticos (sprites, fotos, ícones)
├── CNAME               # Domínio customizado para GitHub Pages
└── README.md
```

## Páginas

| URL | Conteúdo |
|-----|----------|
| `fabiodevito.com.br` | Portfolio completo com experiência, destaques e contato |
| `fabiodevito.com.br/dicas-de-ia` | Manual do Escoteiro Mirim da IA — 24 capítulos + epílogo |

### Manual do Escoteiro Mirim da IA

Guia prático de IA para times criativos e jornalistas. Sem programação, com foco no raciocínio.

| Parte | Capítulos |
|-------|-----------|
| Parte 0 — Regras de Campo | 1. O que não colocar · 2. Quando NÃO usar IA · 3. A conta do tempo |
| Parte 1 — Fundamentos | 4–12: Prompt, Script, Prompt vs. Script, Agente, Skill, Quando usar qual, Pensamento lógico, Tokens e contexto, Alucinação |
| Parte 2 — Ferramentas e Modelos | 13–16: LLMs, Painel de ferramentas, Afinando o instrumento, Além do texto |
| Parte 3 — Fluxo de Trabalho | 17–20: Processo e documentação, Loops e checkpoints, Configurar um agente, Pesquisa com IA |
| Parte 5 — Organização e Escala | 21–24: Exportando conteúdo, GEO, Escalando para o time, Hackeando o sistema |
| Epílogo | Glossário do Escoteiro (12 termos) + Links Úteis |

> GIFs das Partes 3 e 5 pendentes — descomentar no HTML e adicionar URL quando disponível.

## Deploy

Push para `main` = deploy automático via GitHub Pages. Sem CI adicional.

## Contato

- [linkedin.com/in/fabiodevito](https://www.linkedin.com/in/fabiodevito/)
- [instagram.com/binhodevito](https://www.instagram.com/binhodevito/)
- devito.idc@gmail.com
