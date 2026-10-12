# myLibri: pobierz aplikację

**Strona z pobieraniem: https://reimaginedpixel.github.io/MyLibri-releasees/**

Tu są gotowe wersje myLibri, bez kodu. Każda wersja to jedno wydanie w
[Releases](https://github.com/ReimaginedPixel/MyLibri-releasees/releases):
`android-build-…` z plikiem `myLibri.apk` i `ios-build-…` z plikami `.ipa`.
Wydania robią się same, kiedy w aplikacji pojawia się coś nowego.

## Zanim pobierzesz

- **To nie jest aplikacja Librusa.** myLibri to niezależny, nieoficjalny
  projekt. Nie jest tworzony, sprawdzany ani wspierany przez firmę Librus i nie
  jest z nią w żaden sposób powiązany. Librus i Synergia to znaki towarowe ich
  właścicieli.
- **Może naruszać regulamin Librusa.** Aplikacja łączy się z Librusem
  nieoficjalnie. Korzystanie z niej może być niezgodne z regulaminem Librusa,
  a Librus może to w każdej chwili utrudnić, zablokować albo ograniczyć dostęp
  do konta.
- **Na własną odpowiedzialność.** Aplikację dostajesz „tak jak jest”, bez
  żadnych gwarancji. W granicach, na jakie pozwala prawo, autor nie odpowiada
  za żadne szkody: za utracone dane, zablokowane konto, kłopoty z telefonem ani
  za błędy w ocenach, frekwencji czy planie. Zawsze wiążący jest oficjalny
  Librus.
- **Pobieraj tylko stąd.** Kopie z innych miejsc mogą być podmienione.

Pobierając, akceptujesz te zasady.

## Android

1. Otwórz na telefonie
   [najnowszą wersję na Androida](https://github.com/ReimaginedPixel/MyLibri-releasees/releases/latest)
   albo od razu pobierz
   [myLibri.apk](https://github.com/ReimaginedPixel/MyLibri-releasees/releases/latest/download/myLibri.apk).
2. Otwórz pobrany plik i dotknij **Zainstaluj**. Za pierwszym razem telefon
   zapyta, czy pozwolić przeglądarce instalować aplikacje.
3. Nowa wersja instaluje się na starą: oceny, notatki i ustawienia zostają.

## iPhone

iPhone nie zainstaluje tych plików prosto z Safari. W
[liście wersji](https://github.com/ReimaginedPixel/MyLibri-releasees/releases)
znajdź najnowsze wydanie `ios-build-…` i wybierz jedno:

- **SideStore albo AltStore:** pobierz `myLibri-sidestore.ipa` i otwórz go w
  aplikacji. Nie ma w nim aplikacji na Apple Watch (SideStore jej nie
  podpisze), ale lekcja z odliczaniem i tak pokazuje się na zegarku.
- **Sideloadly:** na komputerze pobierz `myLibri-unsigned.ipa` (z aplikacją
  na zegarek) i zainstaluj ją swoim Apple ID.

Potem na iPhonie zaufaj swojemu Apple ID w Ustawienia > Ogólne > VPN i
zarządzanie urządzeniem (na iOS 16 i nowszym włącz też Tryb dewelopera). Z
darmowym Apple ID aplikacja działa 7 dni; odśwież ją albo zainstaluj ponownie.

## Skąd myLibri wie, że jest nowa wersja

Aplikacja co kilka godzin zagląda na tę stronę (publiczne API GitHuba, bez
konta i bez żadnych Twoich danych) i porównuje numer swojego buildu z
najnowszym. Kiedy jest nowszy, Start pokazuje „Nowa wersja myLibri”, a
Ustawienia > O aplikacji mówią, co się zmieniło i skąd pobrać.
