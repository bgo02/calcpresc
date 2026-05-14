# Calculadora de Prescrição Previdenciária — versão simples

Versão estática, sem React, sem Vite, sem build, sem GitHub Actions e sem dependências externas.

## Como publicar no GitHub Pages

1. Crie um novo repositório público no GitHub.
2. Faça upload do arquivo `index.html` na raiz do repositório.
3. Vá em `Settings` → `Pages`.
4. Em `Build and deployment`, escolha:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Salve.

A página deve ficar em:

`https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/`

## Observação

A lógica da calculadora foi portada para JavaScript puro dentro do próprio `index.html`.
