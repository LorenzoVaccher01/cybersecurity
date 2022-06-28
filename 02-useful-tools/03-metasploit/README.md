# Metasploit
Metasploit Framework (MSF) è un Software Open Source scritto in Ruby che fornisce informazioni riguardanti eventuali vulnerabilità di un Server e ne semplifica le operazioni di penetration testing. 

## Installazione
In ParrotOS questo strumenti di analisi dovrebbe essere già installato. Se così non fosse, possiamo risolvere questo problema digitando i seguenti comandi:
```
sudo apt update && sudo apt install metasploit-framework
```

## Utilizzo
Per poter utilizzare MSF dobbiamo digitare `msfconsole` che avvierà il terminale grazie al quale saremo in grado di sfruttare tutte le funzione di Metasploit.

### Enumeration
Per prima cosa dobbiamo capire che servizi il nostro Target sta offrendo. Per portare a termine questa operazione dobbiamo fare un'analisi con [Nmap](../01-nmap/README.md).