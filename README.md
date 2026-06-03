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

**[⬇️ Pobierz najnowszy APK — v1.0.104](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.104)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.105 (2026-06-03)

- 🍽️ Nowy edytor posiłku — po zrobieniu zdjęcia pokazuje się pełnoekranowy edytor z możliwością poprawienia wszystkich danych od AI
- ✏️ Każdy składnik można edytować — nazwa, kcal, białko, tłuszcze, węglowodany, błonnik, cukry, składniki i opis
- ➕ Dodawanie własnych składników przez tapnięcie na zdjęciu — wskaż palcem gdzie jest jedzenie, a aplikacja doda nową kropkę
- 🔄 Ponowne rozpoznanie przez AI — wybierz inny model (Gemini 2.0 Flash, 2.5 Flash, ChatGPT, OpenRouter) i spróbuj ponownie bez wychodzenia z edytora
- 📊 Podsumowanie makro na żywo — suma kalorii, węgli, białka i tłuszczu aktualizuje się automatycznie przy każdej zmianie
- 📝 Edycja istniejących posiłków — z ekranu szczegółów posiłku możesz w każdej chwili ponownie rozpoznać lub poprawić składniki

### v1.0.104 (2026-06-03)

- 🔗 Własny model AI (tekst) w ustawieniach — podepnij ChatGPT, OpenRouter, NVIDIA NIM, Groq, OpenCode Zen lub HuggingFace jako dodatkowe źródło analizy etykiet, gdy Gemini nie poradzi sobie sam
- 📷 Własny model AI (obraz) w ustawieniach — skonfiguruj ChatGPT Vision lub OpenRouter Vision do rozpoznawania etykiet ze zdjęć, zamiast wbudowanego Gemini
- 🔄 Inteligentny fallback AI — jeśli Gemini nie jest skonfigurowane, aplikacja automatycznie używa Twojego własnego modelu jako głównego, a wbudowany Gemini jako zabezpieczenie

### v1.0.103 (2026-06-03)

- 📊 Nowy licznik zapytań AI w ustawieniach — widzisz ile z 1500 dziennych zapytań do Gemini zostało wykorzystane, z paskiem postępu i ostrzeżeniami zanim skończy się limit
- 🚫 Automatyczne blokowanie zapytań po przekroczeniu limitu — AI przestaje wysyłać zapytania do Gemini gdy skończy się dzienny limit, zamiast zwracać nieczytelny błąd 429

### v1.0.101 (2026-06-03)

- 🖼️ Biblioteka ikon lodówkowych — 100 ręcznie rysowanych ikon produktów (nabiał, mięso, ryby, owoce, warzywa, napoje, sosy, dania gotowe, desery) do łatwego oznaczania kategorii w aplikacji
- 🔍 Nowy komponent FridgeIcon — wystarczy podać nazwę ikony, a resztą zajmuje się system

### v1.0.100 (2026-06-02)

- 🔧 Poprawa skanowania lodówki — AI nie ucina już odpowiedzi przy dużej liczbie produktów, zwiększono limit tokenów
- 🔧 Lepsze parsowanie JSON z AI — dodano obsługę tablic i rozszerzone naprawianie błędów składni
- 🔄 Inteligentne ponawianie przy błędzie skanowania — nie tracisz już przeanalizowanych zdjęć; możesz kontynuować od nieudanego lub wziąć to co udało się rozpoznać---
_Ostatni build: 2026-06-03 18:52 · v1.0.104_