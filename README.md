# NOME_REPO

> **Hai appena creato la repo da questo template? Fai questi passi, poi cancella questo riquadro.**
>
> 1. Rinomina la repo nel formato `<rov>_<componente>_pcb` (es. `nereo_power_pcb`).
> 2. Aggiungi il topic **`electronics`** (ingranaggio accanto ad "About"). I topic non vengono copiati dal template.
> 3. *Settings → Pages → Deploy from a branch → main → /docs → Save*.
> 4. Metti il progetto KiCad dentro `hardware/` (un solo `.kicad_pro`), con le librerie della scheda in `hardware/lib/local/`.
> 5. Sostituisci `NOME_REPO`, `NOME_PROGETTO` e il link al firmware qui sotto. `NOME_PROGETTO` è il nome del file `.kicad_pro` senza estensione.
> 6. Fai `git pull` prima di ogni modifica: dopo ogni push il bot aggiunge i render.

Descrizione della scheda (ROV, funzione, microcontrollore, numero di layer).
Firmware: [NOME_REPO_FIRMWARE](https://github.com/PoliTOcean/NOME_REPO_FIRMWARE)

[![Interactive BOM](https://img.shields.io/badge/Interactive_BOM-open-1B7F3B)](https://politocean.github.io/NOME_REPO/)

| Top | Bottom |
|---|---|
| ![Top](docs/img/NOME_PROGETTO-top.png) | ![Bottom](docs/img/NOME_PROGETTO-bottom.png) |

![3D](docs/img/NOME_PROGETTO-3d.png)

## File di produzione

Gerber, forature e PDF dello schema si scaricano da **Actions → ultima run → pcb-outputs**.

## Struttura

~~~
hardware/            progetto KiCad
hardware/lib/local/  simboli, footprint e modelli 3D usati solo da questa scheda
docs/                render e interactive BOM (generati dal bot, non modificare)
~~~
