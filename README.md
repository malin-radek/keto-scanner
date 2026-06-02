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

**[⬇️ Pobierz najnowszy APK — v1.0.100](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.100)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.102 (2026-06-03)

- ✨ Efektowne odkrywanie produktów podczas skanowania lodówki — ikony wyłaniają się z ciemności, a rozpoznane składniki ujawniają się losowo na ekranie zamiast nudnego paska postępu

### v1.0.101 (2026-06-03)

- 🖼️ Biblioteka ikon lodówkowych — 100 ręcznie rysowanych ikon produktów (nabiał, mięso, ryby, owoce, warzywa, napoje, sosy, dania gotowe, desery) do łatwego oznaczania kategorii w aplikacji
- 🔍 Nowy komponent FridgeIcon — wystarczy podać nazwę ikony, a resztą zajmuje się system

### v1.0.100 (2026-06-02)

- 🔧 Poprawa skanowania lodówki — AI nie ucina już odpowiedzi przy dużej liczbie produktów, zwiększono limit tokenów
- 🔧 Lepsze parsowanie JSON z AI — dodano obsługę tablic i rozszerzone naprawianie błędów składni
- 🔄 Inteligentne ponawianie przy błędzie skanowania — nie tracisz już przeanalizowanych zdjęć; możesz kontynuować od nieudanego lub wziąć to co udało się rozpoznać

### v1.0.99 (2026-06-02)

- 📸 Skanowanie lodówki z użyciem aparatu — zrób do 5 zdjęć lodówki, AI rozpoznaje produkty w każdej z nich, scala wyniki i przekazuje Keto-Szefowi do ułożenia idealnego przepisu
- 🧠 Uniwersalny pipeline skanowania — przygotowany do przyszłych zastosowań (np. inwentaryzacja zapasów) bez potrzeby przebudowy

### v1.0.96 (2026-06-02)

- 🧊 Dwie kategorie akcji Szefa: "Coś z lodówki" (z Twoich produktów) i "Zaszalejmy" (kreatywne przepisy)
- 🌍 Szef zna Twój kraj i proponuje lokalne składniki — nad Bałtykiem ryby, nad Morzem Śródziemnym owoce morza
- 🎯 Jeśli poprosisz o konkretny składnik (np. krewetki), Szef robi przepis bez gadania — lokalność nie blokuje---
_Ostatni build: 2026-06-03 00:17 · v1.0.100_