# myLibri: pobierz aplikację

Tu są gotowe wersje myLibri, bez kodu. Każda wersja to jedno wydanie w
[Releases](https://github.com/ReimaginedPixel/MyLibri-releasees/releases):
`android-build-…` z plikiem `myLibri.apk` i `ios-build-…` z plikami `.ipa`.
Wydania robią się same, kiedy w aplikacji pojawia się coś nowego.

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
