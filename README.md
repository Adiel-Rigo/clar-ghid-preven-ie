# CLAR — Ghid de prevenție a dependențelor

Website static, în limba română, construit cu HTML, CSS și JavaScript. Nu necesită instalarea unui framework sau a unui server propriu.

## Ce include
- 25 de fișe educaționale despre substanțe psihoactive.
- Căutare și filtre interactive.
- Ferestre cu detalii despre origine, efecte raportate, riscuri și semne de urgență.
- Imagini documentare încărcate din Wikimedia Commons, cu link spre pagina sursei/licenței. Necesită conexiune la internet.
- Secțiuni despre alcool, tutun și nicotină, mituri, prevenție și resurse de sprijin.
- Design adaptiv pentru telefon, tabletă și calculator.

## Deschidere în Visual Studio Code
1. Descarcă și dezarhivează proiectul.
2. Deschide Visual Studio Code.
3. Alege **File → Open Folder** și selectează folderul `ghid_preventie_dependente`.
4. Deschide `index.html`. Pentru previzualizare recomand extensia **Live Server**: Extensions → caută „Live Server” → Install → click dreapta pe `index.html` → **Open with Live Server**.

## Publicare gratuită cu GitHub Pages
1. Creează un cont pe GitHub: https://github.com/
2. Apasă **New repository**. Numește-l `clar-ghid-preventie`, selectează **Public**, apoi **Create repository**.
3. În pagina repository-ului apasă **Add file → Upload files**.
4. Încarcă fișierele `index.html`, `style.css`, `app.js` și `README.md` (nu încărca folderul ZIP).
5. Apasă **Commit changes**.
6. Intră la **Settings → Pages**.
7. La **Build and deployment**, alege **Deploy from a branch**; Branch: **main**, folder: **/(root)**; apasă **Save**.
8. Așteaptă câteva minute. GitHub va afișa adresa publică, de forma `https://NUMELE-TAU.github.io/clar-ghid-preventie/`. Oricine are linkul o poate deschide.

## Cum ajunge pe Google
Publicarea pe GitHub Pages face site-ul accesibil pe internet, dar nu garantează apariția imediată în rezultatele Google.
1. Deschide Google Search Console: https://search.google.com/search-console/
2. Alege **URL prefix** și introdu adresa GitHub Pages completă.
3. Verifică proprietatea urmând metoda oferită de Google (pentru GitHub Pages, metoda HTML file sau meta tag poate necesita pași suplimentari; folosește metoda pe care Search Console o confirmă pentru proprietatea ta).
4. După verificare, folosește **URL Inspection** și apasă **Request indexing** pentru pagina principală.
5. Așteaptă recrawl-ul. Indexarea poate dura zile sau săptămâni și nu este garantată.

## Actualizare
Modifică fișierele în VS Code, apoi încarcă fișierele modificate în repository și apasă Commit changes. GitHub Pages publică automat actualizarea.

## Notă editorială și medicală
Conținutul este educațional, nu diagnostic sau tratament. Descrierile efectelor sunt generale și pot varia mult. Nu include rețete, instrucțiuni de preparare sau recomandări de consum. Nu am inventat mărturii atribuite unor persoane reale: secțiunile despre efecte sintetizează reacții raportate în general. Pentru publicare într-un proiect școlar/instituțional, verifică și completează conținutul cu un medic specialist și citează sursele primare. Pentru urgențe în România/UE: 112.

Imaginile sunt căutate automat prin API-ul public Wikimedia Commons. Verifică licența fiecărei imagini înainte de reutilizarea ei în materiale promoționale sau comerciale; linkul imaginii duce la pagina sursei.
