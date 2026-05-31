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

**[⬇️ Pobierz najnowszy APK — v1.0.64](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.64)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.50 (2026-06-01)

- 🔒 Tworzenie własnych profili wymaga teraz licencji — darmowa wersja pozwala korzystać z profili wbudowanych
- 🔒 Klonowanie profili również wymaga licencji

### v1.0.49 (2026-05-31)

- ✏️ Nowy edytor produktu — kliknij "Edytuj produkt" na ekranie wyniku, aby poprawić nazwę, wartości odżywcze i składniki
- 🌐 Szukaj w sieci — edytor automatycznie wyszukuje dane w OpenFoodFacts i Spoonacular, aby uzupełnić brakujące informacje
- 🔄 Zapisz i oceń ponownie — po edycji produkt jest od nowa oceniany względem Twojego profilu
- 📝 Wypełnij ręcznie — wszystkie pola można edytować samodzielnie, gdy wyniki z sieci są niepełne

### v1.0.48 (2026-05-30)

- 🔑 Własny klucz Google Gemini AI — skonfiguruj darmowy klucz i korzystaj z AI bez błędów i przeciążeń
- 🧭 Kreator konfiguracji AI krok po kroku — prosty przewodnik dla każdego, nawet bez znajomości technologii
- ⚡ Większa stabilność i szybkość — własny klucz = szybsze działanie i brak limitów

### v1.0.47 (2026-05-30)

- 🍽️ Nowa funkcja "Klasyfikacja jedzenia" — zrób zdjęcie talerza, a AI rozpozna produkty i oceni je względem Twojej diety
- 🎯 Kolorowe kropki na zdjęciu — zielone = pasuje, czerwone = nie pasuje do profilu
- 👆 Kliknij kropkę, aby zobaczyć skład typowych składników i wartości odżywcze danego produktu
- 📅 Dziennik żywieniowy z kalendarzem — zapisuj posiłki i przeglądaj co jadłeś i kiedy
- ⏰ Automatyczne określanie typu posiłku (śniadanie/lunch/kolacja/przekąska) na podstawie godziny
- ⚡ Ustawienie jakości analizy — szybka (Gemini 2.0 Flash) lub zrównoważona (Gemini 2.5 Flash)

### v1.0.46 (2026-05-29)

- 🔧 Poprawa działania Vision AI — lepsza diagnostyka błędów API i limit czasu
- 🔄 Zaktualizowano domyślny model Gemini do gemini-2.5-flash
- 🏷️ Etykiety pól z kolorowym statusem — zielone gdy wypełnione, czerwone gdy puste
- 🔢 Dodano pole EAN — ręczne wpisanie kodu kreskowego podczas skanowania etykiety
- 📸 Lepsze rozpoznawanie nazwy produktu — Vision AI analizuje całe zdjęcie
- 🔁 "Zapisz do bazy" działa teraz także bez kodu EAN — produkt zawsze trafia do lokalnej bazy
- 🧭 Nutri-Score na ekranie kamery — skala A–E z podświetleniem ostatniego wyniku
- 📋 Log OCR domyślnie zwinięty — przycisk rozwijania panelu z szczegółami
- 🔙 Back: najpierw wróć do "Skanuj", drugi raz dopiero wyjście
- 💪 Wytrzymały parser JSON — radzi sobie z dziwnymi formatami odpowiedzi AI
- 🎯 Nazwa produktu nie jest wymagana — dane wejdą do formularza nawet bez nazwy---
_Ostatni build: 2026-06-01 00:51 · v1.0.64_