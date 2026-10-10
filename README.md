# Namnets bokstäver

En app som tolkar namn utifrån en teori om vad varje bokstav betyder. Skriv ett namn och få en sammanfattning, en analys i flera delar och en bokstav-för-bokstav-genomgång. Två namn kan också jämföras.

Under fliken Fler teorier tolkas samma namn även med pythagoreisk och chaldeisk numerologi, ljudsymbolik och nordiska runor, så att man kan jämföra.

Appen finns på svenska och engelska. Språket väljs uppe till höger och sparas i webbläsaren. Länken `?lang=en` öppnar appen direkt på engelska.

Allt körs i webbläsaren. Inget skickas någonstans och ingen inloggning behövs.

## Kör lokalt

Öppna `index.html` i en webbläsare.

## Publicera med GitHub Pages

1. Gå till **Settings → Pages** i repot.
2. Välj **Deploy from a branch**, branch `main` och mappen `/ (root)`.
3. Efter en stund ligger appen på `https://<användarnamn>.github.io/<repo>/`.

På mobilen kan sidan sedan läggas till på hemskärmen och öppnas som en app.

## Teorin

Bokstävernas betydelser ligger i `DEFAULT_THEORY` i `index.html`, och texterna som analysen bygger på i `BANK` och `ALT`. De engelska motsvarigheterna ligger i `THEORY_EN`, `EN_TEXT`, `EN_ALT` och `LANGS.en`.
