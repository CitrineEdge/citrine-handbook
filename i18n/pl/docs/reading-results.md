# Odczytywanie backtestów, prowizji i płatności finansujących (funding)

<!-- language-navigation -->
[English](../../../docs/reading-results.md) | [Français](../../fr/docs/reading-results.md) | [Deutsch](../../de/docs/reading-results.md) | [Nederlands](../../nl/docs/reading-results.md) |
[Español](../../es/docs/reading-results.md) | [Español (España)](../../es-ES/docs/reading-results.md) | [Italiano](../../it/docs/reading-results.md) |
[Português (Portugal)](../../pt/docs/reading-results.md) | [Português (Brasil)](../../pt-BR/docs/reading-results.md) | [Polski](reading-results.md)
<!-- /language-navigation -->

Rzetelne porównanie wymaga tego samego instrumentu, dat, strefy czasowej,
środków początkowych, alokacji i założeń kosztowych. Paper, Shadow, odtwarzanie
historii i rzeczywista realizacja nie mają identycznych danych wejściowych ani wykonań.

## Arkusz porównawczy

Zapisz te dane przy obu wynikach przed porównaniem końcowej kwoty w dolarach:

| Dane | Dlaczego są ważne |
| --- | --- |
| Produkt i kierunek | Kontrakty BTC i ETH nie są zamienne; spot i futures to różne produkty |
| Czas początku i końca oraz strefa czasowa | Inna granica może objąć dodatkowe wejście, zamknięcie lub zdarzenie finansowania |
| Środki początkowe i alokacja | Inna zdolność do otwierania pozycji może zmienić liczbę kontraktów |
| Zamknięte transakcje i otwarta ekspozycja | Suma zakończonych transakcji nie jest tym samym co konto z otwartą pozycją |
| Ceny wykonania i prowizje | Wykonania symulowane i rzeczywiste mogą się różnić; prowizje konta i domyślne nie są zamienne |
| Pokrycie danymi finansowania i jego znak | Uznanie, obciążenie, zweryfikowane zero i niedostępna informacja mają różne znaczenia |
| Podstawa księgowa i okres | Składnik salda zgłoszony przez giełdę nie jest automatycznie wynikiem jednej sesji |

## Nie odejmuj tej samej prowizji dwa razy

Wyłącznie hipotetyczne obliczenie: załóżmy, że PnL brutto zamkniętych transakcji
wynosi **+$24**, prowizje handlowe **$4**, a uwzględnione finansowanie to uznanie
**+$1**. Jeśli raportowany zrealizowany wynik jest już pomniejszony o te prowizje,
wynosi **+$20**. Dodanie uznania z finansowania daje **+$21**. Ponowne odjęcie
$4 oznaczałoby podwójne uwzględnienie tego kosztu.

Przykład wyjaśnia zasadę uzgadniania; nie jest uniwersalnym wzorem dla każdego
ekranu ani zestawienia giełdowego. Przeczytaj wskazaną podstawę wyniku,
uwzględnione koszty, pokrycie danymi finansowania i otwartą ekspozycję.
Finansowanie jest osobnym składnikiem księgowym i nie musi należeć do wyniku
zamkniętych transakcji.

## Brak danych nie oznacza zera

Liczbowe zero może oznaczać znane zero. Brak danych finansowania nie dowodzi,
że nie było obciążenia ani uznania. Odtwarzanie historii korzysta z dostępnych
danych finansowania spełniających wymagania; sprawdź szczegóły wyniku przed
porównaniem z rozliczeniem giełdy. Nie wyliczaj dokładnego finansowania z różnicy
dwóch zaokrąglonych sald.

## Obsunięcie nie oznacza tylko najgorszej transakcji

Maksymalne obsunięcie (drawdown) mierzy spadek od wcześniejszego szczytu wybranej
serii wartości kapitału lub salda. Hipotetyczna seria
**$1000 -> $1030 -> $1018** ma spadek od szczytu do dołka równy **$12**,
chociaż kończy się powyżej salda początkowego. Kilka stratnych transakcji może
przyczynić się do jednego obsunięcia.

Podstawa próbkowania ma znaczenie. Seria oparta na zamknięciach różni się od
ciągłej wyceny kapitału uwzględniającej otwarte pozycje i może nie pokazywać
minimum w trakcie transakcji. Korzystaj z podstawy opisanej w szczegółach wyników
Citrine; nie traktuj wartości opartej na zamknięciach jako największej możliwej
straty rzeczywistej ani nie zakładaj, że zlecenia stop gwarantują konkretną cenę wykonania.

## Gdy dwa przebiegi się różnią

Porównaj najpierw ilości i znaczniki czasu wykonania, potem ceny, źródło prowizji,
finansowanie i otwartą ekspozycję. Zachowaj oryginalne eksporty bez zmian.
Kontaktując się z pomocą, opisz rozbieżność i podaj tylko informacje, o które
rzeczywiście poproszono; nie publikuj pełnych eksportów kont.

[Metodyka backtestingu](https://citrineedge.com/pl/backtesting/) |
[Bezpieczna diagnostyka](safe-troubleshooting.md) |
[Powrót do podręcznika](../README.md)
