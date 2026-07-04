# Gerador de Súmulas

Gerador de súmulas (scorecards) para competições de cubo mágico, no estilo do
[Groupifier](https://github.com/jonatanklosko/groupifier). É uma única página
HTML, sem dependências de build ou servidor.

## Como rodar localmente

Basta abrir o arquivo `index.html` no navegador:

```bash
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

Ou, se preferir servir por HTTP (opcional):

```bash
python3 -m http.server 8000
```

E acesse [http://localhost:8000](http://localhost:8000).

Nenhuma instalação de dependências é necessária — o PDF é gerado no
navegador usando [pdfMake](https://pdfmake.github.io/docs/0.1/), carregado via
CDN.
