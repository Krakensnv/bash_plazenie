# Vitaj v bash plazení!

(Bash - tlmočník príkazového jazyka)
(plazenie - zrejme to pojde pomaly :-)

## Toto je hra, ktorá ťa naučí základy používania terminálu POSIX (Linux, BSD, UNIX).

Ak chceš začať hrať, otvor terminál.

Do terminálu zadaj písmená "cd" (iba písmená, nie úvodzovky)...

Potom medzera (stlač medzerník)...

Potom potiahni a pusť adresár `vstup` z tohto priečinka do tvojho terminálu.

Ak sa ťa tvoj terminál spýta, čo chceš urobiť s tým, čo si doň práve pretiahol, 
vyber `Prilepiť umiestnenie`.
Ak sa to nepýta, očakávaj, že doň vloží cestu k súboru priečinka, ktorý si práve pretiahol.

Akonáhle budeš mať niečo ako:

```
$ cd /home/tvoje_meno/Downloads/bash_plazenie/vstup
```

V okne terminálu stlač RETURN.
Presná cesta k vstupu sa líši v závislosti od toho, kde si súbor uložil.

**Tvoj prvý krok je veľmi dôležitý. Vo zvitkoch vždy nájdeš potrebné informácie ako postupovať ďalej.**
Zadaj toto do svojho terminálu:

```
cat zvitok
```

## Teraz hráš hru.
Nech ťa bohovia zachránia :-)

## POZNÁMKY PRE macOS X
Zdá sa, že sa vyskytol problém so štandardným nástrojom `Archive Utility`, ktorý sa volá z nástroja `Finder`
keď na archív zip dvakrát klikneš, aby si ho rozbalil do aktuálneho priečinka,
ak sťahuješ archív z GitLab namiesto použitia nástroja `git clone` na priame stiahnutie hry.
Môžeš zistiť, že všetky súbory v cieľovom priečinku sú nastavené ako spustiteľné.
To spôsobí veľký zmätok, keď budeš hrať hru podľa plánu,
pretože každý obyčajný textový súbor bude na nerozoznanie od spustiteľných skriptov.
Tu je návod, ako sa tomuto problému vyhnúť:

1. Otvor svoju obľúbenú aplikáciu emulátora terminálu (napr. „Terminal.app“ alebo „iTerm2“).
2. Prejdi do adresára, kde chceš rozbaliť archív zip:
    ```
    cd /cesta/k/cieľu
    ```

3. Nahraď '/cesta/k/cieľu' relatívnou cestou (nezačína lomítkom '/')
alebo absolútnou (začína lomítkom '/') cestou k požadovanému cieľu.
4. Napíš `unzip ` (to je 'unzip' nasledované jednou alebo viacerými *medzerami* [aspoň raz stlač medzerník])
5. Z `Finder` pretiahni súbor bash_plazenie-main.zip do okna emulátora terminálu.
Absolútna cesta k stiahnutému archívu by mala byť vložená do okna terminálu
podobné nasledujúcemu:
    ```
    unzip /Users/${USER}/Downloads/bash_plazenie-main.zip
    ```
	
6. Stlačením `Enter` rozbalíš obsah archívu zip do aktuálneho adresára.
7. V okne terminálu zmeň adresár na `bash_plazenie/vchod`:
    ```
    cd bash_plazenie/vchod
    ```

## V tomto bode si v hre! Príjemnú zábavu!
Nech ťa bohovia zachránia :-)