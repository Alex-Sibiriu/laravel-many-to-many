# laravel-many-to-many

creiamo con Laravel il nostro sistema di gestione del nostro Portfolio di progetti, aggiungendo una relazione many to many.

## Sviluppo

-   creare la migration per la tabella `technologies`
-   creare il model `Technology`
-   creare la migration per la tabella pivot `project_technology`
-   aggiungere ai model Technology e Project i metodi per definire la relazione many to many
-   visualizzare nella pagina di dettaglio di un progetto le tecnologie utilizzate, se presenti
-   permettere all’utente di associare le tecnologie nella pagina di creazione e modifica di un progetto
-   gestire il salvataggio dell’associazione progetto-tecnologie con opportune regole di validazione

### Bonus:

Creare il seeder per la tabella pivot
