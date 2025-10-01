# Kłamca czy pomocnik? AI dla sceptyków

**Główna teza:** LLM to nie magiczne rozwiązanie, ale potężne narzędzie, które przy właściwym zastosowaniu może skalować to, co ludzie robią najlepiej.

***

## Część 1: Dlaczego sceptycyzm jest zdrowy

Według ostatnich raportów MIT, **95% projektów AI nie przynosi zwrotu z inwestycji**.
📊 [Źródło: MIT AI Report 2025](https://www.artificialintelligence-news.com/wp-content/uploads/2025/08/ai_report_2025.pdf)

**Powód?**

- Hype i szum informacyjny
- Bardzo szybki postęp technologii
- Wysyp narzędzi bez jasnej strategii

> Nie technologia jest problemem, ale podejście do niej.

### Halucynacje AI a rzeczywistość

Można znaleźć wiele przykładów, gdzie odpowiedź wygenerowana przez AI została przyjęta za pewnik. Na przykład kanadyjskie linie lotnicze musiały honorować politykę zwrotów, którą chatbot sam wymyślił.
📰 [Air Canada vs chatbot](https://www.cbsnews.com/news/aircanada-chatbot-discount-customer/)

**💡 Key message:** *Sceptycyzm chroni przed kosztownymi błędami. Ale czy oznacza to, że powinniśmy zrezygnować?*

***

## Część 2: Jak LLM naprawdę działa - probabilistyka vs determinizm

LLM przewiduje następne słowo na podstawie wzorców, nie faktów (przykład dla człowieka: "wlazł kotek na...") - **to cecha, a nie wada!**

### Przykład praktyczny

❓ **Pytanie:** Ile "r" jest w "strawberry"?
🤖 **LLM:** Prawdopodobnie się pomyli albo odpowiedź nie zawsze będzie taka sama.
✅ **Lepsze podejście:** Zapytaj LLM o napisanie skryptu, który to policzy.

**💡 Key message:** *Nie pytajcie LLM o 2+2. Pytajcie go, jak napisać lepszy email do trudnego klienta.*

***

## Część 3: Jak zarządzać wadami LLM i maksymalizować zalety

### LLM vs Praktykant w firmie

| Wada LLM | Praktykant | Rozwiązanie |
| :-- | :-- | :-- |
| Jest powolny - czekasz na odpowiedź minutę | Też potrzebuje czasu na wykonanie zadania | Czy procesy w firmie nie trwają dłużej? |
| Często się myli | Również popełnia błędy | Nadzór i weryfikacja |
| "Sam zrobię to szybciej" | Też tak myślisz o praktykantach | Inwestycja w przyszłość |
| Trzeba tłumaczyć | Potrzebuje instrukcji i szkoleń | Precyzyjne polecenia |

### Strategia implementacji

- **Odizolowanie LLM** do pojedynczego zadania w procesie
- **Testować, mierzyć i oceniać** każdy przypadek użycia
- **Human in the loop**

**💡 Key message:** *LLM to jak praktykant - ma wady, ale przy właściwym nadzorze i ograniczeniu zadań może być bardzo produktywny.*

***

## Część 4: It's all about data

### Fundamentalne ograniczenia

- LLM jest nauczony na danych, w których **nie ma danych Twojej firmy**
- LLM potrzebuje kontekst (przykład z porównaniem 9.11 i 9.9 - daty vs liczby)
- **Shit in - shit out** dotyczy każdego podejścia, deterministycznego i probabilistycznego


**💡 Key message:** *LLM bez właściwych danych to jak GPS bez map - może jechać, ale nie wie dokąd.*

***

## Część 5: Przykłady obszarów implementacji AI

### 🔍 Wyszukiwarki

- Przykład mojego startupu - Semantic search w polskich kodeksach prawnych
- Jak ludzie używają wyszukiwarek?


### 🎫 Obsługa ticketów

- Gdzie czynność człowieka jest na dobrym poziomie, ale się nie skaluje
- **Human in the loop** - AI kategoryzuje, człowiek decyduje


### 🛡️ Moderacja treści

- Pierwszy filtr automatyczny
- Eskalacja trudnych przypadków do człowieka

***

## Zakończenie

### Kluczowe elementy sukcesu:

- ✅ **Jakość danych wejściowych**
- ✅ **Precyzyjny kontekst**
- ✅ **Human in the loop**

**💡 Final Key Message:** *AI to nie zamiennik, to wsparcie.*

### 🎁 Bonus tricks

**Jak dobrze zbudować prompt w dziedzinie, której się w ogóle nie zna?**
