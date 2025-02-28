# Darwin Simulation

## Opis projektu
Projekt "Darwin Simulation" to aplikacja umożliwiająca przeprowadzanie symulacji ekosystemu w czasie rzeczywistym. Program pozwala na uruchamianie symulacji z wybranymi parametrami, analizowanie statystyk oraz wizualizację interakcji pomiędzy organizmami na mapie.

## Wykorzystane technologie
- **Java 21**
- **JavaFX**
- **Gradle**
- **IntelliJ IDEA**

## Główne funkcjonalności
- Możliwość wyboru gotowych konfiguracji lub stworzenia własnych ustawień symulacji
- Obsługa wielu jednocześnie uruchomionych symulacji w osobnych oknach
- Animacja przedstawiająca pozycje zwierząt i roślin na mapie
- Wizualizacja poziomu energii zwierząt (np. poprzez kolory lub paski zdrowia)
- Możliwość zatrzymania i wznowienia symulacji w dowolnym momencie
- Śledzenie statystyk, takich jak:
  - liczba zwierząt i roślin
  - liczba wolnych pól
  - najpopularniejsze genotypy
  - średni poziom energii zwierząt
  - średnia długość życia martwych zwierząt
  - średnia liczba dzieci żyjących zwierząt
- Możliwość śledzenia wybranego zwierzaka – w tym jego genomu, poziomu energii, liczby zjedzonych roślin, dzieci i potomków
- Podświetlanie pól preferowanych przez rośliny oraz zwierząt o dominującym genotypie
- Eksport statystyk do pliku CSV, umożliwiającego analizę w programach takich jak Excel

## Przykłady działania
### Zdjęcie mapy symulacji:
*![image](https://github.com/user-attachments/assets/d3d577bc-9124-4a4f-8ad6-008086914fcc)*  
### Zdjęcie ekranu ustawień:
*![image](https://github.com/user-attachments/assets/54fa952d-758a-40b0-bb8d-6e2bac76b6a8)*

## Wymagania systemowe
- Java 21+
- System operacyjny: Windows, Linux, macOS
- IntelliJ IDEA (zalecane do rozwoju aplikacji)

## Instalacja i uruchomienie
1. Sklonuj repozytorium:
   ```sh
   git clone https://github.com/igorpie1705/Darwin-Simulation
   ```
2. Przejdź do folderu projektu:
   ```sh
   cd Darwin-Simulation
   ```
3. Uruchom aplikację za pomocą Gradle:
   ```sh
   ./gradlew run  # Linux/macOS
   gradlew.bat run  # Windows
   ```

## Kontakt
Jeśli masz pytania dotyczące projektu zapraszam do kontaktu:)

