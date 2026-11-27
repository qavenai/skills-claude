# Caio Bastos Tattoo — landing page

Página estática, sem build. Para publicar, suba a pasta inteira (`index.html` + `assets/`) em qualquer hospedagem estática (Netlify, Vercel, GitHub Pages, Cloudflare Pages).

- **3D:** mar e Farol da Barra em Three.js (r160, via jsDelivr), renderizados com sombra pontilhada no estilo da tatuagem. O mar reage ao mouse e ao toque. Ao rolar até o fim, a cena vira pôr do sol no farol.
- **Desempenho:** o 3D só desenha enquanto o topo ou o fim da página estão na tela, pausa com a aba oculta e respeita "reduzir movimento". Sem WebGL, a página mostra um fundo em gradiente.
- **WhatsApp:** todos os botões abrem `wa.me/5571992932165`. O formulário "Monte seu pedido" monta a mensagem com estilo, local, tamanho e ideia.
- **Fotos:** `assets/*.webp` foram recortadas de prints do Instagram. Troque pelos arquivos originais em alta quando o Caio enviar, mantendo os mesmos nomes.
