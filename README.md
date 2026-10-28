# Fleet & Route Analytical Dashboard
Dwumodułowy model analityczny stworzony z myślą o wsparciu procesów *Revenue Managementu* oraz *analizy operacyjnej punktowości (On-Time Performance)* w liniach lotniczych.

## O projekcie
Projekt składa się z dwóch niezależnych, spójnych wizualnie i merytorycznie paneli menedżerskich bazujących na tym samym zbiorze danych operacyjno-finansowych:
1. **Moduł Finansowy (Revenue & Yield Management):** Analiza całkowitych przychodów, liczby pasażerów oraz średniej ceny biletu (Yield) w ujęciu poszczególnych portów wylotowych.
2. **Moduł Operacyjny (Delay & Reliability Analysis):** Monitorowanie punktowości, całkowitego czasu opóźnień oraz liczby incydentów operacyjnych na trasach.

## Zastosowane mechanizmy w Excel
* **Tablice dynamiczne:** `SORTBY`, `UNIQUE`, `AVERAGEIFS`, `SUMIFS`, `COUNTIFS`.
* **Menedżer nazw (Name Manager):** Globalna zmienna `wybrane_lotnisko` sterująca interaktywnymi filtrami w czasie rzeczywistym.
* **Formuły warunkowe z obsługą błędów:** Wykorzystanie funkcji `NA()` do ukrywania nieaktywnych serii danych na wykresach.
* **Zaawansowane wykresy:** Poziome wykresy paskowe z nałożonymi seriami (**100% overlap**) dla dynamicznego podświetlania wybranego portu lotniczego na wykresie.

## Podgląd Dashboardu

### 1. Panel Finansowy i Pasażerski
<img width="1842" height="728" alt="Panel Finansowy i Pasażerski" src="https://github.com/user-attachments/assets/3d5c1b04-35ac-4355-b799-66ce66dc72d8" />

### 2. Panel Operacyjny (Opóźnienia i Niezawodność)
<img width="1727" height="718" alt="Panel Operacyjny (Opóźnienia i Niezawodność)" src="https://github.com/user-attachments/assets/44201bbf-16ae-4b2f-8c35-a7cbb9951591" />


