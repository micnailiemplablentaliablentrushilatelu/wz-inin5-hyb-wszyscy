# Zasady współpracy – Przewodnik po stolicach Europy

## 🏷️ Nazewnictwo branchy

Każdy student tworzy osobną gałąź według wzoru:
stolica_imie

## 🛠️ Tworzenie Issue

Jeśli zauważysz problem, dodaj *Issue* z:
- jasnym tytułem (np. „Brak zdjęcia w sekcji Rzym”)
- etykietą (`bug`, `suggestion`, `question`, itp.)
- przypisaną osobą (jeśli wiadomo kto się tym zajmie)

## 🔀 Pull Request

Aby zaproponować zmianę, utwórz *Pull Request*:
- PR musi dotyczyć jednej stolicy
- W opisie PR napisz:
- co dodałeś (np. opis stolicy, zdjęcie, sekcja HTML)
- skąd pochodzi zdjęcie (link do źródła)
- link do zadania Trello w sekcji „In progress”
Przed wysłaniem PR:
- Upewnij się, że zdjęcie jest w katalogu `img/`
- Sekcja HTML musi mieć strukturę:

<section>
<h2>Stolica</h2>
<img src="img/nazwa_pliku.jpg" alt="Opis zdjęcia">
</section>