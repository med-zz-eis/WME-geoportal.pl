# geoportal.gov.pl layers for WME (API March 2026)

Skrypt wyświetla warstwy z Geoportalu w edytorze Waze. Wyświetlane warstwy to: ortofotomapa ("podkład satelitarny"), numery domów i nazwy miejscowości. Skrypt został zaktualizowany w marcu 2026 r., aby w pełni wspierać nowy interfejs WME ("Draggable Cards").

Skrypt jest zbudowany na podstawie skryptu [geoportal.gov.pl layers for WME without translating PROXY](https://greasyfork.org/en/scripts/10611-geoportal-gov-pl-layers-for-wme-without-translating-proxy) autorstwa [Pawła Pyrczaka](https://greasyfork.org/en/users/9996-pawe%C5%82-pyrczak) oraz poprawek Stracha https://github.com/strah/WME-geoportal.pl oraz Kamila Maruda https://github.com/kmarud/WME-geoportal.pl

**Instalacja:** https://greasyfork.org/en/scripts/572377-geoportal-waze-integration-fork-by-snpl  

Pliki źródłowe są dostępne na [Githubie](https://github.com/med-zz-eis/WME-geoportal.pl), zapraszam do forkowania/aktualizacji.
---

The script displays Geoportal overlays in the WME ("satellite view", house numbers, cities names). Updated in March 2026 for full compatibility with the new "Draggable Cards" WME interface.

This script is based on [geoportal.gov.pl layers for WME without translating PROXY](https://greasyfork.org/en/scripts/10611-geoportal-gov-pl-layers-for-wme-without-translating-proxy) script by [Paweł Pyrczak](https://greasyfork.org/en/users/9996-pawe%C5%82-pyrczak) and Strah's adjustments https://github.com/strah/WME-geoportal.pl and Kamil Marud https://github.com/kmarud/WME-geoportal.pl

**Installation:** https://greasyfork.org/en/scripts/572377-geoportal-waze-integration-fork-by-snpl

The source file is hosted on [Github](https://github.com/med-zz-eis/WME-geoportal.pl), feel free to fork/update.

---

## Jak używać / How to use

1. **Instalacja / Installation**: Zainstaluj skrypt za pomocą menedżera skryptów (np. Tampermonkey).
2. **Uruchomienie / Startup**: Otwórz Waze Map Editor.
3. **Warstwy / Layers**: W bocznym panelu "Warstwy" (pojawiającym się jako nowa karta) znajdziesz sekcję **"-- Geoportal PL --"**.
4. **Włączanie / Toggling**: Kliknij checkbox lub po prostu przesuń suwak przezroczystości w prawo. Zmiana suwaka automatycznie aktywuje warstwę.
5. **Przezroczystość / Opacity**: Ustawienie suwaka na 0% automatycznie wyłącza warstwę.
6. **Kategorie / Categories**: Warstwy są pogrupowane w zwijane kategorie (Ortofoto, Adresy, Podział Adm, BDOT).

## Changelog [1.5.0] - 2026-04-03
*   **Wsparcie API Marzec 2026 / March 2026 API Support**: Pełna kompatybilność z nowym systemem kart ("Draggable Cards").
*   **MutationObserver**: Stabilna obecność menu mimo przerywania renderowania przez WME.
*   **Nowy interfejs UI / New UI layout**: Suwaki pod nazwami warstw, obsługa Dark Mode.
*   **Wydajność / Performance**: Lazy loading (ładowanie tylko włączonych warstw) oraz filtracja poziomów przybliżenia (zoom).
*   **Pamięć ustawień / Settings Persistence**: Automatyczne zapisywanie włączonych warstw i przezroczystości.
