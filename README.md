RUNow to działająca aplikacja na Androida oparta na Javie do śledzienia tras podczas biegania.

GŁÓWNA AKTYWNOŚĆ
U góry głównej czynności przycisk przełączania — „Motyw” dla różnych motywów - tryb dzienny i nocny znajduje się w lewym rogu, który użytkownik może dowolnie wybierać podczas biegania. Obok w prawym górnym rogu przycisk o nazwie „Historia” prowadzący do kolejnej strony z zapisami przebiegów, którymi użytkownik może manipulować.
Główne działanie aplikacji składa się głównie z fragmentu mapy, który pokazuje aktualną lokalizację w interfejsie Google Maps podczas działania. 
Podczas biegu wielokolorowa linia pokazuje trasę w zależności od tempa biegaczy. 
Linia symbolizuje tempo biegu w trzech kolorach (czerwony – żółty – zielony) co odpowiada trzem różnym zakresom tempa, czerwony reprezentuje wolne i zielony reprezentuje szybko.
Pod mapą znajduje się dashboard z informacjami, które są zbierane podczas pracy użytkownika. Aplikacją steruje się za pomocą trzech przycisków u dołu strony.
Za pomocą przycisku „start” rozpoczyna się nowa aktywność biegowa. Gdy użytkownik biegnie, pewne zmienne są gromadzone i wyświetlane pod fragmentem mapy w odpowiednich TextViews, 
takie jak dystans, tempo, czas trwania biegu i spalone kalorie. Logo zmienia się w przycisk „wstrzymaj”, gdy tylko aktywność zostanie rozpoczęta i na chwilę zatrzymuje śledzenie biegu i obliczanie zmiennych, 
dopóki bieg nie będzie kontynuowany za pomocą tego samego przycisku, co oznacza „wznów”. 
Przycisk „stop” kończy rejestrację biegu i dodaje śledzony bieg do historii biegu (lokalnej bazy danych) wraz ze wszystkimi obliczonymi zmiennymi.

PRZEŁĄCZNIK MOTYWU
Aplikacja zapewnia tryb dzienny i tryb nocny dla lepszego doświadczenia użytkownika w różnych sytuacjach oświetleniowych poprzez przełączenie przełącznika. 
W trybie dziennym interfejs użytkownika jest utrzymany w jaśniejszym odcieniu pasującym do schematu kolorów.

STRONA NAGRYWANIA
Przycisk z ikoną „pamięć” w prawym górnym rogu w głównej aktywności aplikacji prowadzi do strony zapisu. 
Za pomocą przycisku „WSTECZ”, znajdującego się na lewo od przycisku „kosz”, użytkownik zostaje przekierowany na stronę główną. 
A za pomocą przycisku „kosz” możesz wyczyścić wszystkie rekordy (całą tabelę) naraz. 
Ponadto umożliwia użytkownikom usuwanie pojedynczych wpisów za pomocą przycisku „usuń” na początku każdego wiersza. 
Na stronie zapisu wpisy biegu wraz z czasem i obliczonymi danymi, w tym identyfikator dla każdego wyniku, dystansu i spalonych kalorii, są wymienione w głównym TextView.
