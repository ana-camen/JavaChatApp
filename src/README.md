# Java Chat App

Un proiect simplu tip client–server scris in Java, care demonstreaza concepte fundamentale de retele, thread‑uri si interfețe grafice cu Swing.

## Functionalitati

* Server TCP care accepta conexiuni multiple de la clienti.
* Broadcast: orice mesaj trimis de un client este distribuit tuturor clientilor conectati.
* Client cu interfata grafica (Swing) pentru trimiterea si primirea mesajelor.
* Comunicarea se face prin socket‑uri Java.

## Structura proiectului

```
com/ana/javachatapp
 ├── server
 │    ├── ChatServer.java
 │    └── ClientHandler.java
 └── client
      ├── ChatClient.java
      └── ChatClientGUI.java
```

## Cum rulezi proiectul

### 1. Porneste serverul

Compilați si rulati `ChatServer.java`. Acesta asculta pe portul 5000.

### 2. Porneste unul sau mai multi clienti

Rulati `ChatClientGUI.java` pentru a deschide fereastra aplicatiei de chat.

Puteti deschide oricate instante pentru a testa comunicarea reala intre clienti.

## Tehnologii folosite

* Java 8+
* Sockets (TCP)
* Threading
* Swing (GUI)

