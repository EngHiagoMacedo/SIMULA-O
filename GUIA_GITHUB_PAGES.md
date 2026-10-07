# Publicar a Sistec Soluções no GitHub Pages

Este pacote já está pronto. Não é necessário instalar ferramentas nem executar build.

1. Extraia o ZIP no computador. Para conferir a plataforma antes da publicação, abra `index.html`. O botão **Baixar resumo em PDF** também funciona localmente.
2. Crie um repositório no GitHub, por exemplo `sistec-solucoes`.
3. Use **Add file > Upload files** para enviar os arquivos e a pasta `assets`. Envie o conteúdo da pasta extraída, não o arquivo ZIP. O `index.html` precisa ficar na raiz do repositório.
4. Confirme o envio com **Commit changes**, usando a branch `main`.
5. Acesse **Settings > Pages**. Em **Source**, escolha **Deploy from a branch**.
6. Em **Branch**, selecione **main** e **/(root)**. Clique em **Save**.
7. Aguarde a publicação e use a URL que aparecer em **Settings > Pages**.

Os caminhos são relativos, portanto a página funciona no endereço de um repositório, como `https://seu-usuario.github.io/sistec-solucoes/`. Esse endereço é apenas um exemplo de formato.

## O que está incluído

- Plataforma com a nova paleta azul, verde e amarelo.
- Nova logo Sistec Soluções, derivada da logo enviada.
- Simulação de 30% de desconto, com economia mensal e anual.
- Cópia do resumo e PDF A4 com logo, valores e projeções de 1, 6 e 12 meses.
- Biblioteca de PDF incluída no próprio pacote, sem CDN nem API.

## Referência oficial

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
