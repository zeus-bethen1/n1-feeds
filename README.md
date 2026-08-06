# n1-feeds

Feeds de catálogo da N1 Goalkeeper, gerados a partir do PrestaShop e publicados
via GitHub Pages.

| Feed | URL |
|---|---|
| Meta (CSV) | https://zeus-bethen1.github.io/n1-feeds/meta_feed_es.csv |
| Google Shopping (XML) | https://zeus-bethen1.github.io/n1-feeds/google_feed_es.xml |

Atualizados 4×/dia (06/12/18/23h Madrid) pelo timer `n1-feeds.timer` no VPS.
Gerador: [`gen_feeds.py`](https://github.com/zeus-bethen1/n1-marketplaces) (repo privado).

**Porquê um repo público separado:** o Google Merchant Center e a Meta respeitam
`robots.txt`. O repo dos relatórios serve com `Disallow: /` e os feeds aí nunca
seriam lidos. O conteúdo destes ficheiros — nome, preço de venda, EAN, link,
imagem — é público por natureza; é o mesmo que está na loja.
