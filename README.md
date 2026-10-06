# Honda Seguros - Protótipo do Assistente Virtual (Cards)

Protótipo interativo em cards que simula a experiência do cliente no assistente virtual, seguindo o fluxograma da Honda Seguros.

## Como usar

- **Online:** abra o link do GitHub Pages do repositório.
- **Local:** baixe o repositório e dê duplo clique em `index.html`. Não precisa de servidor nem de internet.

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | Protótipo completo (HTML, CSS e JavaScript em um único arquivo) |
| `flow.json` | Fluxo em JSON (telas, textos e opções), para consulta |
| `.nojekyll` | Faz o GitHub Pages servir os arquivos sem processamento |

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos para a raiz (**Add file** > **Upload files**).
2. Vá em **Settings** > **Pages**.
3. Em **Source**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`, e salve.
4. Após 1 a 2 minutos, o link aparece no formato `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Ajustar o fluxo

Os textos e as ramificações ficam no bloco `<script id="flow-data">` do `index.html`. O `flow.json` é uma cópia do mesmo conteúdo.

> Protótipo para validação. Confira as informações com as áreas responsáveis antes do uso oficial.
