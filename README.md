# Kniha poptávek

Evidence svatebních poptávek. Běží na GitHub Pages, data ukládá do databáze Supabase.

## Soubory

- `index.html` – celá appka
- `config.js` – adresa a klíč databáze (doplníš ze Supabase)
- `schema.sql` – vytvoří tabulku v Supabase (spouští se jednou)

## Nastavení

1. **Supabase:** založ projekt na supabase.com. V SQL Editoru spusť obsah `schema.sql`.
2. **Uživatel:** Authentication → Users → Add user → Create new user. Zadej svůj e-mail a heslo, zaškrtni Auto Confirm User.
3. **Zákaz registrací:** v nastavení přihlašování vypni „Allow new users to sign up“, ať si nikdo jiný nezaloží účet.
4. **Klíče:** z Project Settings → API zkopíruj Project URL a publishable (anon) key do `config.js`.
5. **GitHub:** nový veřejný repozitář, Add file → Upload files, nahraj `index.html`, `config.js` a `README.md`.
6. **Zveřejnění:** Settings → Pages → Deploy from a branch → `main` / root → Save. Appka poběží na `https://UZIVATEL.github.io/NAZEV-REPOZITARE/`.

## Úpravy

Kurz eura, rozpočtová pásma a kategorie „Odkud se o mně dozvěděli“ jsou nahoře ve skriptu v `index.html` (blok NASTAVENÍ).
Po nahrání upraveného souboru na GitHub se změna projeví do pár minut.
