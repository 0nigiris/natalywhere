<h1 align="center">natalywhere</h1>

<p align="center">
  A one-page <b>wayfinding card</b> — clear, human directions to a single real-world address,<br>
  so someone can get there without maps, apps or an account.
</p>

<p align="center">
  <sub>HTML · CSS · vanilla JS &nbsp;·&nbsp; one file &nbsp;·&nbsp; zero dependencies</sub>
</p>

---

I built this for my mum: not a map, just the parts that actually help — the address,
a step-by-step walk from the nearest landmark, a photo of what the entrance looks like,
and a way to message me if she gets lost. It opens instantly on a phone and needs nothing
installed.

### What's inside

- **Directions that read like a person wrote them** — landmarks and turns, not coordinates.
- **A photo of the entrance**, because the last 20 metres are where people get lost.
- **Theme-aware** — follows the system light/dark preference, with a manual toggle that
  is remembered across visits.
- **Mobile-first and self-contained** — a single `index.html`, no build step, no framework,
  no tracking. Works offline once loaded.

### Tech

Plain HTML, CSS custom properties for theming, and a few lines of vanilla JavaScript for the
theme toggle (persisted in `localStorage`). The page content is in Russian.

### Run it

```bash
# it's a single file — just open it
xdg-open index.html      # or double-click it
```

---

<p align="center"><sub>A small, personal utility. Kept deliberately tiny.</sub></p>
