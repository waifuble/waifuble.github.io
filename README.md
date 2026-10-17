# Miki Dalit — Personal Website

Static portfolio site. Plain HTML/CSS/JS only — no build step, no frameworks.
Push the contents of this folder straight to a GitHub repo and enable
GitHub Pages (Settings → Pages → Deploy from branch) to go live.

## Structure

- `index.html` — hero, About, project cards, resume download, contact footer
- `style.css` — shared stylesheet (warm minimal theme, responsive)
- `resume.pdf` — resume download (copied from `~/workspace/user/files/MariaDalitResume2026.pdf`)
- `projects/governed-fuel-cell.html` — Governed Fuel Cell Project
- `projects/mooni-gadget.html` — Muse AI Gadget Assistant (Mooni)
- `projects/fieldbus-thermal.html` — Fieldbus Thermal Simulation w/ SPE Uplink
- `projects/mini-battery-cell.html` — Mini Battery Cell Production (on hold)

## Notes

- Equations render with KaTeX loaded from the jsDelivr CDN — needs internet
  access at view time, no build step required.
- Photo slots are dashed placeholder blocks; swap in real build photos later.
- Content mirrors the Notion "Miki Dalit Portfolio" pages (Oct 2026), wording
  kept as-is. If the About copy or project status changes, update the HTML
  directly — it's all hand-editable.
