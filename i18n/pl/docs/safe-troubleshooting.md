# Bezpieczna diagnostyka handlu na urządzeniu

<!-- language-navigation -->
[English](../../../docs/safe-troubleshooting.md) | [Français](../../fr/docs/safe-troubleshooting.md) | [Deutsch](../../de/docs/safe-troubleshooting.md) | [Nederlands](../../nl/docs/safe-troubleshooting.md) |
[Español](../../es/docs/safe-troubleshooting.md) | [Español (España)](../../es-ES/docs/safe-troubleshooting.md) | [Italiano](../../it/docs/safe-troubleshooting.md) |
[Português (Portugal)](../../pt/docs/safe-troubleshooting.md) | [Português (Brasil)](../../pt-BR/docs/safe-troubleshooting.md) | [Polski](safe-troubleshooting.md)
<!-- /language-navigation -->

Jasne zgłoszenie jest przydatniejsze niż pełny zrzut danych konta. Zapisz zachowanie
przed zmianą ustawień lub ponowną instalacją aplikacji, ponieważ może to usunąć
przydatne lokalne dowody.

## Przydatne pola zgłoszenia

```text
Wersja/build aplikacji:
Wersja Androida i model urządzenia:
Tryb i stan działania:
Przybliżony czas zdarzenia i strefa czasowa:
Ekran lub działanie:
Oczekiwane zachowanie:
Zaobserwowane zachowanie:
Czy można odtworzyć? Jeśli tak, minimalne kroki:
Ewentualny komunikat błędu bez identyfikatorów konta:
```

Nie dołączaj kluczy API, kluczy prywatnych, fraz odzyskiwania, tokenów dostępu,
tokenów zakupu Google Play, dokumentów bankowych lub podatkowych ani pełnych
identyfikatorów zleceń giełdowych. Ukryj nazwy kont, salda i treści powiadomień
na publicznych zrzutach ekranu, gdy nie są potrzebne. Sprawdź eksporty przed
udostępnieniem; plik JSON nie jest anonimowy tylko dlatego, że nie wygląda jak zdjęcie.

## Najpierw obserwuj

- Odróżnij nadal wczytywany widok od potwierdzonego zera, niedostępnej danej lub
  wstrzymanego działania. Zapisz dokładny status zamiast go parafrazować.
- Zaznacz, czy pozycję otwarto poza aplikacją czy w niej i które urządzenie nią
  zarządzało. Observation monitoruje, a nie steruje wykonywaniem zleceń.
- Sprawdź Coinbase bezpośrednio, gdy pytanie dotyczy rzeczywistego zlecenia lub
  pozycji. Nie powtarzaj działania na zleceniu tylko z powodu opóźnienia widoku.
- Zapisz łączność, restarty, zmiany działania w tle i czas aktualizacji aplikacji.
  To wskazówki diagnostyczne, a nie dowód przyczyny.
- Nie zawieraj transakcji tylko po to, by odtworzyć błąd interfejsu. W miarę
  możliwości zacznij od Paper lub odtworzenia bez handlu.

## Dokąd wysłać

Korzystaj z [pomocy Citrine](https://citrineedge.com/pl/support/) w sprawach
konkretnego konta. Publiczne repozytorium dokumentacji służy poprawkom podręcznika,
a nie prywatnej pomocy w handlu. Przy podejrzeniu luk zobacz
[Zgłaszanie problemów z bezpieczeństwem](../SECURITY.md). Nigdy nie publikuj
danych uwierzytelniających, nawet na prośbę niezweryfikowanego konta.

[Powrót do podręcznika](../README.md)
