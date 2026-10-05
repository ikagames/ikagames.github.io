# ikagames.github.io

Sito statico dell'organizzazione **IkaGames**, pubblicato con [GitHub Pages](https://pages.github.com/) su <https://ikagames.github.io>.

Struttura:

- `/` — hub studio (lista giochi)
- `/ikapop/` — vetrina di **IkaPop!** e link allo store
- `/ikapop/privacy.html` — informativa privacy di IkaPop!
- `/app-ads.txt` — verifica AdMob (alla root del dominio, condiviso da tutti i giochi)
- `.nojekyll` — disabilita Jekyll su GitHub Pages

URL utili per Play Console / AdMob:

| Uso | URL |
|-----|-----|
| Sito sviluppatore (hostname per app-ads) | `https://ikagames.github.io` |
| Pagina gioco IkaPop! | `https://ikagames.github.io/ikapop/` |
| Privacy IkaPop! | `https://ikagames.github.io/ikapop/privacy.html` |
| app-ads.txt | `https://ikagames.github.io/app-ads.txt` |

Per un nuovo gioco (es. IkaBlast), aggiungi una cartella `/ikablast/` con `index.html` e `privacy.html`, poi linkala dall'hub in root.

## Pubblicazione

1. Push su `main` nel repository `ikagames/ikagames.github.io`.
2. Su GitHub: **Settings → Pages**, source branch `main`, cartella `/ (root)`.
3. Dopo qualche minuto il sito è online.

Verifica app-ads.txt:

```bash
curl -i https://ikagames.github.io/app-ads.txt
```

Corpo atteso:

```text
google.com, pub-8204656869502841, DIRECT, f08c47fec0942fa0
```
