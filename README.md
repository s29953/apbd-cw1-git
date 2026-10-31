
# APBD – Ćwiczenie 1: Git

## Opis projektu

Prosta aplikacja konsolowa napisana w języku C# w ramach ćwiczeń z przedmiotu Aplikacje Baz Danych (APBD).

Program:
- Wyświetla komunikat `Hello, APBD!` za pomocą klasy `Greeting`.
- Oblicza sumę liczb z tablicy `{ 2, 4, 6 }` za pomocą metody `CalculateSum` z klasy `StatisticsHelper`.
- Wyświetla wynik obliczeń w konsoli.

## Wymagania

- .NET 9 SDK

## Uruchomienie programu

1. Otwórz terminal w katalogu projektu.
2. Wykonaj polecenie:

   ```bash
   dotnet run
   ```

## Oczekiwany wynik

```text
Witaj w kalkulatorze APBD!
Suma: 12
Średnia: 4
Liczba elementów: 3
Maksimum: 6
```

## Struktura projektu

- `Program.cs` – główny plik aplikacji.
- `Greeting.cs` – klasa odpowiedzialna za powitanie.
- `StatisticsHelper.cs` – klasa obliczająca sumę liczb.
- `GitPractice.csproj` – konfiguracja projektu .NET.
- `.gitignore` – plik określający elementy ignorowane przez Git.
