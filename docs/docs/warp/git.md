# Git Cheat Sheet

[WARP](docs/warp/git.md)

| Polecenie | Przykład użycia | Co opisać |
| --- | --- | --- |
| git clone | ``` bash git clone URL ``` | Pobranie repozytorium i utworzenie lokalnego katalogu.|
| git status | ``` bash git status ``` | Sprawdzenie gałęzi oraz plików zmienionych i przygotowanych. |
| git add | ``` bash git add docs/warp/git.md ``` | Dodanie konkretnego pliku do obszaru staging. |
| git commit | ``` bash git commit -m "docs: add Git cheatsheet" ``` | Zapis przygotowanych zmian z czytelnym komunikatem. |
| git push | ``` bash git push -u origin feature/git-cheatsheet ``` | Publikacja nowej gałęzi i ustawienie śledzenia. |
| git pull | 	``` bash git pull --ff-only origin main ``` | 	Pobranie zmian bez tworzenia nieoczekiwanego merge commita. |
| git fetch | ``` bash git fetch origin ``` | 	Pobranie informacji o zmianach bez modyfikowania plików roboczych. |
| git branch | ``` bash git branch ``` | Wyświetlenie lokalnych gałęzi i oznaczenie aktywnej. |
| git switch | 	``` bash git switch -c feature/nazwa ``` | 	Utworzenie gałęzi roboczej i przełączenie na nią. |
| git log |	``` bash git log --oneline -5 ``` | Skrócony podgląd pięciu ostatnich commitów. |

