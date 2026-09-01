# Kontekst projektu

To jest osobiste repozytorium z agentami i skryptami używanymi w Claude Code,
zsynchronizowane między Makiem (dom) a Windowsem (praca).

## Zasady ogólne

- Pisz skrypty tak, żeby działały zarówno na macOS, jak i Windows (albo wyraźnie
  zaznacz, jeśli coś jest specyficzne dla jednego systemu).
- Przed usunięciem lub przeniesieniem plików zawsze pokaż plan działania i poproś
  o potwierdzenie, chyba że wyraźnie powiem "rób bez pytania".
- Preferuj Python do skryptów wieloplatformowych (moduł `pathlib`, `shutil`).
- Komentarze w kodzie i podsumowania działań pisz po polsku.

## Struktura repozytorium

- `.claude/agents/` — definicje subagentów (każdy w osobnym pliku .md)
- `.claude/commands/` — własne komendy /slash
- `scripts/` — samodzielne skrypty (np. do porządkowania plików)
- `projekty/` — foldery poszczególnych projektów

## Znane środowiska

- **Mac (dom):** macOS, foldery domowe pod `~/`
- **Windows (praca):** Windows, foldery domowe pod `C:\Users\<nazwa>\`
