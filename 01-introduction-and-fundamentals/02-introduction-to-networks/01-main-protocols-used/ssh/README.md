# SSH
SSH, acronimo di **Secure Shell**, offre la possibilità di creare un collegamento client-server per l'amministrazione di elaboratori da remoto tramite una connessione criptata con un'[autenticazione a chiave pubblica/privata](/01-introduction-and-fundamentals/03-encryption/README.md). La sicurezza della comunicazione in SSH è assicurata grazie alla realizzazione di un canale criptato **TLS/SSL** che permette di proteggere da intercettazioni i dati scambiati tra client e server sulla porta 22.

Uno dei Software più utilizzati per connettersi a un Server tramite SSH è [PuTTY](https://www.putty.org/). In alternativa ci si può collegare tramite Shell.

## Shell
Per connettersi a un elaboratore tramite SSH basta eseguire il seguente comando, avendo cura di inserire i dati corretti (porta, IP e user) del server:
```ssh <user>@<ip> -p <port>```
Se il servizio è in ascolto sulla porta 22 (default) non serve specificare `-p <port>`. 
Una volta stabilita la connessione sarà possibile eseguire comandi direttamente nel server dal nostro computer.