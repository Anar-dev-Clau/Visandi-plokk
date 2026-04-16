# Visandiplokk

Ühe-faililine HTML rakendus portfoolio ja materjali esitlemiseks mobiilseadmes.

## Kasutus

**Arvutis** — ava `visand.html` brauseris:
- Lisa teksti ja pilte toolbar'ist
- Lohista elemente, muuda suurust nurgast
- Klikk elemendil → vali · `Delete` klahv → kustuta
- `Salvesta fail` → genereerib `visand_VALMIS.html` mobiilile saatmiseks

**Mobiilis** — ava `visand_VALMIS.html`:
- Vaatamine ainult, muutmine pole võimalik
- Swipe üles/alla → lehtede vahel liikumine
- Portrait asend — landscape blokeeritud

## Struktuur

```
visandiplokk/
  visand.html        ← arendusfail (see fail)
  README.md
  arhitektuur.md     ← arhitektuursed otsused ja lõksud
  .gitignore
```

## Commit distsipliin

- Iga toimiv versioon = commit
- Tag `lukupunkt-N` enne riskantseid muutusi
- `visand_VALMIS.html` ei commitita (ainult saatmiseks)
