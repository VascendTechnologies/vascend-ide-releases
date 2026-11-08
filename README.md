# Vascend IDE Releases

Download pubblici di Vascend IDE: qui non c'è codice sorgente. Tutto viene pubblicato dal workflow "Release Vascend IDE" del repository dell'IDE.

- `vascend-ide-<versione>`: installer per Windows (`VascendIDEUserSetup-x64-<versione>.exe`), macOS (`VascendIDE-darwin-<arch>-<versione>.dmg` / `.zip`) e Linux (`vascend-ide-<versione>-amd64.deb`, `VascendIDE-linux-x64-<versione>.tar.gz`).
- `vascend-ide-server-<versione>`: server remoto usato dalle connessioni WSL e SSH, `vascend-ide-server-<os>-<arch>-<commit>.tar.gz`. `<commit>` deve coincidere con quello del client.
- `feed`: manifest firmati (`<piattaforma>-stable.json` + `.sig`) da cui gli IDE installati si aggiornano da soli. Non vanno scaricati a mano.

Dopo la prima installazione non serve più scaricare nulla: l'IDE trova la versione nuova, la scarica, ne controlla firma e hash e chiede di riavviare.

La release `horizon-reh-1.131.0` è del periodo in cui l'IDE si chiamava Horizon IDE.
