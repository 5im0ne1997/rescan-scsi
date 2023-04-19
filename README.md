# SCRIPT PER RESCAN DEGLI SCSI A CALDO

Il seguente script permette di eseguire il rescan dei dischi, sia nuovi che già presenti, senza riavviare la VM.

Quando viene aggiunto un disco nuovo, oppure si espande uno esistente, il sistema operativo potrebbe non vedere la modifica.

Copiare il contenuto del file ed eseguiro.

```
vi rescan_scsi.sh
chmod +x rescan_scsi.sh
./rescan_scsi.sh
```