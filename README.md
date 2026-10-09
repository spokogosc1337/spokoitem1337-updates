# CheatBreaker 1.7.10 — Angelica / HitFix

Publiczne paczki klienta oraz podpisany kanal automatycznych aktualizacji.

- Pobierz paczke `*-versions.zip` z [Releases](https://github.com/spokogosc1337/spokoitem1337-updates/releases/latest). Folder zawierajacy JAR i JSON skopiuj do `.minecraft/versions`; wybierz Java 17 lub nowsza.
- Alternatywnie importuj `*-Prism.zip` w Prism Launcher.
- Od 1.1.8 obie paczki sprawdzaja aktualizacje przy starcie gry. Osoby ze starszym buildem musza raz zainstalowac nowa paczke. Sam mod Forge JAR nie ma aktualizatora.
- Potrzebna licencja KeyAuth od wlasciciela klienta. Pierwsza aktywacja przypisuje ja do komputera; po wymianie/reinstalacji systemu moze byc potrzebny reset HWID przez wlasciciela.
- Prawy Shift: Mods. Przecinek: ukrycie/przywrocenie czatu i scoreboardu. Clear Glass: OFF / REGULAR / ALL w Resource Packs.
- Nie instaluj OptiFine ani dodatkowego HitFix obok tej paczki.

`latest.properties` zawiera podpisany manifest: wersja, URL, rozmiar i SHA-256 JAR-a. Launcher weryfikuje RSA-SHA256 przed pobraniem i SHA-256 przed uruchomieniem. Nie nadpisuje ustawien, swiatow ani zapisanej licencji. Przy problemach z aktualizacja zachowuje dzialajaca instalacje; aktywacja KeyAuth wymaga sieci.

Nie ma tutaj kodu zrodlowego, prywatnych kluczy uzytkownikow, tokenow API ani prywatnego klucza podpisujacego. Zrodla projektu sa w prywatnym repozytorium wlasciciela. Obfuskacja nie uniemozliwia dekompilacji Javy. Dawne uslugi online CB wymagaja osobnego backendu.
