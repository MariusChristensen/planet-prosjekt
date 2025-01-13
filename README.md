# One-Page Planet Website Project

Dere skal samarbeide i grupper på 2 om å lage en one-page nettside med en av planetene i solsystemet som tema.

Nettsiden skal ha en ganske enkel struktur: Header med en navbar som scroller til de forskjellige seksjonene. Minimum 2 seksjoner. Forslag til seksjoner: Bildegalleri, Infoside, Faktaliste etc. Se layout mal nederst.

Fokus skal være på design og layout, valg av fargetema, valg av bilder, valg av fonter.

## TIPS

### HTML
```html
<section id="mysection"></section> <!-- Container element for section -->
<a href="#mysection"></a> <!-- Link til navbar knappene som scroller til section -->
```

### CSS
```css
html {
  scroll-behavior: smooth;
}
/* Med denne får du en smooth scroll når du navigerer til section */
```

### Planlegging

Dere skal planlegge design og layout i Figma. (En lager Figma-prosjektet og inviterer den andre til å være editor i prosjektet). Figma-skissen kan enten være kun wireframe og konsept, eller full skisse (Men husk å sette av god tid til å kode ut siden!)

### Koding

Siden skal kodes med HTML og CSS. Det legges vekt på god bruk av semantisk og ryddig HTML og bruk av flex-box til layout i CSS (I CSS skal du være varsom med bruk av position absolute og absolutte verdier. Spør om du er usikker på hva som menes med dette.)

Siden trenger ikke å være responsiv (dvs den trenger ikke å optimaliseres for mobil).

### Samarbeid

Dere skal samarbeide om koding med å bruke 1 GitHub repository som begge pusher og puller kode til/fra. (En lager repository og gir den andre tilgang. Dette kan vi hjelpe med.)

Husk å kommentere i koden.

### Hosting

Siden skal hostes på GitHub Pages (gratis hosting-tjeneste, her er en [quickstart guide](https://docs.github.com/en/pages/quickstart)).

## Ressurser
- [Unsplash](https://unsplash.com/) og [Pexels](https://www.pexels.com/) er gode ressurser for lisensfrie bilder.
- [NASA Solar System Overview](https://solarsystem.nasa.gov/planets/overview/) er en bra ressurs for bilder/informasjon.

## Layout Mal

Bruk denne malen som utgangspunkt for layout og struktur. La dere gjerne inspirere av fargevalg og fonter, men unngå å lage en blåkopi, gjør den til deres egen.

![Planeteksempel](assets/img/planeteksempel.png)
