Survival Vi, Vim, Nvim
======================

Vim ponoć ma wysoki próg wejścia.

Ale czy to prawda?

Po pierwsze: **Dlaczego umieć VI**?

ponieważ:
- precyzja
- dużo programów na linuxie inspirowana Vi używa klawiszy `h` `j` `k` `l`


## Absolutne minimum przetrwania

|Klawisz|Opis|
|---|---|
|i|Wejdź w tryb edycji, wstawiania -- INSERT --|
|ESC|Cofnij się do truby -- NORMAL -- | 
|←|Lewo|
|↓|dół|
|↑|góra|
|→|prawo|
|:wq|Zapisz aktualny plik, oraz wyjdź z programu|
|:q!|Wyjdź z programu i NIE zapisuj wprowadzonych zmian|
|:w|zapisz zmiany|

Z czasem zaczniesz unikać strzełek i w zamian będziesz używać `h` `j` `k` `l`.

Ale na dziś - wystarczy

## PANIKUJĘ!!

zacznij cisnąć w `ESC` kilkanaście razy, zazwyczaj pomaga!

Cofniesz się do trybu "NORMAL". A stamtąd już łatwo wyjść.

## Co to jest -- INSERT --

W tym trybie zmieniasz tekst, dodajesz go, usuwasz. Dokładanie tak jak w notatniku.

## Co to jest -- NORMAL --

Gdy uruchomisz Vi, Vim, Nvim, to domyślnie jesteś w trybie "NORMAL".

To jest tryb czytania, nie możesz pisać. Ale możesz poruszać kursorem.

Aby móc zacząć pisać, musisz wcisnąć klawisz `i` i wejść do trybu "INSERT"