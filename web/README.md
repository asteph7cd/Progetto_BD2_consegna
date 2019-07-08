## Web
In questa sottocartella sono presenti i programmi per avviare il server web.
Per far funzionare i comandi presentati di seguito è necessario posizionarsi in questa cartella:
```bash
	cd web/
```

Per avviare il server basta eseguire il comando 
```bash
	python index.py
```

Fatto questo dal browser si può accedere alla pagina del motore di ricerca all'indirizzo 0.0.0.0:8080.
Se si vuole cambiare la porta basta aggiungere il numero della porta desiderata nel comando precedente.
Per esempio:
```bash
	python index.py 8000
```
In questo modo si utilizza la porta 8000

### Nota:
Si assume che ci sia un indice raggiungibile con ../indice_stop3.
Conviene essere connessi ad internet, in modo da poter utilizzare alcuni css e script, altrimenti si possono verificare rallentamenti nel caricamento delle pagine.
