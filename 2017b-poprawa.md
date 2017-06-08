<p style="text-align: right; width: 100%">Programowanie I C, 2.06.2017</p>

<h1 style="text-align: center">Kolokwium</h1>

## Zad 1 (3 punkty)
Napisz program, który dla zadanych *a*, *b*, *c* i *n* znajdzie rozwiązanie
równania *a*x<sup>2</sup> + b*x + c ≡ 0 (mod n)*

Wejście programu to stanowić będą 4 liczby całkowite: *a*, *b*, *c* i *n*.
*0 &le; a, b, c &le; 1000000*, zaś *2 &le; n &le; 1500*.

Na wyjściu ma się znaleźć jedna liczba
całkowita - jedno z rozwiązań równania,
lub tekst "BRAK ROZWIĄZANIA" jeśli rozwiązanie nie istnieje.

Przykłady:

| Wejście        | Wyjście           |
| ------------- |-------------|
| `0 0 3 10`      | `BRAK ROZWIĄZANIA` |
| `1 1 4 10`    | `2`      |
| `1 113 344 1234` | `541`      |

## Zad 2 (3 punkty)
Napisz program, który dla zadanego zbioru liczb zwróci jego medianę (wartość środkową).

Dla zbiorów o nieparzystej długości, mediana to element który po posortowaniu zbioru znajduje się na środkowej pozycji.

Dla zbiorów o parzystej długości, mediana to średnia arytmetyczna dwóch środkowych elementów.

Wejście zawiera liczbę *n* - liczbę elementów zbioru, a następnie *n* wartości elementów. Wyjście powinno zawierać jedną liczbę - medianę zbioru.

Np.

| Wejście        | Wyjście           |
| ------------- |-------------|
| 7 <br> 12 4 5 0 0 3 10      | 4 |
| 4 <br> 5 4 3 2    | 3.5      |
| 5 <br> 1 4 5 2 1 |  2     |


## Zad 3 (4 punkty)
Dany jest graf nieskierowany *n &lt; 1000* wierzchołkach i *m &lt; 10000* krawędziach. Wierzchołki są ponumerowane od *0* do *n-1*.

Napisz program, który dla danego grafu i danej pary wierzchołków *x0*, *x1* sprawdzi czy istnieje droga między wierzchołkami.

Wejście:
- *n*, *m*, *x0*, *x1* - kolejno ilość wierzchołków, krawędzi, numer wierzchołka początkowego i końcowego
- *m* par liczb *x,y*

Wyjście: `TAK` lub `NIE`

Np.

| Wejście        | Wyjście           |
| -------------------------------- |-------------|
| 4 3 0 3 <br> 0 1<br>1 2 <br>2 3  | TAK |
| 5 4 0 2 <br> 0 1 <br> 0 5<br> 1 4<br>2 3 | NIE      |
