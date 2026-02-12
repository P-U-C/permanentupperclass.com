# permanentupperclass.com

Assets. Capital. Relationships.

The coordination layer for people who build things that compound.

## Structure

```
├── index.html          — Landing page (Directives 01 + 02)
├── manifesto.md        — Full founding document (all six sections, including Precedents)
├── brand-identity.md   — Brand identity system (voice, visuals, positioning)
├── CNAME               — Custom domain config for GitHub Pages
└── README.md           — This file
```

## Deployment

This site is designed to be deployed via [GitHub Pages](https://pages.github.com/).

1. Push to `p-u-c/permanentupperclass.com`
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch** → `main` / `/ (root)`
4. Custom domain: `permanentupperclass.com`
5. Enforce HTTPS: ✅

### DNS

Add these records to your domain registrar:

| Type  | Name | Value                        |
|-------|------|------------------------------|
| A     | @    | 185.199.108.153              |
| A     | @    | 185.199.109.153              |
| A     | @    | 185.199.110.153              |
| A     | @    | 185.199.111.153              |
| CNAME | www  | p-u-c.github.io              |

## Documents

- **Directive 01** — The founding statement (on landing page)
- **Directive 02** — The manifesto (on landing page, trimmed; full version at `/manifesto.md`)
- **Brand Identity** — Voice, visual direction, content framework, naming conventions

## License

Private. Not for distribution or derivative works without authorization.

---

EST 2026
