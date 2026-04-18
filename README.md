# Atlas do Deep

Atlas interativo das descobertas de James Nestor em *Deep: Freediving, Renegade Science, and What the Ocean Tells Us About Ourselves* (Houghton Mifflin Harcourt, 2015).

Organizado em **14 seções** que cobrem desde as zonas oceânicas (Fótica, Mesopelágica, Batipelágica, Hadal) até os mistérios do corpo humano e os paralelos ancestrais com o oceano.

## Conteúdo

1. **Zona Fótica** — a casca iluminada e sua importância planetária
2. **Mesopelágica** — o crepúsculo, a cor azul, camuflagem vermelha
3. **Batipelágica** — bioluminescência, Idabel de Karl Stanley, ooze
4. **Hadal** — xenofióforos, snailfish, arquipélago de mundos isolados
5. **Corpo Humano** — Master Switch, Richet, Scholander, blood shift
6. **Cetáceos** — cachalotes, cliques fractais, Norris, melão, visão de raio-X
7. **Tubarões** — ampolas de Lorenzini, eletrorrecepção, Malpelo
8. **Magnetismo** — magnetita, Tupaia, Guugu Yimithirr, proteína CRY2
9. **Ecolocalização** — FlashSonar, Bushway, Kish, córtex visual em cegos
10. **Bioeletricidade** — raias elétricas, canais de íons, monges Tum-mo
11. **Amas** — tradição feminina de 2.500 anos, "só entre na água"
12. **Origem da Vida** — vents hidrotermais, Corliss, teoria ferro-enxofre
13. **Ancestralidade** — hipótese do macaco aquático, CRY2, ainda somos peixes
14. **Memorial** — Mevoli, Mestre, o custo do freediving competitivo

## Arquivos

- `atlas-do-deep.html` — o app completo (single file)
- `manifest.json` — manifesto PWA (instalação na tela inicial)
- `icon-192.png` — ícone 192×192 (Android e PWA)
- `icon-512.png` — ícone 512×512 (splash screen e PWA)
- `index.html` — redirect para atlas-do-deep.html (para facilitar deploy)

## Deploy no GitHub + Vercel

### 1. Criar repositório no GitHub

Suba os 5 arquivos para um repositório novo. Estrutura:

```
seu-repo/
├── atlas-do-deep.html
├── index.html
├── manifest.json
├── icon-192.png
└── icon-512.png
```

### 2. Conectar ao Vercel

- Acesse [vercel.com](https://vercel.com)
- Clique em **Add New → Project**
- Importe seu repositório GitHub
- Em *Framework Preset* escolha **Other** (é estático puro, sem build)
- Clique em **Deploy**

Em menos de um minuto você terá uma URL HTTPS tipo `seu-atlas.vercel.app`.

### 3. Instalar no celular

**Android/Chrome:** abra a URL, um banner "Instalar" vai aparecer automaticamente.

**iPhone/Safari:** abra a URL, toque no botão de compartilhar (caixinha com seta pra cima), depois em "Adicionar à Tela de Início". O ícone do freediver vai aparecer como app.

**Importante:** HTTPS é obrigatório para o PWA funcionar. Vercel já fornece por padrão.

## Offline

Depois de aberto uma vez com internet, o app fica cacheado pelo service worker e funciona 100% offline — leitura completa sem rede.

## Conteúdo

Todo o conteúdo é paráfrase direta do livro de James Nestor, com atribuição explícita. Este atlas é uma ferramenta pessoal de navegação — para a experiência completa, leia o original.
