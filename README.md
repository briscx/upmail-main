dotAcademy OTP Verification

Questo programma è stato creato come parte del corso dotAcademy per la verifica OTP (One Time Password).
Descrizione

Il programma è un'applicazione Flask che gestisce la verifica OTP per l'accesso. L'utente inserisce le credenziali di accesso e riceve una OTP generata casualmente tramite email. Successivamente, l'utente può inserire la OTP ricevuta per verificare l'accesso.
Funzionalità

    Pagina di accesso: L'utente può inserire le proprie credenziali per accedere al sistema.
    Generazione OTP: Dopo aver effettuato l'accesso con successo, viene generata una OTP casuale.
    Invio OTP via email: L'OTP generata viene inviata all'utente tramite email.
    Verifica OTP: L'utente può inserire la OTP ricevuta per verificare l'accesso.
    Accesso riuscito: Se l'OTP inserita è corretta, viene visualizzata una pagina di accesso riuscito.

Requisiti di sistema

    Python 3.7 o versioni successive
    Flask
    Flask-Mail

Installazione

    Clona il repository: git clone https://github.com/tuonome/progetto.git
    Entra nella directory del progetto: cd progetto
    Installa le dipendenze: pip install -r requirements.txt

Configurazione

Prima di eseguire il programma, è necessario configurare le seguenti variabili nell'applicazione:

    app.config['MAIL_SERVER']: Il server SMTP per l'invio delle email.
    app.config['MAIL_PORT']: La porta del server SMTP.
    app.config['MAIL_USERNAME']: L'indirizzo email utilizzato per l'invio delle email.
    app.config['MAIL_PASSWORD']: La password dell'indirizzo email utilizzato per l'invio delle email.

Utilizzo

    Esegui il programma: python app.py
    Accedi all'applicazione tramite il tuo browser all'indirizzo http://localhost:5000.
    Inserisci le credenziali di accesso corrette per ottenere la OTP.
    Controlla la tua casella di posta elettronica per la ricezione dell'email con la OTP.
    Inserisci la OTP ricevuta nell'apposito campo per verificare l'accesso.

Contributi

Sono benvenuti i contributi a questo progetto. Se desideri contribuire, segui questi passaggi:

    Forka il repository
    Crea un branch per la tua funzionalità: git checkout -b my-new-feature
    Esegui il commit delle modifiche: git commit -am 'Add some feature'
    Esegui il push del branch: git push origin my-new-feature
    Invia una pull request

Licenza

Questo progetto è concesso in licenza ai sensi dei termini della licenza MIT. Per ulteriori informazioni, consulta il file LICENSE.
Contatti

Per qualsiasi domanda o suggerimento, contattami all'indirizzo [email protected]
