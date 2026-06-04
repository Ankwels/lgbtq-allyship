# LGBTQIA+ Allyship — Regent's University London LGBTQIA+ Ally Staff Network

A static website for Pride 2026, built for the QueeRs LGBTQIA+ Ally Network at Regent's University London.

No build step. No dependencies. Plain HTML files and one image, hosted on Vercel.

---

## What's here

| File | What it is |
|------|------------|
| `index.html` | The allyship quiz. This is the landing page. |
| `resources.html` | The curated resources page. Linked from the end of the quiz. |
| `recap.html` | The printable summary of a person's quiz responses. Linked from the result screen. |
| `rose_swirl_lilac_soft_peach_rotated__1_.png` | The Regent's rose image used in the resources header. Must stay in the same folder as the HTML files. |

---

## Deploying

The site is hosted on [Vercel](https://vercel.com), connected to this GitHub repository. Any commit to the main branch redeploys automatically, usually within a minute.

To update the site: edit a file on GitHub, commit, done.

---

## Editing content

Everything is plain HTML. No framework, no build process.

**To change a quiz question or reflection**, open `index.html`, find the `QUESTIONS` array near the top of the `<script>` block, and edit the text inside the quote marks. Each question has a `scene` (the scenario), `options` (the four choices), and `reflect` (the reflection shown after answering). Some also have a `link` with a label and URL.

**To change a resource link**, open `resources.html` and find the relevant `<section>`. Links follow this pattern:

```html
<li><a href="URL" target="_blank" rel="noopener">
  Link title
  <span class="res-note">Short description</span>
</a></li>
```

**To change the action items** at the end of the quiz, find the `ACTIONS` object in `index.html`. Each tier (`minute`, `week`, `ready`) has a `label` and an `items` array.

---

## Brand

### Colours

| Name | Hex |
|------|-----|
| Forest green | `#195c4d` |
| Off-white | `#f7f1e8` |
| Violet | `#d8cbf1` |
| Charcoal | `#171f20` |
| Gold | `#C3A35B` |
| Salmon | `#FFA188` |
| Lime | `#DAF092` |
| Sky | `#A4DEEB` |
| Pink | `#FF81B0` |

Source: Regent's University London 2024 colour swatch (ASE file held separately).

### Fonts

The site declares **TS Magnole** for headings and **Avenir Next** for body copy. Both are commercial fonts licensed to Regent's University London and are not embedded in the site files. They will render correctly on devices where they are installed. On other devices, the fallbacks are Cormorant Garamond (headings) and DM Sans / system-ui (body), which are close enough for public-facing use.

If you want to embed the fonts for consistent rendering across all devices, contact the Regent's marketing team for the licensed web font files and add them via `@font-face` declarations.

---

## Contact

QueeRs, the LGBTQIA+ Ally Network at Regent's University London.  
[Join the Teams channel](https://teams.microsoft.com/l/channel/19%3AHTmCXLXnL0jKT5NSWmIL6SV9tS-Sjm4idJB7HJAzQGE1%40thread.tacv2/General?groupId=ba281ee6-5327-4fb5-9170-caf7414308a2&tenantId=b40c8424-283d-4a7a-a31b-80b82fee1303)
