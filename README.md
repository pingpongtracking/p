# PingPongTracking — GitHub Pages

Statyczna, responsywna strona promocyjna aplikacji PingPongTracking. Nie wymaga instalowania bibliotek, kompilacji ani serwera.

## Publikacja

1. Umieść pliki `index.html`, `style.css`, `script.js`, `support.html`, `privacy.html` oraz folder `assets/` w katalogu głównym repozytorium `pingpongtracking.github.io` organizacji `pingpongtracking`.
2. W GitHub przejdź do **Settings → Pages**.
3. W **Build and deployment** wybierz **Deploy from a branch**, gałąź `main`, folder `/(root)`.
4. Adres: `https://pingpongtracking.github.io/` (jeśli właścicielem repozytorium jest organizacja `pingpongtracking`).

## Zrzuty ekranu

Dodaj pionowe obrazy PNG pod nazwami:

- `assets/screenshots/01.png`
- `assets/screenshots/02.png`
- `assets/screenshots/03.png`
- `assets/screenshots/04.png`

Strona wykrywa je automatycznie. Dopóki ich nie ma, widoczne są estetyczne pola zastępcze. Aby dodać więcej, skopiuj element `.screenshot-slide` w `index.html`, zmień adres obrazka, a także dodaj odpowiednie tłumaczenia placeholderów w `script.js` (lub zrezygnuj z podpisów, gdy obrazy są gotowe).

## Personalizacja

- Teksty polskie i angielskie: obiekt `translations` w `script.js`.
- Kolory, układ i wygląd: `style.css`, w szczególności sekcja `:root`.
- Link App Store: po premierze możesz zastąpić etykietę „Wkrótce” prawdziwym linkiem.
- Obecny mockup wyników 11:09 i ilustracja stołu są **wyłącznie ozdobną grafiką strony** — nie pokazują prawdziwego interfejsu aplikacji.
- Podstrony `support.html` i `privacy.html` zawierają **tylko miejsca do uzupełnienia** — przed udostępnieniem App Store koniecznie dodaj prawdziwe treści i dane kontaktowe.

## Testy

Przetestuj na telefonie i komputerze, przełącznik PL/EN, karuzelę i wszystkie odnośniki. Github Pages obsługuje ten projekt jako zwykłą statyczną stronę.
