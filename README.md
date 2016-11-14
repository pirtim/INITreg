# INITreg
## Oficjalny regulamin Studenckiego Koła Innowacji i Transferu Technologii INIT

Dokument w formacie `.pdf` znajduje się w zakładace `Releases`.

### Szczegóły techniczne:
Dokument podzielony jest na dwie części.
Część merytoryczna dokumentu znajduje się w pliku `reg_text.tex`.
Cześć techniczna kontrolująca wygląd (deklaracje importowanych pakietów, funkcji itp.) znajduje się w pliku `main.tex`.

W celu uzyskania wersji `.pdf` z plików źródłowych konieczna jest kilkukrotna (w celu rozwiązani wszystkich wewnętrznych referencji) kompilacja przy pomocy (lub równoważnego polecenia):
```bash
xelatex main.tex -aux-directory="./.tex_output"
```

<!--Może być przydatne (dopuszczenie plików o nazwach z znakami nie-ASCII):
```bash
git config hooks.allownonascii true
```-->