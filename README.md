# Script_entita_da_condividere

## IMPORTANTE: FAI UNA COPIA DEL FILE PER POTERLO USARE

## Occorrente:
File di autorizzazione per usare le API di Google, caricato in una cartella Drive di tua scelta.
Un file CSV con due colonne: "URL" e "Content". "URL" serve per capire a quale URL, appunto, appartiene il contenuto. "Content" per il contenuto da analizzare. Puoi ottenere questo file a partire da una scansione di Screaming Frog con estrazione personalizzata, o con il metodo di scraping che preferisci. Ricorda di caricare subito il file.
## Impostazioni:
Nel primo blocco di codice troverai tre campi da impostare:

- lang: È il parametro che si riferisce alla lingua. Usa un input di codice linguistico a due caratteri. L'italiano è "it", ed è preimpostato.
- file: È il percorso temporaneo del CSV da analizzare. Ti basterà impostare: {{nome_file}} + ".csv"
- auth_path: È il percorso del file di autorizzazione JSON delle API di Google Cloud, che dovrai aver preventivamente salvato in Google Drive. Copia il percorso del file ed inseriscilo dove richiesto.

## Come far funzionare lo script:
Dopo aver impostato quanto richiesto, ti basta far partire il codice così come indicato per ottenere i CSV di risultato. Otterrai diversi CSV, che dovrai combinare in un solo file per arrivare al risultato finale.

## Next Step:
Ci piacerebbe sapere cosa pensi che si possa migliorare di questo file, in modo da rendere il lavoro sempre più snello e veloce. Al momento, abbiamo in cantiere:

Implementazione dello scraping via Trafilatura per essere indipendenti dal CSV, e passare direttamente un DataFrame alle API. Questo per snellire il processo e non uscire nemmeno dal Colab, anche in fase di preparazione dei dati.
