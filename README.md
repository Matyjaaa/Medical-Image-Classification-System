# Medical Image Classification System (SPIDER-Breast)

## O projekcie
Aplikacja okienkowa (GUI) służąca do automatycznej analizy i klasyfikacji obrazów histopatologicznych tkanek piersi. System wykorzystuje model głębokiego uczenia (SPIDER-breast), aby wspierać diagnostykę medyczną poprzez detekcję zmian nowotworowych na podstawie wycinków obrazów mikroskopowych.

## Główne funkcjonalności
* **Przetwarzanie obrazów (Preprocessing):** Automatyczne przycinanie (crop), skalowanie i normalizacja zdjęć medycznych (PNG, JPG, TIFF) do wymagań wejściowych modelu.
* **Klasyfikacja ML:** Wykorzystanie pretrenowanego modelu (PyTorch/HuggingFace) do przewidywania etykiety diagnostycznej oraz obliczania prawdopodobieństwa wystąpienia nowotworu.
* **Wizualizacja:** Możliwość podglądu poszczególnych kroków preprocessingu oraz generowanie tzw. Mapy Prawdopodobieństwa, wskazującej obszary istotne dla decyzji algorytmu.
* **Moduł Historii (CRUD):** Wbudowany system zapisu wyników do lokalnej bazy danych (JSON), pozwalający na przeglądanie historii analiz, dodawanie notatek diagnostycznych i zarządzanie wpisami.
* **Interfejs Użytkownika:** Responsywne i intuicyjne GUI zbudowane przy użyciu biblioteki Tkinter.

## Stos technologiczny
* **Język:** Python
* **Uczenie Maszynowe:** PyTorch, HuggingFace Transformers
* **Przetwarzanie obrazu:** Pillow (PIL), OpenSlide, tifffile
* **Frontend / GUI:** Tkinter
* **Baza danych:** JSON

** Projekt został zrealizowany w 5-osobowym zespole inżynierskim.** 
