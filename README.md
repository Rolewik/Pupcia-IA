# HAIDILIDI SZUKACZ 🐸

**Pupcia IA** to nazwa zakładki „O aplikacji”. Główna nazwa programu pozostaje **HAIDILIDI SZUKACZ**.

**Kalapupcia przejęty przez AI stworzył ten pojebany Szukaczajzer.**

Lekka, lokalna wyszukiwarka plików i aplikacji dla Windows 10/11. Bez chmury, telemetrii i wysyłania indeksu.

## Pobieranie

**[Pobierz najnowszą wersję HAIDILIDI SZUKACZ](https://github.com/Rolewik/Pupcia-IA/releases/latest)**

Pobierz `Pupcia-IA.exe` oraz opcjonalnie `Pupcia-IA.exe.sha256`. Program nie wymaga instalatora. Windows x64 wymaga zainstalowanego [Microsoft .NET Desktop Runtime 10](https://dotnet.microsoft.com/en-us/download/dotnet/10.0).

## Najważniejsze funkcje

- Wyszukiwanie lokalne, indeksowanie **wyłącznie po kliknięciu**, zapis indeksu SQLite.
- Ustawienia podzielone na czytelne, rozwijane sekcje: **Skaner**, **Skróty**, **Specjalne** i **Indeks**.
- Wszystkie skróty **wyłączone domyślnie**. Możliwość przypisania własnych kombinacji. **Ctrl+Shift+Space jest niedozwolony**.
- Opcjonalne przywoływanie przez **Win+S** tylko po włączeniu skrótów w ustawieniach.
- Tryb gamingowy OFF, AUTO albo 24/7 oraz edytor listy plików gier `.exe`.
- Wskazanie szacowanego czasu i tempa indeksowania, kiedy są dostępne dane do estymacji.
- Start z Windowsem poprzez launcher czekający na dostępność programu na wirtualnym dysku.
- Powiadomienia o nowych wydaniach na GitHubie, instalacja po weryfikacji SHA-256.

## Pierwsze uruchomienie i aktualizacje

Pierwsze uruchomienie tworzy brakujące pliki ustawień pod `%AppData%\PupciaFastSearch` i `%LocalAppData%\PupciaFastSearch`. Istniejące pliki nie są nadpisywane. **Indeks i ustawienia pozostają po aktualizacji EXE.** Funkcja aktualizacji korzysta wyłącznie z wydań GitHub Releases i porównuje ich sumy SHA-256.

## Bezpieczeństwo

Przed pierwszym uruchomieniem plik może wymagać zatwierdzenia przez SmartScreen, ponieważ nie jest podpisany komercyjnym certyfikatem. Sprawdzaj sumę SHA-256 pobranego EXE.

Ten repozytorium służy dystrybucji gotowych wydań aplikacji. Prywatne indeksy, konfiguracje i pliki użytkownika nie są publikowane.
