Manechic.us static export – Cursor-ready

Struktura:
- index.html          – główny plik strony
- assets/css/        – skompresowane style (Google Fonts, Showit CSS)
- assets/js/         – skrypty Showit (bez jQuery)
- assets/img/        – wszystkie obrazy z static.showit.co
- assets/fonts/      – lokalne fonty (w tym Questrial)
- assets/media/      – wideo/audio jeśli występują
- assets/files/      – pozostałe pliki statyczne
- vendor/jquery.min.js – jQuery z ajax.googleapis.com

W Cursorze:
1. Otwórz ten folder jako projekt.
2. Uruchom prosty serwer (np. `npx serve` albo rozszerzenie "Live Server").
3. Wejdź na `http://localhost:3000` / odpowiedni port – załaduje się index.html.