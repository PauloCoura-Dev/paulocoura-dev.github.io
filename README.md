# Paulo Coura · portfólio

Site pessoal em https://paulocoura-dev.github.io, em português e inglês (`#en` abre direto em inglês).

Um arquivo só, `index.html`, com HTML, CSS e JavaScript puros. Sem build e sem dependências. As fontes vêm do Google Fonts.

## Editar

- **Textos em português:** direto no HTML.
- **Textos em inglês:** no objeto `EN` do `<script>` no fim do arquivo. Cada chave corresponde a um `data-t` do HTML. Elemento sem chave no `EN` continua em português.
- **Diagrama do fluxo:** cada caixa tem 12 caracteres entre as barras `│`. Uma tradução com tamanho diferente desalinha o desenho.

## Ver localmente

```bash
python3 -m http.server 8000
```

Depois abra http://localhost:8000.

## Publicar

O GitHub Pages serve a branch `main` a partir da raiz. Cada `git push` atualiza o site em cerca de um minuto.
