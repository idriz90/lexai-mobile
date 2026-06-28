# LexAI Mobile

Versione statica per GitHub Pages.

## Uso

1. Apri la pagina pubblicata da GitHub Pages.
2. Premi `Chiave Gemini` o invia una prima domanda.
3. Inserisci la tua chiave Gemini API.
4. La chiave viene salvata nel browser del dispositivo.

## Sicurezza

Questo repository non deve contenere chiavi API.

Non inserire la chiave Gemini dentro `index.html` prima di caricarlo su GitHub.

## Pubblicazione su GitHub Pages

1. Crea una nuova repository su GitHub.
2. Carica in repository solo questi file:
   - `index.html`
   - `README.md`
3. Vai in `Settings`.
4. Apri `Pages`.
5. In `Build and deployment`, scegli:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Salva.
7. Dopo qualche minuto GitHub mostra il link pubblico della pagina.

## Chiave Gemini

La chiave si crea da Google AI Studio:

https://aistudio.google.com/

Documentazione:

https://ai.google.dev/gemini-api/docs/api-key
