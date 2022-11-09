# Vim, vi, nvim - edycja tekstu

Vim ponoć ma wysoki próg wejścia, i ponoć jest trudny.

Ale czy to prawda?

Po pierwsze: **Dlaczego umieć VI**?

ponieważ:
- dużo programów na linuxie inspirowana Vi używa klawiszy `h` `j` `k` `l`
- precyzja
- będziesz mógł się przechwalać, że jesteś najlepsiejszy!

## Absolutne minimum przetrwania

|Klawisz|Opis|
|---|---|
|`vi nazwaPliku`|Otwórz plik w programie Vim|
|`i`|Wejdź w tryb edycji, wstawiania `-- INSERT --`|
|`ESC`|Wyjdź się do trybu `-- NORMAL --`| 
|`←`|Lewo|
|`↓`|dół|
|`↑`|góra|
|`→`|prawo|
|`:wq`|Zapisz aktualny plik, oraz wyjdź z programu, z trybu `NORMAL`|
|`:q!`|Wyjdź z programu i NIE zapisuj wprowadzonych zmian, z trybu `NORMAL`|
|`:w`|zapisz zmiany, z trybu `NORMAL`|

Z czasem zaczniesz unikać strzełek i w zamian będziesz używać `h` `j` `k` `l`.

Ale na dziś - wystarczy

## PANIKUJĘ!!

zacznij cisnąć w `ESC` kilkanaście razy, zazwyczaj pomaga!

Cofniesz się do trybu "NORMAL". A stamtąd już łatwo wyjść.

## Co to jest -- INSERT --

W tym trybie zmieniasz tekst, dodajesz go, usuwasz. Dokładanie tak jak w notatniku.

## Co to jest -- NORMAL --

Gdy uruchomisz Vi, Vim, Nvim, to domyślnie jesteś w trybie "NORMAL".

To jest tryb czytania, nie możesz pisać. Ale możesz poruszać kursorem.

Aby móc zacząć pisać, musisz wcisnąć klawisz `i` i wejść do trybu "INSERT"