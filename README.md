# Scenatiusze do gry SimRail

Witaj, w repozytorium znajdują się nowe misje do gry SimRail - wykonane przez: **patwrobel**.<br />
Każdy scenariusz zawiera liczny ruchem AI, wybór pogody i pory roku oraz godziny rozpoczęcia.<br />
Dodatkowo każdą misję możemy rozpocząć od wybranego checkpoint'u co pozwala na wznawianie przerwanej gry.

# Aktualna wersja
Wersja: 1.0.3<br />
Data aktualizacji: 2025.03.18 09:15

## Instalacja
Należy pobrać spakowany folder o nazwie **44_patwrobel.7z** i wypakować go do głównego folderu scenariuszy gry SimRail:

`..\SteamLibrary\steamapps\common\SimRail\SimRail_Data\StreamingAssets\Sceneries\`

## Pobierz
Najnowsza wersja dostępna pod adresem: [44_patwrobel.7z](https://github.com/patwrobel/SimRail/releases/latest/download/44_patwrobel.7z)

## Etap startowy scenariusza
Każda misja została podzielona na etapy, aby była możliwość grania fragmentami - dokończenia gry od pewnego miejsca. Po każdym uruchomieniu scenariusza użytkownik zostanie poproszony o wybór etapu - są one ułożone po kolei. Możemy zacząć grę od dowolnego etapu i grać do końca.

## Symulacja
Scenariusze zawierają liczny ruch AI oraz zdarzenia losowe (w tym wygaszenia semaforów, uszkodzenia przejazdów, sygnały zastęcze, jazda lewym torem, itp.)

## Pogoda i pora dnia
Każdorazowo gra prosi na starcie o określenie pogody (pora roku) oraz pory dnia.
Mamy do dyspozycji:
- Pogowa (poda roku):
   - Deszczowa (Wiosna)
   - Słoneczna (Lato)
   - Mglista (Jesień)
   - Śnieżna (Zima)
- Pora dnia:
   - Rano (07:00)
   - Popołudniu (12:00)
   - Wieczorem (18:00)
   - Noc (22:00)

## Misje
- [Misja 1 - Strzemieszyce 3xEN57](#misja-1---strzemieszyce-3xen57)
- [Misja 2 - Łazy Cargo](#misja-2---łazy-cargo)

## Misja 1 - Strzemieszyce 3xEN57
- Tabor: EN57
- Kanał startowy: 2
- Etapy:
    - Dąbrowa Górnicza Ząbkowice (Początek)<br />
    Start misji. Manewry na stacji Dąbrowa Górnicza Ząbkowice, aby skierować się w stronę Strzemieszyc.
    - Dąbrowa Górnicza Ząbkowice (Wyjazd)<br />
    Po manewrach gotowy do wyjazdu w kierunku Huty
    - Dąbrowa Górnicza Strzemieszyce (Wyjazd)<br />
    Po połączeniu z uszkodzonym składem na stacji Dąbrowa Górnicza Strzemieszyce. Jazda w 3xEN57 do Katowic jako osobowy 24901.
- Opis:<br />
Rozpoczynamy rozgrywkę na stacji Dąbrowa Górnicza Ząbkowice pod nastawnią DZB. Udajemy się pod skład 2xEN57, który widzimy na wprost i **rozłączamy jednostki**. Następnie uruchamiamy tylko pierwszy EZT w kierunku Łaz i zgłaszamy się na radiu (kanał 2). Wykonujemy manewry o które prosi nas dyżurny. Po udanych manewrach ruszamy jako pociąg 115232 do Strzemieszyc celem wsparcia uszkodzonego pociągu osobowego. Po dotarciu do Strzemieszyc wykonujemy manewry pod skład 2xEN57 i łączymy go w 3xEN57. Po połączeniu jedziemy jako osobowy 24901 do Katowic zatrzymując się na każdym przystanku.
- Łączenie w skład 3xEN57:<br />
   - Dojeżdżamy i dobijamy sprzęgi
   - Wyłączamy kabinę (UWAGA: zostawiamy włączone radio)
   - Podchodzimy do sprzęgu -> prawym -> Upewniamy się że wszystko jest połączone
   - Wchodzimy do kabiny składu II (środkowy) zaraz przy sprzęgu
   - Zwalniamy hamulec ręczny
   - Przechodzimy po składzie na koniec tego EZT po drodze włączamy baterie i odblokowujemy przekaźnik różnicowy
   - Wychodzimy tylnym wyjściem ze składu
   - Wchodzimy do kabiny składu III (ostatni)
   - Zwalniamy hamulec ręczny
   - Przechodzimy po składzie na koniec tego EZT po drodze włączamy baterie i odblokowujemy przekaźnik różnicowy
   - Wchodzimy do kabiny (koniec pociągu) i zapalamy czerwone światła
   - Wychodzimy ze składu i sprawdzamy czy świecą czerwone lampki
   - Przechodzimy po peronie na sam początek składu (od strony Kazimierza)
   - Uruchamiamy kabinę
   - Wywołujemy dyżurnego
   - Cofamy za semafor V
   - **UWAGA:<br />jeżeli nie będzie można cofnąć (skład odhamowany, ale nie jedzie) wówczas podchodzimy do sprzęgu między I a II (tym co sami go łączyliśmy) i klikamy prawym "Rozłącz przewody sterujące" następnie znów "Połącz przewody sterujące" i wracamy do kabiny**
   ![Photo1](Photos/Misja%201/Photo1.jpg)
   ![Photo3](Photos/Misja%201/Photo3.jpg)
   ![Photo4](Photos/Misja%201/Photo4.jpg)

## Misja 2 - Łazy Cargo
- Tabor: ET22 / EU07 / Dragon / Traxx
- Kanał startowy: 2
- Etapy:
    - Sosnowiec Gł. (Początek)<br />
    Start misji. Przejmujemy skład towarowy i odprowadzamy go do stacji Łazy.
    - Łazy (Manewry)<br />
    Skład dostarczyliśmy już do Łaz i rozpoczynamy manewry zgodnie z instrukcjami dyżurnego.
    - Łazy (Wyjazd)<br />
    Jesteśmy już po manewrach i rozpoczynamy służbowy kurs luzakiem do Bukowna przez Przemiarki i Dąbrowę Górniczą Wschodnią (zmiana kabiny). W Bukownie wykonujemy manewry pod uszkodzony skład.
    - Bukowno (Wyjazd)<br />
    Mamy już połączony skład i ruszamy do Łaz z beczkami.
    - D.G. Strzemieszyce (Wyjazd)<br />
    Kontynuujemy jazdę składem z beczkami
    - Sosnowiec Pł. (Wyjazd)<br />
    Kontynuujemy jazdę składem z beczkami
- Opis:<br />
Rozpoczynamy na peronie stacji Sosnowiec Główny - tuż po wyjściu z pociągu osobowego. Udajemy się pod semafor wyjazdowy H5 (w kierunku Będzina) - tam za chwilę podjedzie towarowy, który przejmiemy. Prowadzimy pociąg kontenerowy z dodatkowymi 2xEU07 na przodzie do odstawienia w Łazach. Po dotarciu do Łaz wykonujemy liczne manewry przez ŁB i ŁA celem odstawienia lokomotyw w odpowiednie miejsce. Po ich zakończeniu udajemy się luzakiem do Bukowna po uszkodzony skład towarowy. Trasa jest poprowadzona przez Przemiarki i Dąbrowę Górniczą Wschodnią, gdzie zmieniamy kabinę. Po dotarciu do Bukowna wykonujemy manewry i łączymy się ze składem beczek. Prowadzimy pociąg towarowy z Bukowna do Łaz.
   ![Photo1](Photos/Misja%202/Photo1.jpg)
   ![Photo4](Photos/Misja%202/Photo4.jpg)
   ![Photo3](Photos/Misja%202/Photo3.jpg)
   ![Photo7](Photos/Misja%202/Photo7.jpg)
   ![Photo8](Photos/Misja%202/Photo8.jpg)
