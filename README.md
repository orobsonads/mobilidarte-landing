# Mobile D'arte By Italínea — Landing Page

Landing page de alta conversão para a loja **Mobile D'arte By Italínea**, desenvolvida pela **VIA Growth**.

Página única (`index.html`) em HTML/CSS/JS puro, sem dependências externas além das fontes Google. Otimizada para performance, mobile-first e conversão via WhatsApp.

---

## Como usar

1. Abrir `index.html` diretamente no browser (sem servidor necessário).
2. Para publicar: fazer upload do conteúdo desta pasta para qualquer hospedagem estática (Netlify, Vercel, GitHub Pages, Hostinger).

---

## Substituições pendentes antes de publicar

- [ ] **Fotos reais do cliente** — substituir as imagens placeholder da Unsplash na seção Hero e Galeria. Salvar em `images/` e atualizar os `src=` no HTML.
- [ ] **Place ID do Google Meu Negócio** — para exibir reviews reais do Google. Ver comentário detalhado na seção `#depoimentos` dentro do `index.html`.
- [ ] **Link real do Instagram** — atualizar o link "Acompanhe mais projetos no Instagram →" na seção Galeria.
- [ ] **Horário de funcionamento** — confirmar no footer (atualmente: Seg-Sex 9h-18h, Sáb 9h-14h).
- [ ] **Logo oficial** — substituir o logo textual em Playfair Display por arquivo PNG/SVG oficial do cliente, se houver.
- [ ] **OG Image** — criar `images/og-cover.jpg` (1200×630px) para preview de compartilhamento em redes sociais.

---

## Estrutura

```
mobilidarte-landing/
├── index.html          ← arquivo principal (único arquivo obrigatório)
├── images/             ← pasta para fotos reais do cliente
│   ├── hero.jpg
│   ├── projeto-01.jpg
│   └── ... (até 6 fotos)
├── .gitignore
└── README.md
```

---

## Contato do cliente

- **Endereço:** Av. José Giorgi, 1181 — Granja Viana, Cotia - SP
- **WhatsApp:** (11) 94631-3844

---

## Comandos Git (após criar repositório no GitHub)

```bash
git init
git add .
git commit -m "feat: landing page inicial Mobile D'arte By Italínea"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/mobilidarte-landing.git
git push -u origin main
```

> Substituir `SEU_USUARIO` pelo usuário real do GitHub. Os comandos não são executados automaticamente — rodar manualmente após criar o repositório.
