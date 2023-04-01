Projekt wykorzystuje różne metody algorytmów klasteryzacji do grupowania spółek giełdowych na podstawie dwóch i czterech wskaźników finansowych. Celem było uzyskanie klastrów charakteryzujących się spójnością wewnątrz klastrową, separacyjnością między innymi klastrami oraz możliwością wykorzystania ich w analizie fundamentalnej.
# Dane

Dane zostały pobrane z strony internetowej https://simfin.com/ z zakładki "Data Finder" w roku 2019. Do opisania cech spółek wykorzystano wybrane wskaźniki finansowe służące do oceny rentowności, wyceny oraz zadłużenia.
# Metody

W pracy opisano metody hierarchiczne, partycyjne oraz gęstościowe klasteryzacji. Poddano omówieniu wpływ parametrów algorytmu na wynik. Funkcja podobieństwa obiektów została zdefiniowana za pomocą metryk. Wybrane wskaźniki posłużyły do oceny jakości grupowania.
# Narzędzia

Do implementacji klasteryzacji wykorzystano menager pakietów Anaconda Navigator z graficznym interfejsem oraz interaktywne środowisko programistyczne Jupyter Notebook. Biblioteki zawierające algorytmy klasteryzacji, które zostały zastosowane to PyClustering i Scikit-Learn. Wykorzystano język programistyczny Python 3.6.9.
# Wyniki

Podczas implementacji klasteryzacji spółek z dwoma wskaźnikami sprawdzono różne metody klasteryzacji. Metoda hierarchiczna z wiązaniem Warda wypadła w spośród wybranych najlepiej. Rezultatem klasteryzacji z dwoma wskaźnikami jest 45 klastrów, które zawierają przynajmniej 10 spółek, jest w nich łącznie 1465 spółek. Proponowanych do dalszej weryfikacji z perspektywy analizy fundamentalnej jest 13 klastrów, w których znajduje się 729 spółek.

Do implementacji klasteryzacji spółek z czterema wskaźnikami wybrano metodę hierarchiczną ze względu na dobre wyniki w przypadku klasteryzacji spółek z dwoma wskaźnikami. Wynikiem klasteryzacji z czterema wskaźnikami jest 25 klastrów, które zawierają przynajmniej 10 spółek, jest w nich łącznie 793 spółek. Proponowanych do dalszej weryfikacji z perspektywy analizy fundamentalnej jest 15 klastrów, w których zgromadzonych jest 533 spółek.
# Uruchamianie projektu

Projekt można uruchomić poprzez otwarcie notebooków .ipynb w środowisku Jupyter i wywołanie zawartych w nim komórek.

**Uwaga:** Do prawidłowego funkcjonowania należy wprowadzić poprawną scieżkę do pliku z danymi .xslx.
# Licencja

Klasteryzacja spółek giełdowych udostępniana jest na licencji MIT. Szczegóły znajdują się w pliku LICENSE.
