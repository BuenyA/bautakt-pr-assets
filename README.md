# PR-Bilder

Nur Vorher/Nachher-Screenshots für PR-Beschreibungen von `bautakt-web` und
`bautakt-app`. Kein Code, keine Kundendaten (nur Testbetriebe, ohne Mailadressen).

- Ablage: `pr/<PR-Nummer oder Thema>/<datei>.png`
- Link im PR: `https://raw.githubusercontent.com/BuenyA/bautakt-pr-assets/main/pr/<ordner>/<datei>.png`
- Hochladen: `scripts/pr-assets-upload.sh` in `bautakt-web`, alle Bilder eines PRs in **einem** Commit.

Dieses Repo ist bewusst **nicht** mit Vercel verbunden. Bis 09.11.2026 lagen die Bilder im
Branch `pr-assets` von `bautakt-web`; dort löste jeder Commit zwei fehlschlagende
Vercel-Deploys aus.
