# Tutorial para rodar o Quarto

1. Instale o [Quarto](https://quarto.org/docs/get-started)
2. Clone o repositório da disciplina
3. Abra o terminal na pasta do repositório clonado
4. Publique o site no GitHub Pages.
   - `quarto publish gh-pages`
   - Obs.: Eu optei pelo zip, o meu comando para publicar o site foi `<caminho_para_o_quarto.exe> publish gh-pages`.
5. Configure o [GitHub Actions](https://quarto.org/docs/publishing/github-pages.html#github-action) para publicar automaticamente o site.

## Atualizar o GitHub Pages

1. Após alterados os arquivos do Quarto, rode o comando:
   - `quarto publish gh-pages`
   - (Caso você tenha instalado o Quarto)
