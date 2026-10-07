# Dizionario dei dati aggregati

## sample_summary.csv

Una riga per campione. `Sample`: Full = campione sperimentale completo; Running_FE e Tower_FE = pannelli bilanciati specifici per compito. `Participants` e il totale. `Male` e `Female` sono conteggi per sesso; `Third_year` e `Fourth_year` sono conteggi per anno di corso. I margini si riferiscono allo stesso campione e non vanno sommati fra dimensioni.

## performance_summary.csv

Una riga per compito e condizione. `Task`: Running o Tower. `Condition`: Baseline, Individual, Team, Solidarity. `Participants`: numero di persone con misura in quella condizione nel pannello bilanciato. `Mean`: media della misura osservata, non del miglioramento. `SD`: deviazione standard campionaria (denominatore n-1). `Unit`: seconds per Running; game_height_units per l’altezza massima Tower. Valori inferiori del tempo e superiori dell’altezza indicano prestazioni migliori. La precisione di visualizzazione e due decimali per Running e un decimale per Tower. Non sono inclusi minimi, massimi, dati individuali o sequenze.

## subjective_comparisons.csv

Una riga per confronto. `Item`: E3 pressione, E4 disponibilita a ripetere, E2 motivazione, E1 impegno, C8 beneficiario del premio. `Outcome`: descrizione. `Individual`: numero di scelte Individual. `Solidarity_or_charity`: numero di scelte Solidarity, oppure charity per C8. `Comparison_N`: somma dei due conteggi. `Solidarity_percent`: 100 per il secondo conteggio diviso il denominatore, arrotondato a un decimale. `Binomial_p_unadjusted`: test binomiale esatto bilaterale rispetto a probabilita 0.5, arrotondato a sei decimali. Non e un p-value corretto per molteplicita.

Non sono usati codici dei partecipanti. Tutti i numeri sono statistiche aggregate, non record sintetici o osservazioni individuali.
