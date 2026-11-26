# Estúdio Pet Feliz – Página de vendas

Site estático (`index.html`), publicado via GitHub Pages.

## Domínio personalizado
1. Crie o arquivo `CNAME` com seu domínio (ex.: `www.seudominio.com.br`).
2. No provedor do domínio, configure o DNS:
   - `www` → CNAME → `<usuario>.github.io`
   - Domínio raiz (apex) → registros A: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
3. GitHub → Settings → Pages → Source: branch `main` / root → Custom domain → marque "Enforce HTTPS".
