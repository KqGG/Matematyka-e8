# Wprowadzenie
Witaj,
Ten dokument (Który nie jest jeszcze dokończony) zawiera zdecydowana wiekszość pojęć potrzebnych Ci, aby napisac **Egzamin Ósmoklasisty z Matematyki** na co najmniej <ins>90%</ins>.<br><br>
Zakładamy, że <ins>**umiesz dodawać, odejmować, mnożyć i dzielić**</ins> na poziome co najmniej 4 klasy Szkoły Podstawowej.<br><br>
Stanowczo odradzamy omijanie pojęć uznanych przez Ciebie za dobrze już rozumiane - wiele bardziej zaawansowanych kwestii umieściliśmy w prostych tematach, <ins>pamiętaj więc o czytaniu całości</ins>.<br><br>
Nie zapominaj o zrobieniu <ins>kilku zadań do każdego zawartego tutaj tematu</ins> aby mieć pewność, że w pełni rozumiesz każdy z nich.<br><br>
**Powodzenia!**
# Index
- [Przeliczanie jednostek](#t-jednostki)
- [NWW i NWD](#t-nww)
- [Cechy podzielności liczb](#t-div)
# Tematy
## <a name="t-jednostki"></a>Przeliczanie Jednostek
### Co to jest Jednostka?
> **Jednostka oznacza standardową miarę wielkości fizycznej (np. metr, gram).**
### Przedrostek - wyjaśnienie
Przedrostków używasz w matematyce bardzo często i nawet możesz nie zdawać sobie z tego sprawy.<br>
Jeśli mamy daną jednostke (np. metr) i potrzebujemy za pomocą niej pokazać jakąś bardzo małą lub bardzo dużą wartość, możemy wykorzystać do tego właśnie przedrostki.<br>
Zamiast pisać 0,01 metrów, możemy użyć przedrostka **centy**, aby ułatwić nam zapis (w tym przypadku otrzymamy 1 centymetr).<br>
Wartości przedrostków są zapisane w [Układzie SI](#w-si) zamieszczonym poniżej.<br>
Na przykład:
```
1dt (decytona) = 0,1t (tony)
20 000 000t = 20 Mt (megaton)
35 000dm (decymetrów) = 3 500 m (metrów) = 3,5 km (kilometra)
```
### Jednostki podniesione do kwadratu / sześcianu
Przeliczanie jednostek jest bardzo monotonne i przewidywalne, zwłaszcza kiedy korzystamy z [Układu SI](#w-si).<br>
Jednakże, inaczej wyglada to z jednostkami podniesonymi do kwadratu lub sześcianu (np. cm², m³).<br>
Jak już się pewnie domyślasz, przy przeliczaniu podnosimy wartość do odpowiedniej potęgi i dopiero wtedy przeliczamy na jednostkę z innym przedrostkiem, zgodnie z przypisanym mnoznikiem.<br>
Na przyklad:
```
100cm² = 100cm * 1cm = 1m * 0,01m = 0,01m² //bo 100² = 10 000, a 10 000 : 100 = 100
20m² = 0,002m * 0,0001m = 0,000002km²
6dm³ = 0,6dm * 0,1dm * 0,1dm= 0,006dm³

// dla porównania
100cm = 1m
20m = 0,02km
6dm = 0.6m
```
Pamiętaj o tym podczas pracy z np. polami figur.
### <a name="w-si"></a>Wybrane przedrostki z Układu SI:
| Symbol | Mnożnik     | Nazwa |
| ------ | ----------- | ----- |
| µ      | 0,000001    | mikro |
| m      | 0,001       | mili  |
| c      | 0,01        | centy |
| d      | 0,1         | decy  |
| da     | 10          | deka  |
| h      | 100         | hekto |
| k      | 1 000       | kilo  |
| M      | 1 000 000   | mega  |
## <a name="t-nww"></a>NWW i NWD
### Co oznaczają te skróty?
> NWW to inaczej **Najmniejsza wspólna wielokrotność**
> NWD to inaczej **Najmniejszy wspólny dzielnik**
// TODO: Napisac ten artykul + Rozkladanie na czynniki pierwsze
## <a name="t-div"></a>Cechy podzielności liczb
*Nie jest to temat potrzebny na egzamin, jednakże bardzo usprawnia prace*<br>
_**Uwaga:** w tym temacie będziemy mówić tylko o [liczbach całkowitych](#REFRENCE)_
### Co to są Cechy Podzielności?
Cechy podzielności to zbiór zasad, dzięki którym możemy szybko sprawdzić przez jakie cyfry dzieli się jakaś duża liczba.
### Cechy podzielności dla cyfr 1-10
- 1 - Każda liczba dzieli się przez 1
- 2 - Ostatnia cyfra liczby to 0, 2, 4, 6 lub 8
- 3 - Suma wszystkich cyfr liczby jest podzielna przez 3
- 4 - Ostatnie dwie cyfry dzielą się przez 4
- 5 - Ostatnia cyfra liczby to 0 lub 5
- 6 - Liczba dzieli się przez 2 i 3 (patrz: Cechy Podzielności dla 2 i 3)
- 7 - Nie ma cechy podzielności dla 7. Możemy za to podzielić liczbę na dwie mniejsze, u których łatwiej to sprawdzić
- 8 - Ostatnie 3 cyfry są podzielne przez 8
- 9 - Suma wszystkich cyfr liczby jest podzielna przez 9
- 10 - Ostatnia cyfra liczby to 0
### Przykład - Wykorzystanie cech podzielności
Zobacz, jak możemy sprawdzić przez jakie cyfry dzieli się liczba <ins>749</ins> wykorzystując cechy podzielności:
```
1: wszystkie liczby są podzielne // PODZIELNA
2: 9 ≠ 0 lub 2 lub 4 lub 6 lub 8 // NIE PODZIELNA
3: 7 + 4 + 9 = 20 | 20 nie jest podzielne przez 3 // NIE PODZIELNA
4: 49 nie dzieli się przez 4 // NIE PODZIELNA
5: 9 ≠ 0 lub 5 // NIE PODZIELNA
6: 749 nie dzieli się ani przez 2, ani przez 3 // NIE PODZIELNA
7: 749 = 700 + 49 | 49 : 7 | 700 : 7 // PODZIELNA
8: Jeśli nie jest podzielna przez 2 to także nie jest podzielna przez rzadną inną liczbę parzystą // NIE PODZIELNA
9: Jeśli nie jest podzielna przez 3 to także nie jest podzielna przez 9 // NIE PODZIELNA
10: 9 ≠ 0 // NIE PODZIELNA
```
Nie trudno zauważyć, że tym sposobem jest to o wiele szybsze i mniej męczące, niż manualne dzielenie tej liczby 10 razy
## Kategoryzacja liczb
W tym temacie poznasz trochę ważnych pojęć dotyczących różnych zbiorów liczb
Używa sie ich, aby łatwiej mówić o grupach liczb oraz żeby utrudnić wymagające już zadanie w celu zniszczeniu uczniowi resztek pewności siebie
### Liczby całkowite
Liczby całkowite to liczby, które <ins>nie są ułamkami</ins> (zob. [ułamki](#REFRENCE), np. 1, -1, 2, -2, 3, -3).
### Liczby naturalne
Liczby naturalne to <ins>liczby całkowite</ins>, które są <ins>większe od 0</ins> (np. 1, 2, 5, 17, 1024).
### Liczby parzyste
Liczby parzyste to liczby całkowite, <ins>podzielne przez 2 bez reszty</ins> (np. 2, 8, 18, 150).
### Liczby nieparzyste
Liczby nieparzyste to liczby całkowite, <ins>nie podzielne przez 2</ins> (np. 1, 3, 9, 13, 149).
### Liczby ujemne
Liczby ujemne to liczby, które są <ins>mniejsze od 0</ins> i oznaczamy je wstawiając znak '-' przed daną wartością (np. -2, -17, -361238123)
### Liczby pierwsze
Liczby pierwsze to liczby, które są <ins>mają tylko 2 dzielniki</ins> (dzielą się przez 1 i samą siebie, np. 2, 3, 5, 7, 11, 17, 71).<br>
_**Uwaga:** liczby 0 i 1 <ins>nie należą do liczb pierwszych</ins> (0 nie dzieli się przez nic, a 1 dzieli się tylko przez 1)_
## Wyrażenia algebraiczne
// TODO: Napisac ten artykul
## Równania
// TODO: Napisac ten artykul
## Ułamki
// TODO: Napisac ten artykul
## Liczby rzymskie
// TODO: Napisac ten artykul
## Potęgi i pierwiastki
// TODO: Napisac ten artykul
## Kolejność wykonywania działań
// TODO: Napisac ten artykul
## Geometria - Figury
// TODO: Napisac ten artykul
## Geometria - Obwody figur
// TODO: Napisac ten artykul
## Geometria - Pola figur
// TODO: Napisac ten artykul
## Geometria - Figury przestrzenne i ich objętość
// TODO: Napisac ten artykul
## Geometria - Trójkąty i twierdzenie pitagorasa
### Co to jest trójkąt
Trójkąt to figura geometryczna która ma <ins>**3 boki 3 kąty oraz 3 wierzchołki**</ins>
### suma kątów w trójkącie
suma kątów w trójkącie wynosi <ins>**180°**</ins>
### Rodzaje trójkątów ze względu na boki
Równoboczny - wszystkie boki są równe oraz każdy kąt ma 60°<br>
Równoramienny - Dwa boki są równe oraz Dwa katy mają taką samą wartość w stopniach<br>
Różnoboczny - Wszystkie boki są różne tak samo z kątami<br>
### Rodzaje trójkątów ze względu na kąty
Ostrokątny - Wszystkie kąty są mniejsze niż 90° np. 50°, 60°, 70°<br>
Prostokątny - Ma jeden kąt 90° Dwa pozostałe razem dają 90°<br>
Rozwartokątny - Ma jeden kąt większy niż 90° Dwa pozostałe są ostre<br>
### Ważne pojęcia
Wysokość – odcinek opuszczony z wierzchołka prostopadle na bok lub jego przedłużenie.<br>
Środkowa – odcinek łączący wierzchołek z środkiem przeciwległego boku.<br>
Dwusieczna – odcinek, który dzieli kąt na pół.
### Trójkąt 45° 45° 90°
Utworzyć taki trójkąt można za pomocą przekątnej w kwadracie. Podstawa tego trójkąta (znajduje się przy 2 kątach wynoszących 45°) ma długość <ins>**a√2**</ins> ramiona mają po <ins>**a**</ins> (jest to trójkąt równoramienny ponieważ ma 2 takie same kąty)
### Trójkąt 30° 60° 90°
Wysokość - <ins>**a√3⁄2**</ins> podstawa - <ins>**1/2a**</ins> przeciwprostokątna - <ins>**a**</ins>
## Działania pisemne
// TODO: Napisac ten artykul
## Średnia arytmetyczna
// TODO: Napisac ten artykul
