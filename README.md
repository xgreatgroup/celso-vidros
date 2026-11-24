# Celso Vidros | Glass Works

Site institucional mantido pela XGreat.

## Publicação (24/11/2026)

- Repositório: `xgreatgroup/celso-vidros`, branch `main`.
- Cloudflare Pages: `celso-vidros`, deploy automático da raiz do repositório.
- Endereço principal: https://celsovidros.com.br/
- Endereço alternativo: https://www.celsovidros.com.br/ — redirecionamento 301 para o domínio principal, preservando caminho e parâmetros.
- Prévia: https://celso-vidros.pages.dev/
- Commits de implementação: CSS `76372ce`, JavaScript `f50125a`, homepage `851b990`.
- Ambos os domínios personalizados constavam como Active / SSL enabled no Pages.
- Registro.br: domínio publicado até 13/10/2027; nameservers jeff.ns.cloudflare.com e kira.ns.cloudflare.com, iguais aos da zona Cloudflare.
- DNS: CNAME do domínio principal e do www para `celso-vidros.pages.dev`, com proxy. MX e demais registros de e-mail/serviços preexistentes preservados.
- DNSSEC da zona Cloudflare permanece desativado; não foi alterado.

## Verificações

Página aberta no Pages e no domínio principal; www redirecionou para o domínio principal inclusive em página interna com parâmetro. HTTPS ativo. Imagens carregadas, links WhatsApp corretos, menu móvel funcional, galeria modal abriu, avançou e fechou; largura móvel sem rolagem horizontal.

## Pendências editoriais

- As três páginas legais ainda contêm texto provisório. Revisar conteúdo com o responsável antes de indexação.
- `index.html` mantém `noindex,follow`; `robots.txt` mantém `Disallow: /`. Após revisão das páginas legais, atualizar ambos e preencher `sitemap.xml`.
- Monitorar a entrega de e-mail no provedor já configurado, sem alterar MX, SPF e serviços relacionados sem necessidade comprovada.
