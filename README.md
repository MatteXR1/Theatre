# Biglietteria per Teatri di Torino

Questo progetto è un'applicazione di biglietteria per i teatri di Torino. È sviluppato utilizzando HTML, CSS e JavaScript per il frontend e Java Spring Framework per il backend. I dati vengono archiviati e gestiti utilizzando MySQL come database relazionale.

## Funzionalità Principali

- Visualizzazione degli spettacoli e delle loro repliche disponibili nei teatri di Torino.
- Prenotazione e acquisto dei biglietti per gli spettacoli selezionati.
- Gestione degli utenti e delle loro prenotazioni.

## Requisiti di Sistema

- Browser web moderno con supporto per HTML5 e JavaScript.
- Java Development Kit (JDK) 8 o versioni successive.
- Maven per il build del progetto Java.
- MySQL Server per l'archiviazione dei dati.

## Installazione e Avvio

1. Clona il repository:

    ```bash
    git clone <url_del_repository>
    ```

2. Backend (Java Spring):
   - Naviga nella cartella del backend:

     ```bash
     cd backend
     ```

   - Configura il database MySQL modificando le informazioni di connessione nel file `application.properties` nella cartella `src/main/resources`.

   - Esegui il build del progetto:

     ```bash
     mvn clean install
     ```

   - Avvia il server:

     ```bash
     java -jar target/nome_del_file.jar
     ```

3. Frontend (HTML/CSS/JavaScript):
   - Naviga nella cartella del frontend:

     ```bash
     cd frontend
     ```

   - Apri il file `index.html` nel tuo browser web.

4. L'applicazione sarà disponibile per l'utilizzo.

## Configurazione del Database MySQL

1. Assicurati di avere MySQL Server installato sul tuo sistema.
2. Crea un nuovo database per l'applicazione utilizzando il comando SQL e eseguire lo script di dump fornito:

    ```sql
    CREATE DATABASE nome_del_database;
    ```

3. Modifica le informazioni di connessione nel file `application.properties` nel backend per collegare l'applicazione al tuo database MySQL.

## Utilizzo

1. Accedi all'applicazione tramite il browser web.
2. Visualizza gli spettacoli disponibili nei teatri di Torino.
3. Seleziona uno spettacolo e prenota/acquista i biglietti desiderati.
4. Gestisci le prenotazioni e gli utenti attraverso le funzionalità messe a disposizione dall'applicazione.
