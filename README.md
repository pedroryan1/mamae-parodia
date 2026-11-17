# Mamãe, é Paródia!

App de humor com personagem fictício inspirado em Arthur Moledo do Val. Sem vínculo, endosso ou falas reais atribuídas a ele. A postura política exagerada é inventada para a paródia.

## Funcionalidades

- Oito perguntas políticas com respostas prontas, sem IA ou chave de API.
- Conversa por temas, com histórico salvo somente no navegador.
- Boneco em SVG com animação de boca durante a digitação.
- Leitura opcional com voz sintética padrão do navegador, sem clonagem de voz.
- Interface responsiva.

## Executar

Abra `dist/index.html` no navegador. Os arquivos HTML, CSS e JavaScript não precisam de compilação. As fontes usam Google Fonts; a interface tem fontes alternativas quando estiver sem internet. A disponibilidade da voz depende do navegador e do sistema.

## Publicar

O workflow `.github/workflows/pages.yml` publica a pasta `dist` após alterações na branch `main`. Nas configurações do repositório, a origem do GitHub Pages deve ser **GitHub Actions**.

## Editar o humor

As perguntas e respostas políticas estão em `politicalQA`, no arquivo `dist/app.js`. A ilustração está em `dist/index.html`; os estilos e animações ficam em `dist/style.css`.
