# Wyjaśnienie kluczowych pojęć w Androidzie

* **setContentView** – wskazuje plik layoutu XML, który ma stanowić wygląd danego ekranu.
* **findViewById** – wyszukuje i pobiera dany element z interfejsu XML na podstawie jego ID, aby użyć go w kodzie Javy.
* **R** – automatycznie generowana klasa zawierająca numeryczne identyfikatory wszystkich zasobów projektu (layoutów, ID, napisów).
* **onCreate** – metoda cyklu życia wywoływana przez system Android w momencie tworzenia ekranu.
* **super.onCreate** – wywołanie bazowej metody z klasy nadrzędnej, konieczne do prawidłowego przygotowania ekranu.
* **AndroidManifest.xml** – plik konfiguracyjny zawierający metryczkę aplikacji, listę ekranów i wymagane uprawnienia.
* **@+id/** – składnia w pliku XML służąca do utworzenia nowego identyfikatora dla danego elementu.
* **match_parent** – wartość wymiaru oznaczająca rozciągnięcie elementu do szerokości lub wysokości rodzica.
* **dp** – jednostka miary rozmiaru i odstępów elementów, niezależna od gęstości pikseli ekranu.
* **sp** – jednostka miary tekstu, uwzględniająca dodatkowo systemowe skalowanie czcionki dla dostępności.