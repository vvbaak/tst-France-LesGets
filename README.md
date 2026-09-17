# Voorhoofdspel

Een lokale heads-up stijl game in één `index.html` bestand.

## Lokaal testen

Open direct:

- `file:///home/runner/work/tst-France-LesGets/tst-France-LesGets/index.html`

Of start een simpele server:

```bash
cd /home/runner/work/tst-France-LesGets/tst-France-LesGets
python -m http.server 8000
```

Open daarna:

- `http://localhost:8000/index.html`

## Publiceren op GitHub Pages

1. Push deze repository naar GitHub.
2. Ga naar **Settings** → **Pages**.
3. Kies **Deploy from a branch**.
4. Selecteer branch **main** en folder **/** (root).
5. Sla op.

De site wordt dan bereikbaar op:

- `https://vvbaak.github.io/tst-France-LesGets/`

## Bestanden

- `index.html` — complete app met HTML, CSS en JavaScript
- `.nojekyll` — zorgt dat GitHub Pages de site als pure statische site serveert
