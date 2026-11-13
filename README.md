# M Cookie's — loja/cardápio online

LP-loja da M Cookie's (doceria em São Paulo · @m_cookieee): cardápio interativo, caixa com desconto progressivo e pedido pronto para enviar pelo Direct do Instagram (ou WhatsApp, quando houver número).

- `index.html` — página completa (HTML/CSS/JS, sem dependências)
- `assets/` — vídeo, fotos dos sabores, fontes e favicon

**Configuração** (topo do `<script>` em `index.html`, objeto `CONFIG`):
- `whatsapp: ''` → pedido é copiado e o cliente cola no Direct da `instagramUser`
- `whatsapp: '5511999999999'` → pedido abre pronto no WhatsApp
- `launchDate` e `tiers` (faixas de desconto da caixa)

Desenvolvido por [Avory](https://www.avorybr.com/).
