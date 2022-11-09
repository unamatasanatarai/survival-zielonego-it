# git - jak przetrzymywać kod _na internetach_

> Najpierw naucz się poprawnie, potem skorzystaj z gotowców.

GitHub jest za darmo, więc zacznij z niego korzystać już dziś.

## Survival

|komenda|opis|
|---|---|
|`git clone https://github.com/unamatasanatarai/survival-zielonego-it.git`|Zrób kopię repozytorium `survival-zielonego-it` w katalogu na Twoim komputerze. Nie będziesz mógł w nim nic zmieniać - zaczyna się od `https://`|
|`git clone git@github.com:unamatasanatarai/survival-zielonego-it.git`|Zrób kopię repozytorium `survival-zielonego-it` w katalogu na Twoim komputerze. W tym repozytorium możesz zmieniać co chcesz i zapisywać - zaczyna się od `git@`. Oczywiście, musisz mieć dostęp do tego repozytorium.|
|`git init`|Utwórz repozytorium .git w katalogu, w którym się znajdujesz.
|`git config user.name "Niepodawaj Prawdziwychdanych"`|Aby móc wysyłać kod do repozytorium, musisz się przedstawić|
|`git config user.email "AdresE-Mail@nikomu.nie.mow"`|Aby móc wysyłać kod do repozytorium, musisz się zidentyfikować|
|`git status`|Sprawdź czy są jakieś zmiany w lokalnym repozytorium|
|`git diff`|Porównaj zmiany z tym co było _oryginalnie_|
|`git add --all`|Dodaj wszystkie zmiany(pliki) do bazy danych gita|
|`git commit -m "Opis commita"`|Nazwij wszystkie zmiany zanim je wyślesz do repozytorium|
|`git push`|Wyślij dodane i zacommitowane zmiany do internetu.|
|`git push -u origin main`|Jeśli `git push` nie da rady, wskaż konkretną gałąź (branch) do której wysyłasz zmiany.|
|`git pull`|Pobierz wszelkie zmiany z _internetu_ na dysk twardy|
