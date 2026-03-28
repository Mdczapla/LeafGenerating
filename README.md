# BioMorphs: Procedural Leaf Generation 🍃

Projekt zrealizowany w **Unreal Engine 5**, eksplorujący koncepcję **biomorfizmu** w informatyce. System pozwala na proceduralne generowanie unikalnych struktur liści przy użyciu logiki Blueprint, symulując ewolucyjne i organiczne procesy tworzenia form.

## 🧬 Koncepcja: Biomorfizm
Projekt nawiązuje do biomorfizmu – nurtu w informatyce i sztuce, który polega na modelowaniu obiektów w oparciu o procesy biologiczne i naturalne kształty. Poprzez manipulację cyfrowym "genotypem" (parametrami), użytkownik może generować nieskończoną liczbę wariacji "fenotypu" (wizualnej formy liścia).

## 🚀 Kluczowe cechy
* **Proceduralny System Blueprint:** Każdy liść jest generowany dynamicznie w czasie rzeczywistym na podstawie zdefiniowanych zmiennych.
* **Mapa "BioMorphs":** Dedykowane środowisko prezentacyjne, w którym można obserwować wpływ poszczególnych parametrów na finalny kształt.
* **Determinizm i Losowość:** Wykorzystanie systemu Seedingu pozwala na powtarzalne generowanie konkretnych form lub pełną losowość.

## ⚙️ Parametry Konfiguracyjne
System oferuje szeroki zakres modyfikacji struktury liścia bezpośrednio z poziomu edytora:
* **New Seed:** Kontrola ziarna losowości dla unikalnych kształtów.
* **Num Of Points:** Rozdzielczość i liczba punktów definiujących krawędź liścia.
* **Leaf Length:** Całkowita długość struktury.
* **Base / Mid / Tip Width:** Precyzyjna kontrola szerokości u podstawy, w środku oraz na czubku liścia.
* **Sharpness:** Parametr definiujący ostrość krawędzi i charakter zakończeń struktury.

## 🛠 Technologie
* **Silnik:** Unreal Engine 5
* **Systemy:** UE5 Blueprints, Procedural Mesh / Spline Logic.

## 💻 Jak uruchomić
1. Sklonuj repozytorium do swojego folderu projektowego Unreal Engine.
2. Otwórz projekt w **Unreal Engine 5**.
3. Wyszukaj i otwórz mapę o nazwie **BioMorphs**.
4. Wybierz Actora liścia na scenie, aby w panelu *Details* modyfikować parametry w czasie rzeczywistym.
