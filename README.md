# PW_WNC

Aplikacja do rezerwacji biurek (shared desking). Użytkownik widzi plan piętra, klika wolne biurko i rezerwuje je na wybrany dzień. W kolejnych etapach: sale i parking.

Projekt wdrożeniowy na studia.

## Zespół
- _Weronika Żukowska_ – Git, frontend
- _Chantal Krupa_ – backend
- _Natalia Józefczuk_ – bazy danych, DevOps

## Stack
- **Frontend:** React, Vite, TypeScript
- **Backend:** Python, FastAPI
- **Baza danych:** PostgreSQL
- **Uruchamianie:** Docker Compose

## Struktura repozytorium
```
frontend/   # aplikacja React
backend/    # API w FastAPI
.github/    # szablon PR, workflowy CI
```

## Jak uruchomić
_Uzupełnimy, gdy będzie szkielet aplikacji (docelowo `docker compose up`)._

1. Skopiuj `.env.example` do `.env` i uzupełnij wartości.
2. ...

## Zasady pracy w zespole

### Branche
- `main` zawsze działa. Nie pushujemy na nią bezpośrednio.
- Każde zadanie to osobny branch: `feature/...`, `fix/...`, `chore/...`
  (np. `feature/login-page`).

### Commity
Format: `typ: krótki opis`, gdzie typ to jedno z:
- `feat` – nowa funkcja
- `fix` – poprawka błędu
- `docs` – dokumentacja
- `chore` – porządki, konfiguracja
- `test` – testy

Przykład: `feat: dodaj widok logowania`

### Pull Requesty
- Małe PR-y (zadanie na kilka godzin pracy).
- Każdy PR ma co najmniej jednego recenzenta.
- Recenzja w ciągu 24 godzin.
- Merge przez **Squash and merge**, potem usuwamy branch.

### Bezpieczeństwo
- Nigdy nie commitujemy `.env`, haseł ani kluczy.
- Jeśli sekret trafi do repo, od razu zmieniamy hasło lub klucz (samo usunięcie pliku nie wystarczy).

## Zadania
Tablica zadań: [Jira](https://chantalkrupa.atlassian.net/jira/software/projects/KAN/list?jql=project%20%3D%20KAN%20ORDER%20BY%20cf%5B10019%5D%20ASC&visitedUserSeg=true).
