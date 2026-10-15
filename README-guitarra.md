# guitarra/index.html

Página oculta de estudo de guitarra — sem link em nenhum menu do site, acesso só por URL direta.

**URL:** `fabiodevito.com.br/guitarra/`

## O que é

App de uma página só (HTML/CSS/JS puro, sem build) com 4 abas:

| Aba | Conteúdo |
|-----|----------|
| Campo harmônico | Teoria do campo harmônico, tríades e tétrades, construtor de acordes interativo, escalas CAGED no braço, autoteste |
| Roda | Roda do ciclo de quintas (campo harmônico girável), com áudio sintetizado tocando os acordes |
| Dicionário | Dicionário de acordes CAGED — por campo harmônico ou por tônica, com diagramas de braço em SVG |
| Cronograma | Plano de estudo de uma semana com checkboxes (progresso salvo em `localStorage`) |

Todo o estado de UI (abas, filtros, checkboxes do cronograma) é mantido em `localStorage`/`location.hash`, sem backend.

## Por que está oculta

É uma ferramenta pessoal/para compartilhar com amigos, não faz parte do portfólio profissional — por isso não aparece em `index.html` nem em nenhum nav.

## Manutenção

Arquivo único e autocontido (`guitarra/index.html`), seguindo a mesma convenção do `dicas-de-ia/index.html`. Para atualizar, basta substituir o arquivo por uma nova versão gerada e commitar.
