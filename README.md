# GitHub Pages

Site estatico pronto para publicacao no GitHub Pages.

## Estrutura

- `index.html`: pagina inicial
- `styles.css`: estilos da pagina
- `.github/workflows/pages.yml`: deploy automatico para o GitHub Pages

## Publicacao

1. Envie este repositorio para o GitHub.
2. Em **Settings > Pages**, selecione **GitHub Actions** como fonte de deploy.
3. A cada push na branch `main`, o workflow publica o site automaticamente.

O endereco normalmente sera `https://SEU_USUARIO.github.io/gpages/`.