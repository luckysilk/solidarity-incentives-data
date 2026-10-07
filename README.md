# Dati aggregati dello studio sugli incentivi

Questo pacchetto contiene soltanto statistiche aggregate dello studio *Can Solidarity Motivate? Comparing Competitive, Team, and Charitable Incentives*.

Non contiene record individuali, identificativi dei partecipanti, chiavi di corrispondenza, eta individuali, sezioni di classe, sequenze individuali delle prove o risposte individuali al questionario.

## File

- `dati_aggregati/sample_summary.csv`: numerosita e caratteristiche aggregate del campione completo e dei pannelli bilanciati usati nei modelli principali.
- `dati_aggregati/performance_summary.csv`: media e deviazione standard delle prestazioni per compito e condizione, sui pannelli bilanciati.
- `dati_aggregati/subjective_comparisons.csv`: confronti soggettivi Individual/Solidarity e beneficiario del premio, corrispondenti alla Tabella 4.
- `DIZIONARIO.md`: definizioni e limiti dei dati.
- `MANIFEST.sha256`: impronte dei file inclusi per il controllo di integrita.

## Ambito e limiti

Le tabelle sono state calcolate dai dati utilizzati per l’articolo. I tre campioni non sono indipendenti: Running e Tower sono sottoinsiemi del campione completo. Le statistiche sulle prestazioni comprendono 95 persone per Running e 96 per Tower. Ogni persona contribuisce una volta a ciascuna condizione del proprio compito.

Per i confronti soggettivi, il denominatore include solo chi sceglie una delle due alternative confrontate. Le altre risposte e i mancanti sono esclusi da quel singolo confronto. I p-value sono quelli del test binomiale esatto bilaterale, senza correzione per confronti multipli.

Non sono diffuse tabelle per sottogruppi dettagliati, combinazioni individuali o valori estremi. Tutti i conteggi non nulli direttamente pubblicati sono almeno 10. Questa scelta e una misura tecnica di riduzione del rischio, non una certificazione di anonimato o una garanzia contro inferenze da altre fonti.

Questi aggregati permettono di esaminare statistiche descrittive e confronti soggettivi; non permettono di ristimare i modelli individuali, i test appaiati o le analisi con effetti fissi. La copia individuale deidentificata e la relativa chiave sono conservate separatamente e non fanno parte del pacchetto.

## Prima del deposito

La selezione tecnica dei file e completata. La pubblicazione resta subordinata alle condizioni dello studio e alla verifica del responsabile dei dati. Questo pacchetto non costituisce un’approvazione privacy e non e stato caricato online. La licenza di riutilizzo deve essere definita dai titolari dei diritti; non ne viene assegnata una automaticamente.

Per il repository usare esclusivamente i file di questo pacchetto. Non aggiungere la cartella di lavoro originale, archivi dei microdati, chiavi, backup o precedenti versioni del dataset. Il file `.gitignore` usa una lista esplicita dei soli file previsti; non protegge file gia presenti nella cronologia Git.
