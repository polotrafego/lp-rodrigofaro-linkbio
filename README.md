# LP Reduzida — Rodrigo Faro (link da bio)

Landing page enxuta do palestrante Rodrigo Faro: **hero → formulário**, mais página `/obrigado`.
Formulário conectado ao CRM do leadlovers (`mid=681453` / `fid=77727`) — não alterar ids/names dos campos.

```
index.html      # hero + formulário leadlovers
obrigado.html   # confirmação + botão WhatsApp
css/styles.css  # identidade visual + override do form001
js/main.js      # reveal on scroll
assets/img/     # fotos e logo Polo
vercel.json     # deploy estático (cleanUrls)
```

Rodar local: `npx --yes serve . -l 4330`

Deploy (Vercel): importar o repositório, Framework Preset `Other`, sem build command nem output directory.
No leadlovers, configurar a URL de redirecionamento pós-envio para `/obrigado`.
