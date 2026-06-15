# Co je Cloudflare? 🌐

Informační webová stránka vytvořená jako školní projekt. Stránka přehledně popisuje, co je Cloudflare, k čemu slouží a jaké služby nabízí.

## 🔗 Živá ukázka

> Po nasazení na GitHub Pages bude stránka dostupná na:  
> `https://TVOJE_JMENO.github.io/cloudflare-page/`

---

## 📁 Struktura projektu

```
/
├── index.html       # Hlavní stránka
├── style.css        # Vlastní CSS styly
├── og-image.png     # Obrázek pro sociální sítě (Open Graph)
└── README.md        # Tento soubor
```

---

## 📄 Obsah stránky

1. **Co je Cloudflare?** — stručné vysvětlení technologie (3 odstavce + statistiky)
2. **K čemu Cloudflare slouží?** — vysvětlení vlastními slovy
3. **Vybrané služby** — přehled 6 klíčových produktů:
   - DDoS Protection
   - CDN (Content Delivery Network)
   - DNS Resolver 1.1.1.1
   - Web Application Firewall (WAF)
   - Cloudflare Workers
   - Cloudflare Pages

---

## 🛠️ Technické specifikace

| Oblast | Řešení |
|---|---|
| Struktura | Čisté HTML5 (sémantické elementy) |
| Styly | Vlastní CSS3 — Flexbox + Grid, bez frameworků |
| JavaScript | ❌ Žádný — stránka funguje čistě bez JS |
| Fonty | Inter (Google Fonts) |
| Přístup | Mobile First |

### Zakázané technologie (dle zadání)
- ❌ JS frameworky (React, Vue, Angular)
- ❌ CSS frameworky (Bootstrap, Tailwind)

---

## ✅ Implementované oblasti

### ⚡ Výkon (Performance)
- Minimální počet HTTP požadavků (1× CSS, 1× font)
- `preconnect` pro Google Fonts
- Inline SVG ikony — žádné externí ikony
- CSS animace přes `@keyframes` (žádný JS overhead)

### 🔍 SEO
- Sémantické HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- Meta tagy: `description`, `keywords`, `author`, `robots`, `canonical`
- Správná hierarchie nadpisů (h1 → h2 → h3)

### ♿ Přístupnost (WCAG AA)
- Skip link „Přeskočit na hlavní obsah"
- ARIA atributy (`aria-label`, `aria-hidden`, `role`)
- Viditelný `:focus-visible` styl pro ovládání klávesnicí
- Kontrast textu: **14:1** (požadavek WCAG AA: min. 4,5:1)
- `prefers-reduced-motion` — vypne animace pro citlivé uživatele
- `prefers-contrast: high` — zesílí okraje při vysokém kontrastu

### 📱 Sociální sítě
- **Open Graph** — `og:title`, `og:description`, `og:image`, `og:url`, `og:locale`
- **Twitter/X Cards** — `twitter:card`, `twitter:title`, `twitter:image`
- AI generovaný OG obrázek (1200 × 630 px)

### 🎨 UI/UX
- **Mobile First** design — base styly pro mobil, breakpointy pro tablet (768px) a desktop (1024px)
- Tmavý moderní design s oranžovými akcenty (barvy Cloudflare)
- Hover efekty na kartách, CSS animace sekcí
- Responzivní grid layout (1 → 2 → 3 sloupce)

### 🤖 AI Integrace
- OG obrázek vygenerován pomocí generativní AI
- Obsah konzultován a upraven s pomocí AI nástrojů


