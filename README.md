# VRAM_SW_DOC_2020
Repository per i documenti del progetto didattico SWE del gruppo VRAM SOFTWARE

## Pseudo norme di progetto - indicazioni per la documentazinone

### Uso dei template
Aggiornare il template solo per aggiungere funzionalità comuni a tutti i documenti.

Se serve creare un nuovo documento copiare il contenuto della cartella template e costruire su questa base senza quindi modificare il template originario.

### Generali

Prima di fare qualsiasi modifica al codice coordinarsi con il resto del gruppo e creare e/o assegnarsi una Issue, al fine di limitare al minimo il lavoro in doppio. 

Se vi vengono in mente più modifiche da fare scrivete pure più Issue ed incaricatevi solo quelle che riuscite a gestire in breve tempo, lasciando le altre al resto del gruppo così da lavorare in parallelo.

### Scrittura del codice
E' buona norma seguire le indicazioni delle prime lezioni di TOS: adottiamo feature-branch come workflow di lavoro.

### Commit
Cercare di tenerli il più possibile "atomici" e collegarli sempre al codice della Issue. Atomici significa che ogni commit dovrebbe registrare solo un tipo di modifica, non una lista. Ag ogni Issue possono corrispondere più commit e viceversa.

[Questa](https://chris.beams.io/posts/git-commit/) è secondo me una buona linea guida su come scrivere messaggi di commit efficaci.

### Branch e Merge di feature-flow
Idealmente ogni Issue va sviluppata su un suo branch dedicato. Ogni branch può avere (e normalmente ha) più commit al suo interno. Effettuare il merge del branch sul ramo principale tramite pull request e solo dopo aver controllato di non aver introdotto bug che possano minare il lavoro degli altri.

Una volta effettuato il merge del branch sul trunk principale eliminare il branch temporaneo su cui si era lavorato.

### Pull request
Chi crea le pull request non le può anche approvare, ma dovrà assegnarle al verificatore perché vengano approvate. Se questo comportasse ritardi troppo importanti prevederemo delle eccezioni alla regola.
