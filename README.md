# JJTECH Academy & RCCG Triumphant Assembly Parish

A shared website for two institutions on one compound in Benin City, Edo State:

- **JJTECH Academy** — Nursery, Primary and Secondary school (`school.html`)
- **RCCG Triumphant Assembly Parish** — church/parish site with service times and ministries (`church.html`)
- `index.html` — shared homepage ("the Threshold") linking to both

## Structure

```
index.html      Homepage — shared gate into the Academy and the Parish
school.html     JJTECH Academy — programs, admissions, contact form
church.html     RCCG Triumphant Assembly Parish — services, ministries, contact form
styles.css      Shared design system (single stylesheet, CSS variables)
script.js       Mobile nav toggle, footer year, scroll reveal animation
```

Plain HTML/CSS/JS — no build step required.

## Editing content

- Contact details (phone, email, address) are placeholders — search each HTML file for `+234 800` and the `@jjtechacademy.org` / `@triumphantassembly.org` addresses and replace with the real ones.
- The contact forms use `action="#"` — connect them to a service like [Formspree](https://formspree.io) or your own backend to receive submissions.
- The map placeholder in `church.html` can be swapped for a real Google Maps `<iframe>` embed once you have the parish's map pin.
- The "pastor photo" and quote blocks are text placeholders — swap in real photos/quotes when ready.

## Running locally

Just open `index.html` in a browser, or serve the folder with any static server:

```
python3 -m http.server 8000
```

## Deploying

This repo is set up to publish via **GitHub Pages** from the `main` branch, `/ (root)` folder.
