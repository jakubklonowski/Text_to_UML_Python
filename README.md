# Narzędzie do ekstrakcji komponentów diagramu przypadków użycia na podstawie zapisu rozmowy z klientem

## Autor

Autorem skryptu oraz dokumentacji jest Jakub Klonowski, student Uniwersytetu Łódzkiego. Oprogramowanie powstało w ramach pracy dyplomowej.

## Wymagania sprzętowe, środowiska oraz bezpieczeństwa

Wymagania sprzętowe i środowiska:
- system Windows10 64-bit;
- 8GB pamięci RAM;
- 10GB wolnej pamięci na dysku twardym;
- procesor o taktowaniu co najmniej 1.90 GHz;
- profil administratora;
- język CPython w wersji 3.10.6;
- środowisko Jupyter Notebook w wersji 6.4.12;
- biblioteka spaCy oraz polski potok do niej, oba w wersji 3.4.0;
- biblioteka pandas w wersji 1.2.4 oraz matplotlib w wersji 3.3.4;
- zainstalowany i skonfigurowany program MS Excel.

Wymagania bezpieczeństwa:
- z oprogramowania należy korzystać wyłączenie zgodnie z prawem;
- z oprogramowania należy korzystać wyłączenie zgodnie z zasadami BHP;
- z oprogramowania należy korzystać wyłączenie zgodnie z instrukcją.

## Konfiguracja środowiska

Należy pobrać i zainstalować język Python w implementacji CPython (https://www.python.org).

Należy pobrać i zainstalować środowisko Jupyter Notebook. Użyj w tym celu w konsoli Windows PowerShell polecenia:
- 'pip install notebook==6.4.12'.

Po zainstalowaniu Jupyter Notebook należy uruchomić Anaconda3 Prompt i pobrać za jej pomocą wszystkie potrzebne zasoby:
- polecenie 'pip install spacy==3.4.0' - aby pobrać bibliotekę spaCy;
- polecenie 'python -m spacy download pl_core_news_lg==3.4.0' - aby pobrać polski korpus językowy do biblioteki spaCy (uwaga: wielkość - ponad 500 MB!);
- polecenie 'pip install pandas==1.2.4' - aby pobrać bibliotekę pandas;
- polecenie 'pip install matplotlib==3.3.4' - aby pobrać bibliotekę matplotlib;

Następnie użyj polecenia 'pip check' aby sprawdzić czy wszystkie potrzebne zależności zostały pobrane, w razie potrzeby proszę je doinstalować.

Środowisko Jupyter Notebook jest gotowe do uruchomienia.

## Uruchomienie skryptu

Wypakuj archiwum z plikami do wybranego katalogu na dysku (uwaga - nie zaleca się wypakowywania plików na pulpicie!).
Uruchom Jupyter Notebook, środowisko otworzy się w przeglądarce. Następnie otwórz za jego pomocą plik 'spaCy.ipynb'.

Instrukcja użytkowania znajduje się w pracy dyplomowej.
