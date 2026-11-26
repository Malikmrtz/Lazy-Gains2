# Lazy Gains

En telefonvenlig madplan, indkøbsliste, snackguide og vægtlog. Intet build-trin. Den kan installeres som en app og virker offline efter det første besøg.

## Filer

`index.html` (appen), `logo.svg` (logo og appikon), `manifest.webmanifest` og `sw.js` (installation og offline).

## Læg den på GitHub Pages (gratis)

1. Opret et nyt **offentligt** repository med navnet `lazy-gains`.
2. **Add file > Upload files**, træk alle fem filer ind, og tryk **Commit changes**.
3. **Settings > Pages**: Source **Deploy from a branch**, branch `main`, mappe `/ (root)`, og tryk **Save**.
4. Efter et minut er appen live på `https://DIT-BRUGERNAVN.github.io/lazy-gains/`.

## Føj den til hjemmeskærmen

- **iPhone (Safari):** Del, derefter **Føj til hjemmeskærm**.
- **Android (Chrome):** Menu, derefter **Installer app**.

## Godt at vide

- Afkrydsede måltider, kurv, budget og vejninger gemmes i din browser. Sletter du webstedets data, forsvinder de.
- Priser, måltider og portioner ligger i listerne `SHOP`, `MEALS`, `SNACKS` og `WEEK` øverst i scriptet i `index.html`.
- Efter ændringer: skift navnet `lazy-gains-v1` i `sw.js`, så telefoner henter opdateringen.
