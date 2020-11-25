<p align="center">
<img src="https://forthebadge.com/images/badges/made-with-javascript.svg"/>
  <img src="https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg"/>
  <img src="https://forthebadge.com/images/badges/built-with-love.svg"/><br></br>
    <b>AnAVIS</b>, progetto realizzato in <b>Node.js</b> per il corso di laurea <b>L-31</b> presso <b>Unicam</b>, <i>nell'anno accademico 2020/2021</i>, realizzato dallo studente <b>Matteo Carosi</b> per l'esame di <b>Programmazione Web App e Mobile</b>
<a href="https://www.unicam.it/">• Unicam</a>
<a href="https://it.wikipedia.org/wiki/Licenza_MIT">• Licenza</a>
</b></p>

## 📝 Panoramica e funzionalità di base


L’obiettivo principale dell’applicativo sviluppato è quello di permettere a persone di vendere e compare qualsiasi cosa.
Le funzionalità principali dell'applicativo e permettere la vendita o l’acquisto di un qualsiasi bene da parte di persone con pochi facili click, anche per persone meno esperte nel mondo della compra/vendita online.
Una persona prima di poter acquistare o vendere un prodotto, deve necessariamente effettuare l’iscrizione per il cosi detto sito. Se l’utente non vuole inscriversi, l’unica attività da lui consentita sarà la visualizzazione dei prodotti e dei relativi dettagli messi in vendita da altri utenti già registrati. 
Per quanto concerne la registrazione di nuovi utenti, essi dovranno farlo tramite un E-mail valida e una password da loro scelta. Una volta registrati potranno finalmente loggare all’interno dell’account.Nel caso di un eventuale perdita o dimenticanza della propria password di accesso, sarà possibile reimpostarla cliccando sopra l’apposito link “ Reset Password “ e inserendo il proprio indirizzo di posta elettronica verrà immediatamente invita un’Email con la procedura di ripristino. Un utente una volta autenticato può inserire l’annuncio di un proprio articolo o comprare un qualsiasi prodotto già messo in vendita da altri utente. Dopo l’eventuale vendita di un prodotto, la rimozione del medesimo sarà cura del ex proprietario rimuoverlo dallo shop. 

## 🧰 Tecnologie di base


Il lato frontend dell’applicativo è stato sviluppato in linguaggio di programmazione JavaScript e HTML mediante il framework Open Source Express Js.
 Per la persistenza dei dati e per quando concerne l'autenticazione degli utenti al servizio ho deciso di affidarmi al database NoSQL MongoDB, un software libero e open source.
Per essere sicuri che gli utenti possano usare la sessione solo se stanno lavorando con le visualizzazione giuste, cioè quelle fornite dall’applicazione, in modo che la sessione non sia disponibile su nessuna pagina falsa è stato un cosiddetto Token CSRF (Cross-site request forgery).
Per l’invio dell’email di avvenuta registrazione e per un eventuale ripristino della password, è stata presa come appoggio la piattaforma di comunicazione  SendGrid, che fornisce un servizio basato su cloud.
Per il caricamento di foto dei vari prodotti messi in vendita è stato usato un middleware node.js chiamato Multer. Invece per poter scaricare la fattura, rilasciata dopo l’effettuato pagamento di un prodotto, è stato usato PDFKitt, una libreria per la generazione di documenti PDF per Node.js.
Mentre per il pagamento dei prodotti in vendita è stato usato Strip un'infrastruttura software che permette a privati e aziende di inviare e ricevere pagamenti via internet.

## 🔭 Autore

•	Carosi Matteo
