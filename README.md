[README (1).md](https://github.com/user-attachments/files/21686280/README.1.md)
# Malware Quick Scanner (Python)

Uno script Python semplice per controllare la presenza di file sospetti in una cartella.

## Funzionalità
- Scansione di tutti i file modificati nelle ultime 24 ore
- Calcolo hash SHA256
- Verifica contro una lista di hash conosciuti di malware

## Utilizzo
1. Imposta `KNOWN_MALWARE_HASHES` con gli hash SHA256 sospetti
2. Esegui lo script con Python 3
3. Inserisci la cartella da scansionare quando richiesto

## Esecuzione
```bash
python scanner.py
```

## Avvertenza
Questo script **non è un antivirus completo**.
È uno strumento educativo o di supporto per controlli base.

## Licenza
MIT License
