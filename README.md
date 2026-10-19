# ODDS — apresentação

Apresentação do **ODDS (Open Domain Driven Specification)**: uma linguagem para
escrever o espaço do problema do DDD (domínio, subdomínios, contextos e as relações
entre eles) como texto, validado e desenhado como mapa no navegador.

- `index.html` — a apresentação, em slides de tela cheia
- `playground.html` — o playground da demo; `?modelo=pagamentos` abre o recorte de
  Pagamentos do BIAN, incoerente de propósito, com o botão **Tornar coerente**

Tudo roda no navegador, sem servidor e sem dado saindo da máquina. As duas páginas
funcionam abertas direto do disco ou servidas pelo GitHub Pages.

## Apresentar

| Tecla | O quê |
|---|---|
| → / espaço · ← | avança · volta |
| F | tela cheia |
| P | abre as notas numa janela à parte (para o monitor do notebook) |
| N | mostra as notas sobre o slide |
| A | apêndice, e volta |

`index.html` abre a versão de 30 minutos; `index.html?v=60`, a de 1 hora.

Gerado por `docs/design/pages/apresentacao.export.mjs`, a partir do commit `89a4bf1`
do repositório de trabalho. Não edite aqui: a fonte é lá.
