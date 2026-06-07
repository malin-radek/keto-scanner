# 🥑 Keto Scanner

Aplikacja mobilna do skanowania i oceny produktów spożywczych pod kątem wybranej diety.
Skanujesz etykietę → aplikacja sprawdza skład → dostajesz ocenę ✅ / ⚠️ / ❌

## 📱 Funkcje

- 📷 Skanowanie etykiet przez kamerę (ML Kit on-device lub AI Vision)
- 🍽️ Obsługa wielu diet: 🥑 Keto, 🥬 Wegańska, 🌾 Bezglutenowa, 🫙 Low FODMAP i inne
- 🔍 Wyszukiwanie produktów w OpenFoodFacts, Spoonacular, Nutritionix
- 👤 Własne profile dietetyczne z konfigurowalnymi regułami
- 📊 Historia skanów i dziennik posiłków
- 🏷️ Przeglądarka lokalnych etykiet i znanych produktów

## 📦 Pobierz

**[⬇️ Pobierz najnowszy APK — v1.0.154](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.154)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.157 (2026-06-08)

- 📊 Firebase Analytics — automatyczne zbieranie statystyk: ile osób korzysta z aplikacji, które ekrany odwiedzają i jakie akcje wykonują (skanowanie kodu, OCR, ręczne wyszukiwanie, zapis posiłku, pomiar wagi, Keto-Szef AI, skan lodówki)
- 1.0.156
- 2026-06-07
- 📊 Nowy ekran statystyk — kliknij w panel wagi, wartości odżywczych lub podsumowania dnia w przeglądzie dnia, aby zobaczyć szczegółowe wykresy
- ⚖️ Wykres wagi — liniowy wykres pomiarów wagi z zaznaczonym min/max
- 🥗 Wykres makroskładników — dzienne ilości tłuszczu, białka i węgli na jednym wykresie
- 🔥 Wykres spożycia kalorii — dzienne kalorie z linią referencyjną TDEE
- 🧬 Wykres składu ciała — BMI, tkanka tłuszczowa, LBM, mięśnie, woda, kości, tłuszcz trzewny, BMR, wiek metaboliczny, białko
- 📅 Zakres dat z szybkimi presetami (7/14/30/90 dni) i ręczną edycją dat od–do
- 📉 Wszystkie wykresy mają przerywane linie min/max oraz legendę

### v1.0.155 (2026-06-07)

- 📅 Panel skanu lodówki w przeglądzie dnia — podsumowanie zawartości lodówki widoczne w dzienniku obok posiłków i pomiarów wagi
- 🔵 Dzień ma dane nawet bez posiłków — kalendarz pokazuje kropkę gdy zrobiłeś pomiar wagi lub skan lodówki, a przegląd dnia wyświetla wszystkie zebrane informacje

### v1.0.154 (2026-06-07)

- 📊 Przebudowa wykresów w dzienniku posiłków — trzy kompaktowe paski postępu dla tłuszczu, białka i węgli pokazują dokładnie ile gramów zjadłeś względem dziennego celu
- 📉 Paski makro zmieniają kolor — zielony = w zakresie celu, pomarańczowy = poniżej, czerwony = powyżej; linie na paskach wskazują dolną i górną granicę celu
- 🔥 Pasek kalorii zintegrowany z oceną poziomu — badge "Dobre chudnięcie" / "Niedojadanie" wyświetla się bezpośrednio przy pasku, oszczędzając miejsce
- 📐 Wszystkie wykresy w jednej zwartej karcie — zamiast rozbijać na osobne sekcje, makro i kalorie są obok siebie, czytelne na pierwszy rzut oka
- 🔧 Pasek kalorii działa dla każdego dnia — nawet jeśli nie masz zapisanego TDEE z pomiaru, aplikacja wylicza je z profilu ciała (wzrost, wiek, płeć, aktywność) i ostatniej wagi
- 📈 Trend wagi w dzienniku — przy każdym pomiarze widzisz strzałkę ▲/▼ pokazującą zmianę względem poprzedniego ważenia, od razu wiesz czy waga idzie w dobrym kierunku

### v1.0.151 (2026-06-07)

- 👆 Klikalne kropki na zdjęciu posiłku — tapnij w numer na zdjęciu, a lista przewinie się do odpowiedniego składnika i podświetli go na żółto

### v1.0.150 (2026-06-07)

- 🧊 Nowy ekran wyników skanowania lodówki — zdjęcie z ponumerowanymi punktami dla każdego produktu, z możliwością przybliżania i przesuwania; lista produktów do edycji (nazwa, ilość, kategoria, stan)
- 🔢 Numerowane kropki na zdjęciach posiłków — każdy wykryty składnik ma wyraźny numer, a pod zdjęciem lista z tymi samymi numerami do łatwej edycji
- 💾 Skan lodówki zapisywany w bazie z timestampem — tak jak posiłki w kalendarzu, możesz w każdej chwili wrócić do ostatniego skanu
- 👨‍🍳 Keto-Szef AI korzysta ze skanu lodówki — "obiad z lodówki" automatycznie sprawdza dzisiejszy skan, a jeśli brak — wczorajszy. Jeśli skan jest starszy, Szef pyta czy użyć czy zeskanować od nowa---
_Ostatni build: 2026-06-08 00:36 · v1.0.154_