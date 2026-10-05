# ikagames.github.io

Sito statico di **IkaPop!** (sviluppatore: ikagames), pubblicato con [GitHub Pages](https://pages.github.com/) all'indirizzo <https://ikagames.github.io>.

Contiene:

- `index.html` — vetrina del gioco e link allo store
- `privacy.html` — informativa privacy
- `app-ads.txt` — verifica AdMob / app-ads.txt
- `.nojekyll` — disabilita l'elaborazione Jekyll su GitHub Pages

## Pubblicazione

1. Push su `main` nel repository `ikagames/ikagames.github.io`.
2. Su GitHub: **Settings → Pages → Build and deployment**.
3. Source: **Deploy from a branch**, branch `main`, cartella `/ (root)`.
4. Dopo qualche minuto il sito è disponibile su <https://ikagames.github.io>.

Per verificare `app-ads.txt` dopo il deploy:

```bash
curl -i https://ikagames.github.io/app-ads.txt
```

La risposta deve essere `200` e il corpo deve essere esattamente:

```text
google.com, pub-8204656869502841, DIRECT, f08c47fec0942fa0
```
