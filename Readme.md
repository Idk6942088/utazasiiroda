# Verziókezelés

## Helyi repo létrehozása

- inicializálás:
    > git init
- git felhasználó ellenörzése:
    > git config user.name

    > git config user.email
- ellenörzés(van e különbség a heliy és a repo közt?)
    > git status
- előkészítjük a commit-ra, minden változást eltárolunk
    > git add .
- ellenörzés:
    > git status
- eltárolása au újabb verziónak:
    > git commit -m "first"

## Összekapcsolás a távoli repoval (Github)
- új repo létrehozása
- helyi repo összekapcsolása a távolival:
    > git remote add origin https://token@github.com/Idk6942088/utazasiiroda.git
- első push-nál meg kell adni a branch nevét:
    > git push -u origin master