# Horizon Releases

Archivi pubblici del server remoto di Horizon IDE (`horizon-reh`), scaricati dalle estensioni Horizon Remote WSL e SSH quando aprono una connessione.

Le release si chiamano `horizon-reh-<versione>` e contengono un archivio per sistema e architettura:

```
horizon-reh-<os>-<arch>-<commit>.tar.gz
```

`<commit>` è il commit di `product.json` dell'IDE, che deve coincidere con quello del client. Gli archivi sono pubblicati in automatico dal workflow "Release Horizon Remote Extension Host" del repository dell'IDE: qui non c'è codice sorgente.
