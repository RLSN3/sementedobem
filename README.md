# Empório Semente do Bem

Site institucional do Empório Semente do Bem: 6 lojas de produtos naturais, vitaminas e suplementos em Macapá, Oiapoque (AP) e Santarém (PA).

Domínio: https://sementedobem.rlsn.com.br

## Estrutura

```
index.html          página principal
404.html            página de erro
assets/             imagens (WebP), ícones e imagem de compartilhamento
favicon.ico         ícone da aba
site.webmanifest    ícone ao salvar na tela inicial do celular
robots.txt          regras para buscadores
sitemap.xml         mapa do site para o Google
CNAME               domínio personalizado do GitHub Pages
.nojekyll           publica os arquivos como estão, sem processamento
```

## Publicar no GitHub Pages

1. Envie todos os arquivos desta pasta para a raiz do repositório (branch `main`).
2. No repositório: Settings > Pages > Build and deployment > Source: **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Em Settings > Pages > Custom domain, confirme `sementedobem.rlsn.com.br` e marque **Enforce HTTPS** quando liberar.
4. No DNS do domínio `rlsn.com.br`, crie um registro **CNAME**: nome `sementedobem`, valor `SEU-USUARIO.github.io`.

## Atualizar conteúdo

- Lojas, telefones e endereços: lista `LOJAS` no final do `index.html` e dados estruturados (`application/ld+json`) no topo.
- Mensagens do WhatsApp: variáveis `MSG` e `MSG_SUP` no `index.html`.
- Ao trocar o domínio: atualize `CNAME`, `robots.txt`, `sitemap.xml` e as URLs `https://sementedobem.rlsn.com.br/` no topo do `index.html`.

---
Realizado por [RLSN · Railson Lima](https://www.instagram.com/railsonnlima/)
