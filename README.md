# Il nostro primo API - Strive Blog

- Sei responsabile della creazione di una serie di WebAPI per l'applicazione Strive Blog

- Oggi ti occuperai di creare e visualizzare gli autori dei blog

- Di seguito troverai come strutturare i tuoi documenti mongo e quali rotte creare

# Strive Blog - Struttura

    _id                         // generato da mongo
    nome                        // stringa
    cognome                     // stringa
    email                       // stringa
    data di nascita             // stringa
    avatar                      // stringa

# Strive Blog - Rotte

- GET/authors => ritorna la lista degli autori

- GET/authors/123 => ritorna il singolo autore

- POST/authors => crea un nuovo autore

# EXTRA (facoltativi, per ora)

- PUT/authors/123 => modifica l'autore con l'id associato

- DELETE/authors/123 => cancella l'autore con l'id associato

# Connessione del backend al frontend

- Se vuoi connettere il backend al frontend dovrai installare il pacchetto 'cors' con il comando: npm i cors

- Dovrai quindi importarlo con un import statement

- Puoi usare cors col seguente comando: server.use(cors())
