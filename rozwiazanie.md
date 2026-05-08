## Proponowany model: „Klikacz” (prosty fidget z wyczuwalnym kliknięciem)

To dobry wybór na szybki projekt w MoI 3D, bo:
- ma ruchomy element (wymóg zadania),
- może mieć 4 części (zgodnie z Twoim pomysłem),
- łatwo dodać napis/logo „Wydział Elektryczny”,
- mieści się w limicie 10 cm.

---

## Części modelu (4 elementy)
1. **Dolna obudowa** – kieszeń na sprężynę + prowadzenie dla trzpienia.
2. **Górna obudowa** – zamknięcie (zatrzaski lub 4 śrubki M2).
3. **Trzpień (stem)** – element wciskany, poruszający się góra–dół.
4. **Nakładka (cap)** – część naciskana palcem, z napisem/logo.

---

## Wymiary startowe (żeby projekt był prosty i drukowalny)
- Całość: **40 × 30 × 18 mm** (bezpiecznie poniżej 100 mm).
- Grubość ścianek: **2.0 mm**.
- Luz między ruchomymi elementami: **0.25–0.35 mm**.
- Sprężyna: np. długopisowa, długość robocza ~10–15 mm.

---

## Instrukcja krok po kroku (MoI 3D)

### Krok 1: Ustal założenia
1. Zapisz finalny limit wymiaru: max 100 mm.
2. Wybierz napis na model: „Wydział Elektryczny” lub skrót/logo.
3. Zdecyduj o sposobie zamknięcia: zatrzaski (szybciej) albo śrubki M2 (pewniej).

### Krok 2: Zrób dolną obudowę
1. Narysuj prostokąt 40 × 30 mm.
2. Wyciągnij (Extrude) na wysokość 10 mm.
3. Wydrąż środek (Shell/Boolean Difference), zostawiając 2 mm ścianek.
4. Dodaj centralne gniazdo pod sprężynę (np. cylinder Ø8 mm, głębokość 5 mm).
5. Dodaj pionowe prowadnice dla trzpienia.

### Krok 3: Zrób górną obudowę
1. Skopiuj obrys dolnej obudowy.
2. Utwórz pokrywę o wysokości ok. 8 mm.
3. Dodaj otwór prowadzący pod trzpień (z luzem 0.25–0.35 mm).
4. Dodaj zatrzaski lub otwory pod śrubki.

### Krok 4: Zrób trzpień (stem)
1. Utwórz walec/prostopadłościan dopasowany do prowadnic.
2. Dodaj dolny „talerzyk” opierający się o sprężynę.
3. Dodaj ogranicznik skoku (żeby stem nie wyskakiwał).
4. Ustaw skok na ok. 2–3 mm (wystarczy do wyczuwalnego kliknięcia).

### Krok 5: Dodaj prosty mechanizm „klik”
1. W górnej obudowie dodaj mały próg/wypust.
2. Na trzpieniu dodaj współpracujący skos.
3. Przy wciskaniu skos przechodzi przez próg i daje odczuwalne „klik”.
4. Uprość geometrię – lepiej 1 próg niż złożony mechanizm.

### Krok 6: Zrób nakładkę (cap)
1. Utwórz prostą nakładkę na górę trzpienia.
2. Dodaj tekst/logo jako wypukłe lub grawerowane (0.6–1.0 mm wysokości/głębokości).
3. Zaokrąglij krawędzie (Fillet), żeby była wygodna w użyciu.

### Krok 7: Sprawdzenie pod druk 3D
1. Usuń ostre, cienkie elementy <1 mm.
2. Sprawdź, czy każdy element ma zamkniętą bryłę.
3. Potwierdź luzy ruchu (min. 0.25 mm).
4. Upewnij się, że model drukuje się bez trudnych podpór.

### Krok 8: Eksport plików do oddania
1. Zapisz projekt źródłowy MoI (`.3dm`).
2. Wyeksportuj każdy element do `.stl` (lub `.obj`).
3. Nazwij pliki czytelnie, np.:
   - `klikacz_dol.stl`
   - `klikacz_gora.stl`
   - `klikacz_stem.stl`
   - `klikacz_cap.stl`
   - `klikacz_projekt.3dm`

### Krok 9: Ustawienia druku (Bambu Lab X1C, dysza 0.2 mm)
1. Warstwa: **0.10–0.16 mm**.
2. Ściany: **3 obrysy**.
3. Infill: **15–25%** (Grid/Gyroid).
4. Materiał na start: PLA.
5. Jeśli mechanizm klika zbyt ciężko – zwiększ luz o 0.05–0.1 mm.

### Krok 10: Co oddać prowadzącemu
1. Komplet plików `.stl`/`.obj`.
2. Plik źródłowy `.3dm`.
3. Krótki opis:
   - że model ma ruchomy element,
   - że zawiera napis/logo wydziału,
   - że największy wymiar nie przekracza 10 cm.

---

## Dlaczego ten projekt jest dobry na szybkie wykonanie
- Prosta bryłowa geometria (łatwa w MoI 3D).
- Spełnia wszystkie wymagania formalne.
- Łatwo poprawiać (luzy, klik, skok) bez przebudowy całości.
