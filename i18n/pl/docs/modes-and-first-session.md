# Tryby Citrine i lista kontrolna pierwszej sesji

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](../../fr/docs/modes-and-first-session.md) | [Deutsch](../../de/docs/modes-and-first-session.md) | [Nederlands](../../nl/docs/modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](../../es-ES/docs/modes-and-first-session.md) | [Italiano](../../it/docs/modes-and-first-session.md) |
[Português (Portugal)](../../pt/docs/modes-and-first-session.md) | [Português (Brasil)](../../pt-BR/docs/modes-and-first-session.md) | [Polski](modes-and-first-session.md)
<!-- /language-navigation -->

## Wybierz zakres odpowiedzialności, nie tylko saldo

| Tryb | Punkt wyjścia | Wysyła rzeczywiste zlecenia? | Właściwe zastosowanie |
| --- | --- | --- | --- |
| Paper | Wybrane przez Ciebie hipotetyczne saldo | Nie | Poznanie obszaru roboczego i śledzenie sesji symulowanej bez importowania klucza API |
| Shadow | Dane uwierzytelnionego konta, a następnie własna sesja symulowana | Nie | Porównanie symulacji uwzględniającej konto z warunkami rynkowymi |
| Observation | Widok rzeczywistego konta | Nie, również bez ręcznego zamykania i zarządzania zabezpieczeniami | Monitorowanie konta bez używania tego urządzenia do wykonywania zleceń |
| Standard | Rzeczywiste konto | Tak, gdy aktywne są Complete i uprawniony dostęp do handlu | Rzeczywiste otwieranie pozycji i dozwolone zarządzanie nimi |

W szczegółach portfela Standard i Observation są wyświetlane jako **Standardowy**
i **Obserwacja**; przełącznik nadal ma etykietę **Tryb Observation**.

Backtesting to odtwarzanie historii, a nie piąty tryb konta rzeczywistego.
Demonstracja z przewodnikiem (Guided Demo) przedstawia interfejs na przykładowym
koncie i nie wymaga zawarcia transakcji.

## Przed sesją Paper

- Otwórz **Samouczek** w sekcji **Pomoc**, aby uruchomić demonstrację z przewodnikiem,
  jeśli nie znasz obszaru roboczego.
- Świadomie wybierz saldo początkowe i alokację. Zachowaj te wartości, jeśli
  planujesz późniejsze porównywanie sesji.
- Odczytaj tryb i stan działania. Sam widoczny wykres nie oznacza, że sesja
  działa ani że warunki wejścia są spełnione.
- Przejrzyj szczegóły Edge, szczegóły wyniku i ich objaśnienia zamiast
  interpretować pojedynczą liczbę bez kontekstu.
- Do porównań zachowaj daty, tryb i eksport sesji.

## Przed użyciem z połączonym kontem

- Potwierdź, że używasz uprawnionego konta Coinbase Advanced dla obsługiwanych
  bezterminowych kontraktów BTC i ETH Coinbase Derivatives Exchange (CDE), a nie
  produktów spot ani produktów Coinbase International Exchange (INTX).
- Przed połączeniem konta sprawdź [aktualną dostępność według kraju](https://citrineedge.com/pl/availability/).
  W Kanadzie dostęp jest ograniczony do kont spełniających wymagania w
  obsługiwanych prowincjach lub terytoriach.
- Postępuj zgodnie z [aktualną konfiguracją klucza](https://citrineedge.com/pl/coinbase-api-setup/).
  Importuj dane uwierzytelniające w aplikacji, nigdy w zgłoszeniu, wiadomości
  ani formularzu pomocy.
- Uprawnienie View umożliwia dostęp do konta. Handel rzeczywisty wymaga również
  Trade. Citrine nie wymaga uprawnień Transfer, Receive ani wypłat.
- Sprawdź weryfikację, wybrany tryb, alokację, dostępne środki, zdolność do
  otwierania pozycji i każdy status wymagający uwagi. Warunek Edge oznaczony
  jako gotowy nie oznacza obietnicy natychmiastowego wysłania zlecenia.
- Utrzymuj zasilanie i połączenie urządzenia Android oraz konfigurację działania
  aplikacji w tle. Dodatkowe urządzenie jest opcją, nie wymogiem.
- Zachowaj bezpośredni dostęp do Coinbase do sprawdzania konta lub pilnych działań.

## Pauza i wyjście to różne działania

**Wstrzymaj handel** wstrzymuje nowe wejścia; dozwolone zarządzanie rzeczywistymi pozycjami
może trwać dalej. **Wyjdź z Citrine** zatrzymuje lokalne działanie. Nie zamyka
automatycznie otwartych pozycji ani nie anuluje istniejących zleceń na giełdzie.

Zabezpieczenie zaakceptowane i utrzymywane przez Coinbase różni się od zarządzania
na urządzeniu. Observation nie zarządza zabezpieczeniami. Po przerwie sprawdź
rzeczywisty stan działania i giełdy zamiast zakładać wznowienie handlu.

[Pełny przewodnik po produkcie](https://citrineedge.com/pl/guide/) |
[Obowiązki dotyczące bezpieczeństwa](https://citrineedge.com/pl/security/) |
[Powrót do podręcznika](../README.md)
