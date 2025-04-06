# BUG_001_OLX_Wyszukiwanie

**Tytuł:** Brak wyników wyszukiwania dla istniejących ogłoszeń

**Data zgłoszenia:** 2025-04-06  
**Zgłaszający:** Fabian  

---

## 🔍 Opis błędu:

Po wpisaniu frazy "rower" w wyszukiwarkę OLX i kliknięciu "Szukaj", nie zostają wyświetlone żadne wyniki, mimo że ogłoszenia o rowerach istnieją.

---

## ✅ Kroki do odtworzenia:

1. Wejdź na stronę główną [olx.pl](https://www.olx.pl/)
2. Wpisz w wyszukiwarkę: `rower`
3. Kliknij przycisk `Szukaj`
4. Obserwuj wyniki

---

## ❌ Rzeczywisty rezultat:

- Brak wyników.
- Komunikat: "Nie znaleziono wyników dla zapytania 'rower'".

---

## ✔️ Oczekiwany rezultat:

- Lista ogłoszeń zawierających słowo "rower".

---

## 💻 Środowisko testowe:

- System operacyjny: Windows 10  
- Przeglądarka: Google Chrome 122.0  
- Rozdzielczość: 1920x1080  
