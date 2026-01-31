# Scenariusze do gry SimRail

Witaj, w repozytorium znajdują się nowe misje do gry SimRail - wykonane przez: **patwrobel**.<br />
Każdy scenariusz zawiera liczny ruchem AI, wybór pogody i pory roku oraz godziny rozpoczęcia.<br />
Dodatkowo każdą misję możemy rozpocząć od wybranego checkpoint'u co pozwala na wznawianie przerwanej gry.

# Aktualna wersja
Wersja: 1.5.11<br />
Data aktualizacji: 2026.01.31

## Instalacja - WorkShop (zalecane)
Wchodzimy na adres workshop: **[Patwrobel Scenerios](https://steamcommunity.com/sharedfiles/filedetails/?id=3651816992)** i klikamy **Zasubskrybuj**<br />
Wszystkie aktualizacje będą instalowały się automatycznie

## Instalacja - ręczna
Należy pobrać plik z adresu: **[44_patwrobel.7z](https://github.com/patwrobel/SimRail/releases/latest/download/44_patwrobel.7z)** i wypakować go do głównego folderu scenariuszy gry SimRail (aktualizacje trzeba wgrywać ręcznie):

`..\SteamLibrary\steamapps\common\SimRail\SimRail_Data\StreamingAssets\Sceneries\`

## Etap startowy scenariusza
Każda misja została podzielona na etapy, aby była możliwość grania fragmentami - dokończenia gry od pewnego miejsca. Po każdym uruchomieniu scenariusza użytkownik zostanie poproszony o wybór etapu - są one ułożone po kolei. Możemy zacząć grę od dowolnego etapu i grać do końca.

## Symulacja
Scenariusze zawierają liczny ruch AI oraz zdarzenia losowe (w tym wygaszenia semaforów, uszkodzenia przejazdów, sygnały zastęcze, jazda lewym torem, itp.)

## Pogoda i pora dnia
Pogoda jest dynamiczna i podlega pewnym zmianom podczas grania - mechanizm został przeniesiony z orginalnych scenariuszy SimRail. Każdorazowo na starcie gra prosi o określenie pory roku, pogody oraz pory dnia.
Mamy do dyspozycji następujące opcje:
- Pora roku:
   - Wiosna
   - Lato
   - Jesień
   - Zima
- Pogoda:
   - Słonecznie
   - Mgliście
   - Deszczowo
   - Burzowo
   - Śnieżnie
- Pora dnia:
   - ★ Uruchom scenariusz z domyślną godziną ★
   - ręczny wybór dowolnej godziny

## Misje
- [Misja 1: Strzemieszyce 3xEN57](#misja-1-strzemieszyce-3xen57)
- [Misja 2: Łazy Cargo](#misja-2-łazy-cargo)
- [Misja 3: Sprinter KM - RE1](#misja-3-sprinter-km---re1)
- [Misja 4: Cargo: Kraków - Płock](#misja-4-cargo-kraków---płock)
- [Misja 5: Osobowy: Łódź - Warszawa](#misja-5-osobowy-łódź---warszawa)

## Misja 1: Strzemieszyce 3xEN57
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

## Misja 2: Łazy Cargo
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

## Misja 3: Sprinter KM - RE1
- Tabor: 2xEN76 - Elf  /  2xEN57
- Kanał startowy: 2
- Opis:<br />
Rozpoczynamy na peronie p.o. Warszawa Powiśle. Przejmujemy pociąg 91836 relacji Grodzisk Mazowiecki - Warszawa Wschodnia (1xEZT). Po dojechaniu do stacji Warszawa Wschodnia zjeżdżamy w tory postojowe i łączymy się z drugim EZT. Po połączeniu składu jedziemy jako pociąg przyśpieszony RE1 19152 jednej z 3 wybranych relacji:<br/>
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
      -  Gracz decyduje przy każdym zdarzeniu<br />
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

## Misja 4: Cargo: Kraków - Płock
- Tabor: ET22 / EU07 / Dragon / Traxx / Škoda CD163
- Kanał startowy: 1
- Trasa: Kraków Główny Towarowy - Płock Trzepowo przez:
    - Kozłów<br />
    - Włoszczowa<br />
    - Idzikowice<br />
    - Koluszki<br />
    - Skierniewice<br />
    - Kutno
- Opis:<br />
Naszym zadaniem na dziś jest dostarczyć próżny skład beczek ze stacji Kraków Główny Towarowy do Płock Trzepowo. Rozpoczynamy pracę na stacji Kraków Główny Towarowy (KGA), gdzie w tle stoi nasza wygaszona lokomotywa. Uruchamiamy i zgłaszamy się do wykonania manewrów pod skład beczek na stacji. Po wykonaniu próby ruszamy w długa i malowniczą trasę biegnącą linią 8 aż do Kozłowa gdzie kierujemy się na CMK. Po dojechaniu do stacji Idzikowice zostaniemy skierowani łącznicą na linię 22 do Tomaszowa Mazowieckiego, a następnie liniami 25 i 534 trafiamy do Koluszek. Tu mamy do wyboru dwa scenariusze:
    - Kontynuować dalej jazdę z tym składem<br />
    Po dojechaniu do Skierniewic udajemy się łącznicą w kierunku Łowicza.
    - Wykonać dodatkowe manewry i zabrać dodatkowe 5 wagonów do st. Skierniewice<br />
    Po wykonaniu manewrów i uformowaniu nowego składu udajemy się do Skierniewic, gdzie wykonujemy manewry i odstawiamy dodatkowe wagony do składu w kierunku Warszawy. Sami z beczkami wracamy na szlak w kierunku Łowicza.
- Dodatkowe elementy w scenariuszu:
    - Na CKM sa dwa długie odcinki, które możemy pominąć - skład przeskoczy do wjazdu do najbliższej stacji (za każdym razem jesteśmy pytani o decyzję). Dotyczy odcinków:
      - Włoszczowa Północ - Olszamowice
      - Olszamowice - Pilichowice
    - W grze brakuje odcinka Radzice - Mikołajów. Po dojechaniu do Radzic gra automatycznie przerzuca nas pod wjazd w Mikołajowie
- Etapy:
    - ★ Kraków Gł. Tow. (Początek) ★<br />
    - Kraków Gł. Tow. (Wyjazd)<br />
    - Kraków Gł. Tow. (Wyjazd)<br />
    - Niedźwiedź (Wjazd)<br />
    - Kozłów (Wjazd)<br />
    - Starzyny (Wjazd)<br />
    - Włoszczowa Północ (Wyjazd)<br />
    - Olszamowice (Wjazd)<br />
    - Pilichowice (Wjazd)<br />
    - Opoczno Południe (Wjazd)<br />
    - Idzikowice (Wjazd)<br />
    - Mikołajów (Wjazd)<br />
    - Koluszki (Wjazd)<br />
    - Koluszki (Wyjazd)<br />
    - Skierniewice (Wjazd)<br />
- Zdjęcia:
![Photo1](Photos/Misja%204/Photo1.png)
![Photo2](Photos/Misja%204/Photo2.png)
![Photo3](Photos/Misja%204/Photo3.jpg)
![Photo4](Photos/Misja%204/Photo4.jpg)
![Photo5](Photos/Misja%204/Photo5.jpg)
![Photo6](Photos/Misja%204/Photo6.jpg)

## Misja 5: Osobowy: Łódź - Warszawa
- Tabor: EN57 / EN71 / ELF / EU07 / EP07 / EP08 / ET22 / TRAXX / DRAGON / PENDOLINO
- Kanał startowy: 7
    - Manewry ŁKA (Widzew): 9
    - KM: 2
- <b>UWAGA - DLC:</b>
    - Do prawidłowego działania wymagane jest DLC Łódź 1
    - Jeżeli gracz wybierze etap z Grodziska Maz. wówczas można bez DLC
- <span style="color:blue; font-weight: bold">Dostępne trasy</span> (orientacyjny czas przejazdu):
    - 1.5h&emsp; [ŁKA] Łódź Fabryczna - Warszawa (Sprinter)
    - 1.5h&emsp; [ŁKA] Łódź Fabryczna - Warszawa (Przyśp.)
    - 2.5h&emsp; [ŁKA] Łódź Fabryczna - Warszawa (Osobowy)
    - 1.5h&emsp; &ensp; [IC] Łódź Fabryczna - Warszawa (InterCity)
    - 1.5h&emsp; &ensp;[PR] Łódź Fabryczna - Warszawa (InterRegio)
    - 1.5h&emsp; &ensp;[PR] Łódź Kaliska - Warszawa (InterRegio)
    - 2.5h&emsp; &ensp;[PR] Łódź Kaliska - Warszawa (Regio)
    - 1.0h&emsp; &nbsp;[KM] Skierniewice - Warszawa (Sprinter)
    - 1.0h&emsp; &nbsp;[KM] Skierniewice - Warszawa (RE)
    - 1.5h&emsp; &nbsp;[KM] Skierniewice - Warszawa (Osobowy)
    - 1.0h&emsp; &nbsp;[KM] Żyrardów - Warszawa (Osobowy)
    - 0.8h&emsp; &nbsp;[KM] Grodzisk Maz. - Warszawa (Osobowy)
- Zatrzymania:
    - ŁKA [Sprinter]:&emsp;KO, Rg, Ske, Zr, WZ, WC, WW
    - ŁKA [Przyś.]:&emsp;&emsp;KO, Rg, Pl, Ske, Zr, Gr, Pr, WZ, WC, WW
    - ŁKA [Os.]:&emsp;&emsp;&emsp;wszystkie przystanki
    - InterCity:&emsp;&emsp;&emsp; KO, Ske, Zy, WZ, WC, WW
    - PR [InterRegio]:&ensp;LA, KO, LR, Ske, SR, Zy, Gr, WZ, WC, WW
    - PR [Regio]:&emsp;&emsp;&ensp;wszystkie przystanki     
    - KM [Sprinter]:&emsp; Ske, Zy, Gr, WZ, WC, WW        
    - KM [RE]:&emsp;&emsp;&emsp;&ensp;do Gr jako os. dalej: WZ, WC, WW
    - KM [Os.]:&emsp;&emsp;&emsp; wszystkie przystanki  
- Skróty stacji:
    - LA = Łódź Andrzejów
    - KO = Koluszki
    - Rg = Rogów
    - LR = Lipce Reymontowskie
    - Pl = Płyćwia
    - Ske = Skierniewice
    - SR = Skierniewice Rawka
    - Zr = Żyrardów
    - Gr = Grodziska Mazowiecki
    - Pr = Pruszków
    - WZ = Warszawa Zachodnia
    - WC = Warszawa Cententralna
    - WW = Warszawa Wschodnia
- Opis:<br />
   Trasa scenariusza przebiega na odcinku Łódź Widzew - Koluszki - Skierniewice - Żyrardów - Grodzisk Maz. - Warszawa. Gracz po uruchomieniu scenariusza ma do dyspozycji wybór dostepnych tras. W zależności od jego wyboru będzię miał do dyspozycji inne pojazdy, inny wybór dostępnych etapów oraz start misji może się różnić. Do każdej trasy jest przygotowany inny zakres postojów handlowych, inne czasy przejazdu - rozróżnione na wolniejsze składy (do 120km/h) oraz szybsze (powyżej 120 km/h).
   <br />
- <span style="color:red;">Linia podmiejska [tunel średnicowy]</span>:<br />
   Wszystkie pociągi osobowe jadą linią podmiejską - dojeżdzają do p.o. Warszawa Ochota i po wjechaniu do tunelu gracz zostaje przeniesiony na p.o. Warszawa Powiśle.<br />
   Przystanki Powiśle i Stadion jeszcze nie obsługują otwierania drzwi, więc gracz jest poproszony o zatrzymanie i odczekanie 15 sek. (<b>bez otwierania drzwi</b>) - następnie jest komunikat od kierownika i może jechać dalej.

- <b>ŁKA - Łódzka Kolej Aglomeracyjna (dodatkowe manewry):</b><br />
   Dostępne składy: EN57 / ELF.<br />
   Jeżeli wybierzemy etap "Początek" wówczas rozpoczniemy scenariusz na peronie stacji Łódź Widzew. Naszym pierwszym zadaniem będzie uformowanie składu dla pociągu 97710 i wyprawienie go w peron, gdzie przejmie go od nas inny maszynista. Skład do manewrów jest zawsze odwrotny do wybranego przez gracza (jeżeli wybrał EN57 to manerwy są na ELFie i  odwrotnie). Jeżeli gracz wybierze podwójny EZT wówczas manewry są dłuższe z łączeniem składu w dwu-skład z dwóch róznych torów. Po wykonanych manewrach wracamy na bazę ŁKA i przygotowujemy swój skład (jeżeli podwójny to musimy połączyć z innego toru). Po wykonanych manewrach wyjeżdżamy na stację Łódź Widzew i jedziemy do stacji Łódź Fabryczna (bez stacji - jeszcze nie gotowa w SimRail). Po wyjechaniu ze stacji pojawiamy się na wjeździe do Widzewa jako pociąg 1935 zgodnie z wybraną wersją i prowadzimy skład do samej Warszawy. Po drodze czekają nas licne zdarzenia losowe, ruch kolizyjny, przepuszczanie szybszych pociągów czy rozkazy pisemne i awarie sygnalizacji. Wszystkie zdarzenia są losowe i każdy przejazd jest inny. Po dojechaniu do stacji Warszawa Wschodnia wykonujemy manewry w tory postojowe stacji i zakańczamy scenariusz wyłącząc skład i wychodząc na zewnątrz (UWAGA: musi być ciśnienie w przewodzie głównym poniżej 4.7)
<br /><br />
- <b>IC - InterCity (dodatkowe podstawienie z Olechowa):</b><br />
   Dostępne składy: EU07 / EP07 / EP08 / TRAXX / DRAGON / ET22 / PENDOLINO / Škoda CD163<br />
   Dostępna ilość wagonów dla lokomotyw: 9 / 7 / 5<br />
   Jeżeli wybierzemy etap "Początek" wówczas rozpoczynamy misję na pociągu służbowym 116002 relacji Łódź Olechów - Łódź Fabryczna. Skład będzie stał pod semaforem wyjazdowym ze stacji Łódź Olechów (p.o. Łódź Andrzejów Szosa). Przejeżdzamy krótki odcinek aż za stację Łódź Widzew i po chwili pojawiamy się na wjeździe do Łódź Widzew od strony Fabrycznej. Prowadzimy pociąg 1935 zatrzymując się na kilku postojach handlowych (Koluszki, Skierniewice, Żyrardów i Warszawa). Podczas podróży natrafimy na liczne zmiany torów, blokowanie ruchu przez pociągi osobowe czy towarowe, wyprzedzania na stacjach. Pojawią się rozkazy pisemne i problemy z sygnalizacją. Wszystkie zdarzenia są losowe i każdy przejazd jest inny. Po dojechaniu do stacji Warszawa Wschodnia zjeżdzamy na stację postojową Warszawa Grochów, gdzie nastąpi zakończenie scenariusza.
<br /><br />
- <b>PR - PolRegio (dodatkowa trasa z Łódź Dąbrowa):</b><br />
   Dostępne składy IR (InterRegio): EU07 / EP07 / EP08 / ET22 / TRAXX / DRAGON / Škoda CD163 / ELF / EN57 / EN71<br />
   Dostępne składy R (Regio): EN57 / EN71 / ELF / EU07 / EP07 / EP08 / ET22 / TRAXX / DRAGON / Škoda CD163<br />
   Dostępna ilość wagonów dla lokomotyw: 3 / 5 / 7 / 9<br />
   Jeżeli wybierzemy etap "Początek" wówczas prowadzimy skła z Łódzi Kaliskiej do Warszawy i rozpoczynamy misję na p.o. Łódź Dąbrowa (2 przystanki przed Łódź Widzew). Po dojechaniu do stacji Łódź Widzew prowadzimy skład normalnie do Warszawy. Po drodze mamy liczne losowe zdarzenia i krzyżowanie ruchu z innymi składami. Po dojechaniu do stacji Warszawa Wschodnia, gdy kierownik sprawdzi skład zjeżdzamy do stacji Warszawa Praga (wyjazd na linię 9 w kierunku Gdańska). Scenariusz kończy się tuż za stacją Warszawa Wschodnia.<br />
   UWAGA: jeżeli prowadzimy skład Regio i jedziemy linią podmiejską wówczas na Wschodniej przejeżdzamy z lini podmiejskiej na dalekobieżną i wjeżdzamy na peron 5 stacji Warszawa Wschodnia
<br /><br />
- <b>KM - Koleje Mazowieckie (dla osobowego dostępne 3 trasy):</b><br />
   Dostępne składy: EN57 / ELF / TRAXX<br />
   Dostępna ilość wagonów dla TRAXX: 3 / 4 / 5 (celowo wagony stare bo są na 160 km/h)<br />
   Domyślnie trasy dla KM zaczynają się w Skierniewicach na torze postojowym. Dla wersji osobowej mamy do dyspozycji dodatkowy start z Żyrardowa i Grodziska Mazowieckiego. Po rozpoczęciu misji udajemy się do stacji docelowej zatrzymując się na wszystkich postojach handlowych przewidzianych w rozkładzie jazdy. Rozkład RE został przygotowany na wzór obecnie obowiązujących przystanków KM do Skierniewic. Sprinter to wersja pośpieszna z zatrzymaniem tylko na głównych stacjach.
- Etapy:
    - ★ Początek ★
    - Koluszki
    - Skierniewice
    - Żyrardów
    - Grodzisk Mazowiecki
- Zdjęcia:<br />
![Photo1](Photos/Misja%205/Photo1.png)
![Photo2](Photos/Misja%205/Photo2.png)
![Photo3](Photos/Misja%205/Photo3.jpg)
![Photo4](Photos/Misja%205/Photo4.jpg)
![Photo5](Photos/Misja%205/Photo5.jpg)