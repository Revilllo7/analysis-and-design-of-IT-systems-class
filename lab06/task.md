# Zadanie: Statyczna struktura systemu informatycznego poprzez tworzenia diagramu

## Diagram klas - notacja i semantyka
Diagram klas w języku UML służy do opisu struktury systemu poprzez przedstawienie jego klas, atrybutów, operacji oraz powiązań między nimi.
Każda klasa jest reprezentowana w postaci prostokąta podzielonego na trzy części:

**Nazwa klasy** – identyfikator klasy, zwykle pisany wielką literą.

**Atrybuty** – cechy lub dane opisujące stan obiektu danej klasy.

**Operacje (metody)** – działania, które klasa może wykonywać.

Diagram klas pozwala na zrozumienie, jakie obiekty występują w systemie i w jaki sposób są one ze sobą powiązane.

## Atrybuty diagramu klas
Atrybuty diagramu klas

Atrybut to właściwość klasy, która opisuje dane przechowywane przez jej obiekty. Każdy atrybut ma określony typ danych, zakres dostępu (np. publiczny, prywatny, chroniony) oraz opcjonalnie wartość domyślną.

Przykład notacji atrybutu:
```javascript
-nazwaAtrybutu: TypDanych = wartośćDomyślna
```

gdzie:
- \- oznacza dostęp prywatny,

- \+ oznacza dostęp publiczny,

- \# oznacza dostęp chroniony.

## Podstawowe relacje stosowane w diagramie klas
Podstawowe relacje stosowane w diagramie klas

Diagram klas przedstawia różne rodzaje relacji pomiędzy klasami. Do najczęściej stosowanych należą:

- Asocjacja – ogólne powiązanie między dwiema klasami.

- Agregacja – związek typu „całość–część”, w którym obiekt części może istnieć niezależnie od całości.

- Kompozycja – silniejsza forma agregacji, w której część nie może istnieć bez całości.

- Zależność (dependency) – wskazuje, że jedna klasa korzysta z innej.

Każda relacja może być opatrzona dodatkowymi informacjami, takimi jak krotność (np. 1..*, 0..1) określająca liczbę wystąpień obiektów w danej relacji.

## Dziedziczenie

Dziedziczenie jest mechanizmem pozwalającym na tworzenie nowych klas w oparciu o już istniejące. Klasa pochodna (podklasa) dziedziczy cechy i zachowania klasy bazowej (nadklasy), co umożliwia ponowne wykorzystanie kodu i ułatwia jego utrzymanie.
Na diagramie UML dziedziczenie przedstawia się za pomocą strzałki z pustym trójkątem skierowanym w stronę klasy bazowej.

## Przykład 1. (Własny np. materiały)

## Przykład 2. czytelnia

## Przykład 3. projekt zespołowy

## Wiele diagramów klas w złożonych projektach - przykładowa struktura

## Wnioski (zalety, zastosowania, implementacje, itd)