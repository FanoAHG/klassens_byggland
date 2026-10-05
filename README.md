# 🏘️ Klassens Byggland

Interaktivt kart der elevene bygger sin egen eiendom, setter pris og rente, og selger egne produkter med bilder – et opplegg i matematikk/økonomi for 10. trinn.

## 🚀 Kom i gang

### 1. Last opp filene til repoet
Last opp `index.html`, `supabase-setup.sql` og denne filen (`README.md`) i repoet på GitHub: **Add file → Upload files**.

Lag også en tom fil som heter `.nojekyll` (med punktum først): **Add file → Create new file** → skriv `.nojekyll` → Commit.

### 2. Koble til Supabase (gratis)
1. Opprett konto på [supabase.com](https://supabase.com) og lag et nytt prosjekt (velg gjerne EU-region).
2. **SQL Editor → New query** → lim inn innholdet fra `supabase-setup.sql` → **Run**.
3. **Settings → API** → kopier **Project URL** og **anon public-nøkkelen**.

### 3. Koble appen til Supabase
Rediger `index.html` i GitHub (klikk på blyant-ikonet), finn disse to linjene:

```js
const SUPABASE_URL = "https://DITT-PROSJEKT.supabase.co";
const SUPABASE_KEY = "din-anon-nøkkel";
```

Lim inn din URL og anon-nøkkel, og commit. (Anon-nøkkelen er offentlig og ment for dette – SQL-filen skrur på radnivåsikkerhet.)

### 4. Publiser med GitHub Pages
1. Repoet → **Settings → Pages**
2. **Source:** Deploy from a branch → **main** / **(root)** → **Save**
3. Etter et par minutter: **https://fanoahg.github.io/klassens_byggland/**

### 5. Del lenken med elevene 🎉 og test selv først

## 📚 Forslag til undervisningsopplegg
- **Uke 1 – Lån:** Elevene velger byggetype, pris og rente. Klikk på et bygg for månedskostnad og total kostnad over 25 år (annuitet). Hvor mye er renter?
- **Uke 2 – Sammenligne:** Hvilket bygg på kartet har lavest månedskostnad – og hvorfor?
- **Uke 3 – Butikk:** Elevene setter priser på egne produkter. Hva skjer med inntekten om prisen økes med 10 %? 25 %?
- **Uke 4 – Refleksjon:** Knytt til kompetansemål: prosent, vekstfaktor, eksponentiell vekst.

## ⚠️ Personvern
Appen lagrer elevenes navn og bilder i Supabase-prosjektet ditt. Bruk bare fornavn, informer foresatte, og slett testdata regelmessig.
