# Alterações desta rodada (fontes, cores, rótulos, limpeza)

- `tailwind.config.js`: `cyan-dark` de #009E99 para #006B68 (contraste de 2,5:1 para 4,8:1 em fundo claro).
- Cores de texto cinza fracas trocadas por #55605D / #4C5955 (claro) e #9FB0AB (escuro).
- Rótulos: removidos `font-mono`, caixa alta, tracking largo e numeração "01 /" (18 ocorrências). Tamanhos < 12 px passam a 12 px (tsx e css).
- Textos: "THE GAP", "REAL → PERCEIVED", "DEW POINT / 00", "Make value visible.", "Digital Value Studio" e "GEO Strategy" em português; "utilizador/contacto" para "visitante/contato"; travessões removidos.
- `index.html`: JetBrains Mono agora pede 400/600/700 (evita negrito falso); `theme-color` #E9E8E3.
- Páginas legais convertidas para o visual claro. Rodapé: "Indaiatuba & RMC" virou "Branding" e links com barra final.
- `/seo-geo/`: alt "Orval'IA Studio" corrigido.
- Limpeza: 49 scripts soltos, zip aninhado, `dist-server`, `sitemap.xml.xml`, 14 componentes mortos e 3 dependências sem uso removidos.
- Build OK e `verify-blog`, `verify-navigation`, `verify-sharing` passam.

## Não alterado (decisão sua)
- `public/proposta/gss` ainda está em `public/` (PDFs e áudios de proposta de cliente).
- `vercel.json` (reescreve tudo para `/`) convive com o deploy em GitHub Pages.
- E-mail `orvaliastudio@gmail.com`, nome "Bruno Correa Gomes", foto de stock em `/seo-geo/`, imagens de Beth e Marta no `i.ibb.co`.
