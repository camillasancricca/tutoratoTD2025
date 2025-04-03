# Scopo del tutorato
- Approfondire l'utilizzo di MySQL e MySQL Workbench per la progettazione e la realizzazione di un database
- Ottenere fino a 1 punto aggiuntivo sul voto finale dell'esame

# Calendario e programma

| Scaglione   | Incontri                                                   | Tutor             | Link |
|:------------|:-----------------------------------------------------------|:------------------|:-----|
| Cappiello   | 15/05/2024 10.00-13.00 <br /> 22/05/2024 10.00-12.00 | Camilla Sancricca | [Webex](https://politecnicomilano.webex.com/meet/camilla.sancricca)  |
| Plebani     | 10/05/2024 14.00-17.00 <br /> 17/05/2024 14.00-16.00 | Carlo Bono        | [Webex](https://politecnicomilano.webex.com/meet/carloalberto.bono)  |
| Salnitri    | 14/05/2024 10.00-13.00 <br /> 21/05/2024 10.00-12.00 | Carlo Bono        | [Webex](https://politecnicomilano.webex.com/meet/carloalberto.bono)  |
| Vitali      | 17/05/2024 10.00-13.00 <br /> 24/05/2024 10.00-12.00 | Camilla Sancricca | [Webex](https://politecnicomilano.webex.com/meet/camilla.sancricca)  |

Secondo le indicazioni delle Scuole, valide per tutti i tutorati:
- Gli incontri si svolgeranno in modalità *a distanza*
- Le presenze verranno rilevate nei primi 15 minuti a partire dagli orari indicati; si raccomanda pertanto la *massima puntualità*.

Durante il primo incontro (3 ore):
- Verranno presentati gli strumenti utilizzati
- Verranno svolti alcuni esercizi guidati sulla creazione di database e il caricamento dei dati

Durante il secondo incontro (2 ore):
- Gli studenti dovranno svolgere degli esercizi in autonomia

## Prerequisiti
Le attività di tutorato si svolgono usando due software gratuiti: MySQL e MySQL Workbench.

Gli studenti sono invitati a partecipare al primo incontro con i software già installati sul proprio pc.
A tale scopo vengono fornite le seguenti guide:
- [Videoguida](https://web.microsoftstream.com/video/a765fd50-3ae1-4193-b491-b2cf5fc43070) per installazione MySQL e MySQL Workbench su Windows
- [Guida ufficiale MySQL](https://dev.mysql.com/doc/refman/8.0/en/installing.html)
- [Guida ufficiale MySQL Workbench](https://dev.mysql.com/doc/workbench/en/wb-installing.html)

# Come si ottiene l'incremento di punteggio
E' previsto l'incremento massimo di 1 punto sul voto dell'esame, in funzione della valutazione dell'attività di tutorato, purché tutte le seguenti condizioni siano soddisfatte:
- Lo studente ha partecipato a entrambi gli incontri previsti per il proprio scaglione
- Lo studente ha inviato il materiale per la valutazione dell'attività, secondo le modalità indicate più sotto, e la valutazione è risultata positiva
- Lo studente ha realizzato il materiale in completa autonomia
- Il voto dell'esame è >= 18 prima dell'incremento

# In cosa consiste l'attività valutata
Saranno oggetto di valutazione:
- La creazione della struttura di database
- La scrittura delle query

Il giorno 10/05/2023 viene pubblicata su questa pagina la prima parte del testo dell'esercizio, che consiste nella descrizione di uno schema di tabelle. Gli studenti devono creare il database rispettando attentamente le specifiche indicate (nomi delle tabelle, tipi di dato, vincoli di integrità, ecc.).

Il giorno 17/05/2023 viene pubblicata su questa pagina la seconda parte del testo dell'esercizio, che consiste nella realizzazione di 5 interrogazioni. Viene anche pubblicato un file contenente i dati da importare nel database precedentemente creato. 

# Valutazione
Le query vengono valutate su un database MySQL con la stessa struttura di quello che è stato fornito agli studenti, ma con all'interno dati differenti. Per ciascuna query:
- Nel caso il risultato sia corretto, viene assegnato un incremento pari a 0,2 punti.
- Nel caso il risultato sia errato, non viene assegnato alcun incremento per la query.
- Nel caso l'esecuzione fallisca (ad esempio per un errore di sintassi), non viene assegnato alcun incremento.
- Nel caso in cui non vengano rispettate le modalità di consegna descritte sotto, non viene assegnato alcun incremento.

# Modalità di consegna
- La **deadline** per la consegna è fissata per le **23.59 del 02/06/2023**
- La consegna deve essere effettuata utilizzando la **cartella di consegna** che verrà predisposta sul corso **WeBeeP** di ciascuno scaglione. Non saranno considerate valide altre modalità di consegna (es. email).
- Non sono previste eccezioni a quanto indicato.

Materiale da consegnare:
- Ogni studente deve consegnare un unico file ZIP, nominato solamente con il proprio codice persona (es. `10765432.zip`, attenzione a NON inserire la matricola)
- All'interno del file ZIP devono essere presenti da 1 a 5 file SQL, chiamati rispettivamente `1.sql` - `2.sql` - ...,  corrispondenti alle 5 query
- Il file `1.sql` dovrà contenere la soluzione della prima query, analogamente per gli altri file
- Ogni file deve essere correttamente formattato secondo gli standard MySQL
- Ogni file deve poter essere eseguito indipendentemente dagli altri file (es. non si può utilizzare una VIEW creata in un altro file, ma ogni VIEW deve essere ridefinita all'interno di ogni file che la utilizza)

Si consiglia di provare ad eseguire le query in MySQL Workbench e, una volta soddisfatti della propria soluzione, esportare la query direttamente da Workbench (File -> SaveScriptAs).


# Plagio
Il tutorato non prevede lavori di gruppo. Ogni studente deve lavorare individualmente alla propria personale soluzione del problema. Ai fini della valutazione, gli studenti possono essere convocati, a campione o a giudizio dei tutor, per verificare l'effettiva paternità delle soluzioni inviate. Nel caso la verifica abbia esito negativo, verrà annullato l'incremento di voto assegnato e saranno presi adeguati provvedimenti.

# Materiali (DA AGGIORNARE)
- Prima parte dell'esercizio: [Descrizione delle tabelle](https://polimi365-my.sharepoint.com/:b:/g/personal/10021621_polimi_it/EYnna4Vb-LVNgSegYEnIxJ8BlgSHcr5on0eMlAO7tTP3ug?e=BNSA18)
- Seconda parte dell'esercizio: [Dati da importare](https://polimi365-my.sharepoint.com/:u:/g/personal/10021621_polimi_it/ET9u_D15AnVLn0yJ78erJjMBa5L0DfDIviuKO8EhV0sAkg?e=NstjjY) + [Interrogazioni](https://polimi365-my.sharepoint.com/:b:/g/personal/10021621_polimi_it/ERkjcnrHSOpNnzcqGswTjMgBB5n1A-FwwgzG4q8p-F1zDQ?e=jSgzif)
