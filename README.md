# Scrivere un programma in Java che simuli un sistema di gestione di conti bancari. Il sistema deve permettere di effettuare le seguenti operazioni:

## Creazione di un conto bancario con un saldo iniziale.

## Deposito di una somma di denaro.

## Prelievo di una somma di denaro.

## Visualizzazione del saldo corrente.

# Requisiti:

Creare una classe ContoBancario con gli attributi saldo e numeroConto.

Implementare i metodi deposita(double importo) e preleva(double importo), dove:

deposita aumenta il saldo di una data somma.

preleva riduce il saldo, ma deve lanciare un'eccezione personalizzata SaldoInsufficienteException se il saldo non è sufficiente.

Creare un'eccezione personalizzata SaldoInsufficienteException, che estenda Exception, con un costruttore che accetti un messaggio di errore.

Implementare un metodo visualizzaSaldo() che restituisca il saldo attuale.

Scrivere una classe Main che utilizzi la classe ContoBancario e gestisca le eccezioni con try-catch.

# Suggerimenti:

Assicurarsi di gestire le eccezioni in modo appropriato utilizzando blocchi try-catch.

Testare il programma con diversi scenari: deposito di denaro, prelievo valido, prelievo con saldo insufficiente.

Stampare messaggi chiari in caso di errore.

Buon lavoro! 🎲
