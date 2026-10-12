# Familiearchief — GitHub Pages

Deze map bevat een complete zelfstandige website. De startpagina heet **index.html** en werkt zonder extra pakketten of serverconfiguratie. Op een telefoonscherm opent automatisch een rustige, tweedelige voorouderverkenner voor Gert en Jolanda. Tik op een tegel voor de ouders, en daarna door naar oudere generaties. Via de knop **Volledige site** rechtsboven open je de volledige bestaande familieatlas; de groene knop onderaan brengt je terug naar de eenvoudige weergave. Op een groot scherm blijft de oorspronkelijke site zichtbaar.

## Op GitHub zetten

1. **Pak de ZIP eerst uit op je computer.** GitHub Pages kan niet rechtstreeks een ZIP als website publiceren.
2. Maak op GitHub een repository (bijvoorbeeld `familiearchief`) en ga naar **Add file → Upload files**.
3. Upload **index.html**, **robots.txt** en **.nojekyll** vanuit deze map, dus **niet de ZIP zelf**. Commit de bestanden op de branch `main`.
4. Open **Settings → Pages**. Kies onder **Build and deployment**: **Deploy from a branch**, branch **main**, folder **/(root)**, en sla op.
5. Wacht tot GitHub Pages de link toont: `https://<gebruikersnaam>.github.io/<repositorynaam>/`. Open die link op je telefoon.

**Snelste optie:** upload alleen `index.html` in de root van de repository en zet Pages aan. De andere twee bestanden zijn optioneel.

## Belangrijke privacywaarschuwing

Dit is een familiearchief met informatie over **levende personen**. Een GitHub Pages-website is doorgaans **publiek toegankelijk voor wie de URL heeft**, ook als je `noindex` gebruikt. Het meegeleverde `robots.txt` en de `noindex`-tag ontmoedigen indexering, maar **beveiligen de gegevens niet**. Publiceer de volledige dataset alleen als alle betrokkenen dat goedvinden. Voor uitsluitend privaat testen kun je `index.html` lokaal op je telefoon openen of een afgeschermde hostingdienst gebruiken.

## Technisch

- Eén HTML-bestand met ingebedde genealogische data; de normale waaier, kaart en persoonspaspoorten blijven aanwezig.
- Mobiele modus: onder 768 CSS-pixels. De gebruiker kan overschakelen naar de volledige website.
- Geen externe bibliotheken of tracking nodig.
