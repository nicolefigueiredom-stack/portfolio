# Portfólio — Nicole Figueiredo

Site portfólio profissional de Visual Merchandising & Brand Experience.
Single-page estático, pronto para publicar no **GitHub Pages**.

---

## 🚀 Como publicar no GitHub Pages (passo a passo)

1. Crie um repositório no GitHub chamado, por exemplo, `portfolio`.
2. Faça upload de **todos os arquivos** desta pasta (`index.html`, `README.md` e a pasta `images/`).
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch `main` e a pasta `/ (root)`. Salve.
5. Aguarde 1–2 minutos. Seu site estará no ar em:
   `https://SEU-USUARIO.github.io/portfolio/`

> Dica: para um domínio próprio (ex.: `nicolefigueiredo.com.br`), configure em Settings → Pages → Custom domain.

---

## 🖼️ Como adicionar suas imagens

O site já funciona sem imagens (mostra placeholders elegantes nos lugares certos).
Para colocar suas fotos reais, salve-as na pasta `images/` com **exatamente estes nomes**:

| Arquivo | Onde aparece |
|---|---|
| `images/nicole.jpg` | Foto principal (hero) — formato vertical 4:5 |
| `images/og-cover.jpg` | Imagem de compartilhamento (link no WhatsApp/LinkedIn) — 1200×630 |
| `images/westwing-01.jpg` … `westwing-03.jpg` | Cases Westwing |
| `images/nike-01.jpg` … `nike-03.jpg` | Cases Nike |
| `images/vivara-01.jpg` … `vivara-02.jpg` | Cases Vivara |
| `images/farm-01.jpg` … `farm-03.jpg` | Cases Farm Rio |

As imagens estão no seu portfólio Adobe Express. Para baixá-las: abra o portfólio,
clique com o botão direito em cada imagem → "Salvar imagem como" → renomeie conforme a tabela.

> Recomendado: otimize as imagens (formato `.jpg`, largura ~1200px) para o site carregar rápido.
> Ferramenta grátis: https://squoosh.app

---

## ✏️ Como editar textos

Tudo está no arquivo `index.html`. Procure pela seção que quer alterar
(estão comentadas: `<!-- SOBRE -->`, `<!-- PORTFÓLIO -->`, etc.) e edite o texto entre as tags.

Para trocar telefone, e-mail ou links, procure por:
- `5511950252503` (WhatsApp)
- `nicolefigueiredo.m@gmail.com` (e-mail)
- `nicolefigueiredomoreira` (LinkedIn)

---

## 🎨 Identidade visual

- **Paleta:** tons terrosos e neutros (terracota, oliva, espresso, areia, off-white).
- **Tipografia:** Fraunces (serifada editorial, passa credibilidade e senioridade) + Hanken Grotesk (corpo).
- **Aspecto:** editorial / luxo discreto, pensado para cargos de liderança.

As cores ficam no topo do `index.html`, em `:root{ ... }`. Para ajustar, mude os valores hexadecimais.

---

## 📁 Estrutura

```
portfolio/
├── index.html      ← o site inteiro (HTML + CSS + JS)
├── README.md       ← este arquivo
└── images/         ← suas fotos (ver tabela acima)
```

Feito com cuidado em São Paulo · 2026
