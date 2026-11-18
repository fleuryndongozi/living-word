# Living Word – instruktioner

## 1. Lägg upp sidan på GitHub (en gång)

1. Logga in på github.com och klicka **New repository**. Döp det till `living-word` och välj **Public**.
2. Klicka **uploading an existing file** och dra in *alla* filer och mappar från den här zip-filen (packa upp först). Klicka **Commit changes**.
3. Gå till **Settings → Pages**. Under *Source* välj **Deploy from a branch**, branch **main**, mapp **/ (root)**. Spara.
4. Efter en minut eller två finns sidan på `https://DITT-ANVÄNDARNAMN.github.io/living-word/`.

> Döper du repot till något annat än `living-word`, ändra `baseurl` i `_config.yml` till samma namn.

## 2. Lägg till en ny undervisning

1. Öppna mappen `_undervisningar` på GitHub och klicka **Add file → Create new file**.
2. Döp filen till t.ex. `2026-12-01-titel-pa-undervisningen.md` (inga mellanslag eller å/ä/ö i filnamnet).
3. Kopiera innehållet från `mall-undervisning.md` (ligger i huvudmappen), fyll i och skriv texten. Klicka **Commit changes**.
4. Sidan uppdateras automatiskt efter någon minut.

### Formatering
- `## Rubrik` ger en rubrik
- `**fet**` och `*kursiv*`
- `> text` ger en markerad ruta (t.ex. för bön eller bibelcitat)
- `1.` eller `-` för listor

## 3. Egen domän (valfritt)
Köp t.ex. `livingword.se`, lägg in den under **Settings → Pages → Custom domain**, och sätt `baseurl: ""` i `_config.yml`.
