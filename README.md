# Scenatiusze do gry SimRail

Witaj, w repozytorium znajdują się nowe misje do gry SimRail - wykonane przez: **patwrobel**.<br />
Każdy scenariusz zawiera liczny ruchem AI, wybór pogody i pory roku oraz godziny rozpoczęcia.<br />
Dodatkowo każdą misję możemy rozpocząć od wybranego checkpoint'u co pozwala na wznawianie przerwanej gry.

# Aktualna wersja
Wersja: 1.1.6<br />
Data aktualizacji: 2025.06.19

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
   - ★ Uruchom scenariusz z domyślną godziną ★
   - Lista godzin co 2h od 3:00 do 23:00

## Misje
- [Misja 1 - Strzemieszyce 3xEN57](#misja-1---strzemieszyce-3xen57)
- [Misja 2 - Łazy Cargo](#misja-2---łazy-cargo)
- [Misja 3 - Sprinter KM - RE1](#misja-3---sprinter-km---re1)

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
- Zdjęcia:
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
    - Dąbrowa G. Wsch. (Wyjazd)<br />
    Luzakiem dotarliśmy już do Dąbrowa Górniczej Wschodniej i zmieniliśmy kabinę. Udajemy się dalej do Bukowna po uszkodzony skład beczek.
    - Bukowno (Wyjazd)<br />
    Jesteśmy już po manewrach w Bukownie - ruszamy do Łaz składem z beczkami.
    - D.G. Strzemieszyce (Wyjazd)<br />
    Kontynuujemy jazdę składem z beczkami ruszając ze stacji Dąbrowa Górnicza Strzemieszyce.
    - Sosnowiec Pł. (Wyjazd)<br />
    Kontynuujemy jazdę składem z beczkami ruszając ze stacji Sosnowiec Południowy.
- Opis:<br />
Rozpoczynamy na peronie stacji Sosnowiec Główny - tuż po wyjściu z pociągu osobowego. Udajemy się pod semafor wyjazdowy H5 (w kierunku Będzina) - tam za chwilę podjedzie towarowy, który przejmiemy. Prowadzimy pociąg kontenerowy z dodatkowymi 2xEU07 na przodzie do odstawienia w Łazach. Po dotarciu do Łaz wykonujemy liczne manewry przez ŁB i ŁA celem odstawienia lokomotyw w odpowiednie miejsce. Po ich zakończeniu udajemy się luzakiem do Bukowna po uszkodzony skład towarowy. Trasa jest poprowadzona przez Przemiarki i Dąbrowę Górniczą Wschodnią, gdzie zmieniamy kabinę. Po dotarciu do Bukowna wykonujemy manewry i łączymy się ze składem beczek. Prowadzimy pociąg towarowy z Bukowna do Łaz.
- Zdjęcia:
   ![Photo1](Photos/Misja%202/Photo1.jpg)
   ![Photo4](Photos/Misja%202/Photo4.jpg)
   ![Photo3](Photos/Misja%202/Photo3.jpg)
   ![Photo7](Photos/Misja%202/Photo7.jpg)
   ![Photo8](Photos/Misja%202/Photo8.jpg)

## Misja 3 - Sprinter KM - RE1
- Tabor: 2xEN76 - Elf
- Kanał startowy: 2
- Opis:<br />
Rozpoczynamy na peronie p.o. Warszawa Powiśle. Przejmujemy pociąg 91836 relacji Grodzisk Mazowiecki - Warszawa Wschodnia (1xELF). Po dojechaniu do stacji Warszawa Wschodnia zjeżdżamy w tory postojowe i łączymy się z drugim EZT. Po połączeniu składu jedziemy jako pociąg przyśpieszony RE1 19152 jednej z 3 wybranych relacji:<br/>
**UWAGA: Przystanki Powiśle i Stadion nie są obsługiwane więc nie otwieramy drzwi**
- Trasy:
    - W-wa Wschodnia - **Grodzisk Mazowiecki** - W-wa Wschodnia
    - W-wa Wschodnia - **Żyrardów** - W-wa Wschodnia
    - W-wa Wschodnia - **Skierniewice** - W-wa Wschodnia
- **W-wa Wschodnia - Grodzisk Mazowiecki - W-wa Wschodnia:**
    - Przebieg:<br />
      -  Do stacji Pruszków:<br />
         pociąg przyśpieszony z zatrzymaniem: Wschodnia / Centralna / Zachodnia<br />
      -  Od stacji Pruszków:<br />
         zatrzymanie na każdym przystanku osobowym
    - Etapy:
      -  Warszawa Powiśle (Początek)
      -  Warszawa Wschodnia (Tor postojowy)
      -  Warszawa Zachodnia (Wyjazd)
      -  Grodzisk Mazowiecki (Tor postojowy)
      -  Józefinów (Pod wjazdem)
- **W-wa Wschodnia - Żyrardów - W-wa Wschodnia:**
    - Przebieg:<br />
      -  Do stacji Grodzisk Mazowiecki:<br />
         pociąg przyśpieszony z zatrzymaniem: Wschodnia / Centralna / Zachodnia<br />
      -  Od stacji Grodzisk Mazowiecki:<br />
         zatrzymanie na każdym przystanku osobowym
    - Etapy:
      -  Warszawa Powiśle (Początek)
      -  Warszawa Wschodnia (Tor postojowy)
      -  Warszawa Zachodnia (Wyjazd)
      -  Grodzisk Mazowiecki (Wjazd od Warszawy)
      -  Żyrardów (Tor postojowy)
      -  Józefinów (Pod wjazdem)
- **W-wa Wschodnia - Skierniewice - W-wa Wschodnia:**
    - Przebieg:<br />
      -  Do stacji Grodzisk Mazowiecki:<br />
         pociąg przyśpieszony z zatrzymaniem: Wschodnia / Centralna / Zachodnia<br />
      -  Od stacji Grodzisk Mazowiecki:<br />
         zatrzymanie na każdym przystanku osobowym
    - Etapy:
      -  Warszawa Powiśle (Początek)
      -  Warszawa Wschodnia (Tor postojowy)
      -  Warszawa Zachodnia (Wyjazd)
      -  Grodzisk Mazowiecki (Wjazd od Warszawy)
      -  Żyrardów (Wjazd od Warszawy)
      -  Skierniewice (Tor postojowy)
      -  Żyrardów (Wjazd od Skierniewic)
      -  Józefinów (Pod wjazdem)
- **Manewry:**
    - Na każdej stacji docelowej (Grodzisk Maz. / Żyrardów / Skierniewice) gracz po zjechaniu w tory postojowe będzie zapytany czy chce wykonać dodatkowe prace na stacji. Dla każdej z tych 3 stacji jest różne zadanie do wykonania.
    - Pytanie o manewry jest zawsze - niezależnie od konfiguracji opcji "Proszę wybrać konfigurację wydarzeń losowych" (opis niżej)
    - Manewry na st. Grodzisk Mazowiecki determinują inny wyjazd ze stacji
- Dodatkowe opcje:
    - W scenariuszu jest dodatkowe pytanie:<br />
      **Proszę wybrać konfigurację wydarzeń losowych**
    - Opis<br />
      W misji zaszyte są "większe" zdarzenia losowe - gracz może mieć wpływ na ich przebieg. Chodzi tu o zamknięcie toru, jazdę lewym torem lub dodatkowe manewry. Dlatego na początku misji gracz zostanie poproszony o wybranie jednej z 3 opcji:
    - Możliwe opcje do wyboru:
      -  ★ Wydarzenia losowane zgodnie ze scenariuszem ★<br />
         Zdarzenia losują się zgodnie z przyjętym prawdopodobieństwem.
      -  Jazda bez wydarzeń losowych<br />
         Brak wydarzeń - czysta jazda bez większysz wydarzeń.
      -  Gracz decyduje przy kazdym zdarzeniu<br />
         Przy każdym zdarzeniu gracz zostanie poproszony o wskazanie, który scenariusz wybiera dla najbliższej sytuacji.<br />
    - Niezależnie od tych "większych" wydarzeń po drodze są losowane mniejsze zdarzenia - jak brak wjazdu / wyjazdu, inny tor przejazdu na stacji, czy nie działający TOP.
- **Łączenie ELFów:**
    - Podjeżdżamy i uderzamy z niską prędkością (ok 3km/h) o sprzęg drugiego EZT
    - Wychodzimy z kabiny i podchodzimy do pierwszych drzwi drugiego EZT
    - Włączamy baterię (zielona klapka przy drzwiach na zewnątrz)
    - Wchodzimy do kabiny i przełączamy aktywację kabiny na:<br />
      Aktywacja ostatniej kabiny w trakcji wilokrotnej
    - Wracamy do pierwszego EZT i przełączamy aktywację kabiny na:<br />
      Aktywacja pierwszej kabiny w trakcji wilokrotnej
    - Odhamowujemy (Odblokowanie przewodu głównego)
    - UWAGA: ważne aby w drugiej EZT zadajnik jazdy był na środku<br />
      (nie może być w pozycji hamowania)
- Zdjęcia:
![Photo1](Photos/Misja%203/Photo1.jpg)
![Photo2](Photos/Misja%203/Photo2.jpg)
![Photo3](Photos/Misja%203/Photo3.jpg)
![Photo4](Photos/Misja%203/Photo4.jpg)
![Photo5](Photos/Misja%203/Photo5.jpg)