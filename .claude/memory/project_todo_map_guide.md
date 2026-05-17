---
name: map-guide-todo
description: Features Joe wants to add to the map and guide — not yet implemented
metadata:
  type: project
---

Følgende kategorier skal tilføjes til guiden og/eller kortet. Ingen er implementeret endnu.

| Kategori | Kort | Guide |
|---|---|---|
| Barer | ✓ | ✓ |
| Punkter på Garbatella walking tour | ✓ | – |
| To eat-liste (steder Joe vil besøge) | ✓ | – |
| Is (gelaterie) | ✓ | ✓ |

**Why:** Joe vil have kortet til at vise mere end restauranter og seværdigheder — barer og gelaterie hører naturligt til i en madguide, walking tour-stops giver kontekst til Garbatella-afsnittet, og to eat-listen på kortet giver brugeren et overblik over uudfyldte anbefalinger.

**How to apply:** Når implementering starter — tilføj nye kategorier i RESTAURANTS/SIGHTS-datastrukturen eller lav separate arrays (BARS, GELATERIAS, WALKINGTOUR, TOEAT). Tilsvarende nye markerfarver og filterknapper på kortet. Barer og gelaterie skal også have kortekster og anmeldelser i guide.html.
