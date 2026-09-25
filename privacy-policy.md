# Informativa sul trattamento dei dati personali
## Bot Discord "Leggenda Stargonauta" e Gestionale Stargonauti

**Ultimo aggiornamento: 24 settembre 2026**

Informativa resa ai sensi degli artt. 13 e 14 del Regolamento (UE) 2016/679 ("GDPR") e del D.Lgs. 30 giugno 2003, n. 196 ("Codice Privacy"), come modificato dal D.Lgs. 10 agosto 2018, n. 101.

---

## 1. Titolare del trattamento

Il Titolare del trattamento è lo **sviluppatore e gestore del bot "Leggenda Stargonauta"** e del **Gestionale Stargonauti**, Founder della community Discord "Stargonauti" (di seguito, il "Server").

**Contatti del Titolare:**
- E-mail: **stargonauti@gmail.com**
- Discord: apertura di un ticket di tipo "💬 Staff" dal canale di supporto del Server

L'identità completa del Titolare è comunicata a chiunque ne faccia richiesta per l'esercizio dei diritti di cui al § 11 o per altre ragioni legittime, scrivendo all'indirizzo sopra indicato.

Il Titolare non ha nominato un Responsabile della Protezione dei Dati (DPO), non ricorrendone i presupposti di cui all'art. 37 GDPR.

---

## 2. Ambito di applicazione

La presente informativa riguarda due strumenti privati, gestiti direttamente dal Titolare e non distribuiti al pubblico:

- il **bot Discord "Leggenda Stargonauta"** (di seguito, il "Bot"), installato e operante unicamente sul Server;
- il **Gestionale Stargonauti** (di seguito, il "Gestionale"), pannello web riservato allo staff del Server, collegato al Bot, che utilizza la stessa applicazione Discord del Bot.

L'uso di Discord è regolato dai termini e dall'informativa privacy di Discord (https://discord.com/privacy), che agisce come titolare autonomo per i dati trattati dalla propria piattaforma. Il Titolare non ha accesso a dati di Discord ulteriori rispetto a quelli resi disponibili tramite le API ufficiali.

---

## 3. Dati trattati dal Bot

### 3.1 Registro membri
Per ogni membro registrato nella community il Bot conserva: ID utente Discord, username (aggiornato automaticamente una volta al giorno), data di ingresso nella community, ruolo nella community (Founder, Admin, Community Manager, Staff, Membro) e le statistiche di attività di cui al § 3.2.

Sulla base di questi dati il Bot pubblica, in un canale dedicato del Server, una **scheda per ciascun membro** con: username, immagine del profilo (avatar), ruolo, data di ingresso, anzianità, tempo totale trascorso nei canali vocali e numero totale di messaggi inviati. La scheda è visibile agli utenti che hanno accesso a quel canale.

### 3.2 Statistiche di attività
Per i soli membri registrati, il Bot rileva automaticamente:

| Dato | Come viene rilevato |
|---|---|
| Numero di messaggi inviati nel Server (settimanale e totale) | Il Bot riceve da Discord i messaggi inviati nel Server e ne registra **solo il conteggio**. **Il contenuto dei messaggi non viene conservato** per questa finalità |
| Minuti trascorsi nei canali vocali (settimanali e totali) | Il Bot registra l'ingresso e l'uscita dai canali vocali (ID del canale e orario di inizio della sessione). Il tempo nel canale AFK non viene conteggiato. **Il Bot non ascolta né registra l'audio** |
| Sessione vocale in corso | ID del canale e orario di inizio, salvati periodicamente per non perdere il conteggio in caso di riavvio del Bot |

### 3.3 Report settimanale e ruoli del podio vocale
Ogni lunedì il Bot pubblica in un canale del Server:
- la **classifica settimanale** dei membri attivi, con username, tempo in vocale e numero di messaggi della settimana conclusa, suddivisi in fasce;
- statistiche aggregate del Server;
- il membro con più tempo in vocale e il membro con più messaggi della settimana.

Contestualmente assegna ai **tre membri con più tempo in vocale** della settimana dei ruoli temporanei ("Capitano", "Tenente" e "Mozzo della Vocale"), che vengono tolti e riassegnati ogni settimana. I contatori settimanali ripartono da zero; i valori della settimana conclusa restano salvati fino al rollover successivo.

### 3.4 Accoglienza e verifica dei nuovi utenti
Quando un utente entra nel Server, il Bot pubblica nel canale di verifica un messaggio di benvenuto che lo menziona e ne mostra l'avatar. Il messaggio viene cancellato automaticamente dopo l'interazione o, in assenza di interazione, dopo 5 minuti. Se l'utente risulta già nel registro, il Bot gli riassegna il ruolo di membro.

### 3.5 Ticket di ingresso (richiesta di adesione)
Se l'utente non risulta nel registro, il Bot:
- crea un canale privato il cui nome contiene lo username dell'utente, visibile all'utente, al Bot e agli amministratori del Server;
- invia all'utente un messaggio privato (DM) con il collegamento al canale;
- lo invita a rispondere a domande di presentazione (nome o nickname preferito, giochi praticati, come ha conosciuto la community, eventuali conoscenze nella community, livello di competitività);
- **comunica al Gestionale** l'apertura del ticket (ID e username dell'utente, nome visualizzato, avatar, ID e nome del canale, data di apertura).

Lo staff legge i messaggi del ticket e risponde **tramite il Gestionale** (§ 4). La decisione (approvazione, rifiuto o chiusura, con eventuale nota o motivo) può essere presa dal Gestionale o dai pulsanti nel canale ed è comunicata all'utente tramite DM. In caso di approvazione l'utente viene aggiunto al registro membri (§ 3.1).

Prima di eliminare il canale, il Bot **invia al Gestionale la trascrizione** del ticket: per ciascun messaggio scritto da persone (non dal Bot), data e ora, username dell'autore, testo e **nomi** dei file allegati (i file non vengono copiati), oltre all'esito, a chi ha deciso e all'eventuale motivo. La trascrizione resta consultabile dallo staff nel Gestionale (§ 4.2).

### 3.6 Ticket di supporto (Segnalazione, Bug Report, Staff)
Quando un utente apre un ticket di supporto, il Bot crea un canale privato numerato, visibile all'utente, al Bot e allo staff, e conserva: ID dell'utente, tipo di ticket, numero progressivo, ID del canale, data e ora di apertura.

Nel ticket l'utente può scrivere messaggi e allegare file. Nei ticket di tipo "Segnalazione" possono essere riportati dati relativi a **terzi** (l'utente segnalato e i fatti che lo riguardano); la presente informativa vale anche nei loro confronti.

Alla chiusura, effettuabile solo dallo staff, il Bot blocca la scrittura nel canale, genera una **trascrizione testuale (.txt)** (numero e tipo del ticket; username e ID di chi lo ha aperto; username dello staff intervenuto; chi lo ha chiuso; date di apertura e chiusura; per ciascun messaggio data, ora, autore, testo e nomi degli allegati), la pubblica in un canale di archivio riservato allo staff, ne salva una copia sul computer che esegue il Bot ed elimina il canale.

### 3.7 Feedback
Alla chiusura di un ticket di supporto, **solo** l'utente che lo ha aperto può, facoltativamente, lasciare una valutazione da 1 a 5 stelle e un commento. Il Bot pubblica in un canale riservato allo staff: numero e tipo del ticket, menzione e ID dell'utente, valutazione e commento.

### 3.8 Canali vocali temporanei
Quando un utente entra nel canale vocale designato, il Bot crea un canale vocale temporaneo, vi sposta l'utente e conserva l'ID di chi lo ha creato e l'orario di creazione, per consentirgli di rinominarlo e di impostarne il limite di utenti. Canale e dati vengono eliminati quando il canale si svuota.

### 3.9 Dati tecnici
Il Bot conserva gli ID di canali, ruoli e messaggi necessari al proprio funzionamento. Il registro di sistema del Bot può riportare lo username dell'utente che usa un comando o entra nel Server, gli errori di funzionamento e i casi in cui non è stato possibile inviare un DM.

---

## 4. Dati trattati dal Gestionale

### 4.1 Chi vi accede
Il Gestionale è accessibile **solo** ai membri dello staff con il ruolo di Community Manager nel Server e al Titolare. L'accesso avviene con il login di Discord (OAuth2, autorizzazione "identify"), che fornisce ID, username, nome visualizzato e avatar dell'account; nessuna password viene raccolta.

Per mantenere l'accesso il Gestionale usa un **cookie tecnico di sessione** firmato (durata 7 giorni) e un cookie tecnico temporaneo per la sicurezza del login (10 minuti). Nel browser dello staff sono salvate solo preferenze di visualizzazione (tema, server selezionato, chat già lette). Non vengono usati cookie di profilazione né strumenti di analisi o pubblicità.

### 4.2 Dati mostrati e conservati
Il Gestionale **mostra allo staff**, leggendoli in tempo reale da Discord, l'elenco dei membri del Server con username, nome visualizzato, soprannome, avatar, data di ingresso nel Server e ruoli Discord.

Il Gestionale **conserva**:

| Dato | Contenuto |
|---|---|
| Schede staff | Per singolo utente: uno stato interno (membro, in prova, inattivo, da espellere), una nota libera scritta dallo staff (massimo 500 caratteri) e le sezioni della community a cui è associato (es. Arc Raiders, Sea of Thieves) |
| Anagrafica | Elenco delle persone registrate dallo staff: ID, username, nome visualizzato, avatar, data di inserimento e chi le ha inserite. Può includere persone che non sono (più) nel Server |
| Ticket di ingresso aperti | I dati comunicati dal Bot (§ 3.5) e quale membro dello staff ha scritto ciascun messaggio inviato dal Gestionale |
| Archivio candidature | Le trascrizioni dei ticket di ingresso chiusi (§ 3.5), con esito, data, chi ha deciso ed eventuale motivo |
| Registro attività dello staff | Ogni azione compiuta dallo staff: chi, quando, su quali utenti e quale azione (ruoli, stato, note, espulsioni, messaggi, decisioni sulle candidature). Per messaggi privati e risposte nei ticket il registro conserva un estratto del testo (fino a 120 caratteri) |
| Ordini al Bot | Le richieste di approvazione, rifiuto o chiusura inviate al Bot, con nota e autore |

Il testo dei ticket di ingresso ancora aperti **non** viene copiato nel Gestionale: viene letto da Discord quando lo staff apre la conversazione.

### 4.3 Azioni possibili dal Gestionale
Dal Gestionale lo staff può, per il tramite del Bot: assegnare e togliere ruoli, espellere utenti dal Server, inviare messaggi privati, rispondere nei ticket di ingresso e decidere sulle richieste di adesione. I **ruoli di comando** possono essere assegnati solo dal Titolare.

### 4.4 Modulo di candidatura online
Il Gestionale include un modulo di candidatura online, **attualmente disattivato**. Se verrà attivato, la presente informativa sarà aggiornata prima dell'attivazione con l'indicazione dei dati richiesti.

---

## 5. Dati non raccolti
Né il Bot né il Gestionale raccolgono indirizzi e-mail, numeri di telefono, password o credenziali, dati di pagamento, dati di geolocalizzazione o registrazioni audio. Il testo dei messaggi scritti nel Server viene conservato **esclusivamente** per i ticket (§ 3.5, 3.6).

**Si invita a non inserire nei ticket dati particolari ai sensi dell'art. 9 GDPR** (salute, orientamento sessuale, opinioni politiche, convinzioni religiose, ecc.) o dati relativi a reati, salvo quanto strettamente necessario per una segnalazione. **Lo staff si impegna a non annotare dati di questo tipo nelle note del Gestionale.**

---

## 6. Finalità e basi giuridiche

| Finalità | Base giuridica |
|---|---|
| Registro membri e ruoli (§ 3.1) | Legittimo interesse del Titolare all'organizzazione della community (art. 6, par. 1, lett. f GDPR) |
| Statistiche di attività, report settimanale e ruoli del podio (§ 3.2, 3.3) | Legittimo interesse del Titolare a valorizzare la partecipazione alla community (art. 6, par. 1, lett. f GDPR) |
| Accoglienza e valutazione delle richieste di adesione, incluse trascrizione e archivio (§ 3.4, 3.5, 4.2) | Misure precontrattuali su richiesta dell'interessato (art. 6, par. 1, lett. b GDPR) e legittimo interesse a documentare le decisioni (art. 6, par. 1, lett. f GDPR) |
| Segnalazioni, bug report, richieste allo staff; moderazione e sicurezza (§ 3.6) | Legittimo interesse del Titolare alla sicurezza della community, anche in adempimento degli obblighi della Discord Developer Policy (art. 6, par. 1, lett. f GDPR) |
| Feedback (§ 3.7) | Legittimo interesse al miglioramento del supporto; conferimento facoltativo (art. 6, par. 1, lett. f GDPR) |
| Canali vocali temporanei (§ 3.8) | Esecuzione della funzione richiesta dall'utente (art. 6, par. 1, lett. b GDPR) |
| Gestione della community tramite il Gestionale, incluso il registro delle azioni dello staff (§ 4) | Legittimo interesse del Titolare a organizzare la community e a rendere tracciabili e verificabili le azioni dello staff (art. 6, par. 1, lett. f GDPR) |
| Funzionamento tecnico, sicurezza, backup (§ 3.9, 4.1) | Legittimo interesse del Titolare (art. 6, par. 1, lett. f GDPR) |

Il Titolare ritiene che tali interessi non prevalgano sui diritti e sulle libertà degli interessati, in considerazione della natura dei dati (conteggi e tempi di attività, non contenuti delle conversazioni, salvo i ticket), del contesto (partecipazione volontaria a una community privata) e delle misure di cui al § 10. L'interessato può in ogni momento opporsi al trattamento ai sensi dell'art. 21 GDPR (§ 11).

L'assegnazione automatica dei ruoli del podio vocale non produce effetti giuridici né incide in modo analogo significativamente sull'interessato ai sensi dell'art. 22 GDPR. L'approvazione o il rifiuto delle richieste di adesione e ogni provvedimento disciplinare sono **sempre decisi da persone dello staff**.

Il Titolare **non** utilizza i dati per profilazione commerciale, pubblicità o marketing, **non** li vende né li cede a terzi e **non** li utilizza per addestrare modelli di intelligenza artificiale.

---

## 7. Destinatari e accesso ai dati

I dati possono essere conosciuti esclusivamente da:
- il **Titolare**;
- i **membri dello staff**, per le sole finalità di gestione della community e del supporto, limitatamente ai canali e alle funzioni a cui hanno accesso;
- gli **utenti del Server** che hanno accesso ai canali in cui sono pubblicati schede e report (§ 3.1, 3.3);
- **Netlify, Inc.**, fornitore del servizio che ospita il Gestionale e il relativo archivio dati, in qualità di responsabile del trattamento (art. 28 GDPR);
- **Discord**, in quanto piattaforma su cui i dati sono pubblicati, secondo la propria informativa;
- **autorità competenti**, ove richiesto dalla legge.

Il Bot è eseguito su un computer nella disponibilità esclusiva del Titolare; i relativi file non sono affidati a fornitori esterni.

---

## 8. Trasferimenti extra UE

Netlify, Inc. ha sede negli Stati Uniti: i dati del Gestionale possono quindi essere trattati al di fuori dello Spazio economico europeo. Il trattamento da parte di Netlify è regolato dal suo Data Processing Agreement, che prevede le clausole contrattuali standard approvate dalla Commissione europea (Decisione di esecuzione (UE) 2021/914). I dati pubblicati su Discord sono trattati secondo l'informativa di Discord.

---

## 9. Periodo di conservazione

| Dato | Conservazione |
|---|---|
| Registro membri e statistiche di attività (§ 3.1, 3.2) | Per la durata della partecipazione alla community e fino alla rimozione dal registro; in ogni caso non oltre **5 anni** dall'uscita dell'utente dal Server |
| Sessione vocale in corso | Fino al termine della sessione |
| Contatori della settimana conclusa (§ 3.3) | Fino al rollover della settimana successiva |
| Copie di backup del registro | **7 giorni**, poi eliminate automaticamente |
| Messaggio di benvenuto (§ 3.4) | Al più tardi 5 minuti |
| Canale del ticket di ingresso (§ 3.5) | Eliminato pochi secondi dopo la decisione o la chiusura; i DM inviati dal Bot restano nella conversazione privata dell'utente |
| Archivio candidature nel Gestionale (§ 3.5, 4.2) | **5 anni** dalla decisione |
| Trascrizioni dei ticket di supporto (§ 3.6) | **5 anni** dalla chiusura |
| Feedback (§ 3.7) e report settimanali (§ 3.3) | **5 anni** dalla pubblicazione |
| Dati dei canali vocali temporanei (§ 3.8) | Fino all'eliminazione del canale |
| Schede staff e anagrafica del Gestionale (§ 4.2) | Fino alla cancellazione da parte dello staff; in ogni caso non oltre **5 anni** dall'uscita dell'utente dal Server |
| Registro attività dello staff (§ 4.2) | **5 anni** dalla registrazione dell'azione |
| Ordini al Bot (§ 4.2) | 7 giorni dall'esecuzione |
| Cookie di sessione del Gestionale (§ 4.1) | 7 giorni |
| Registro di sistema (§ 3.9) | Per il tempo necessario alla risoluzione dei problemi tecnici |

Il periodo di 5 anni corrisponde al termine di prescrizione del diritto al risarcimento del danno da fatto illecito (art. 2947 c.c.) ed è necessario a documentare le decisioni di moderazione e di ammissione in caso di contestazioni. Oltre tale termine i dati sono conservati solo se necessari per un procedimento in corso o su richiesta di un'autorità.

Alla cessazione definitiva del Bot e del Gestionale, tutti i dati da essi conservati saranno eliminati, in conformità ai Termini per sviluppatori di Discord.

---

## 10. Misure di sicurezza

Il Titolare adotta misure tecniche e organizzative adeguate alla natura dei dati, tra cui:
- canali dei ticket visibili solo agli interessati, al Bot e allo staff o agli amministratori;
- accesso al Gestionale solo tramite login Discord e solo per il ruolo di Community Manager e il Titolare, con verifica dei permessi a ogni richiesta;
- ruoli di comando assegnabili solo dal Titolare;
- registro di tutte le azioni dello staff nel Gestionale;
- comunicazione tra Bot e Gestionale protetta da una chiave segreta, su connessione cifrata (HTTPS);
- credenziali di Bot e Gestionale non accessibili pubblicamente;
- computer che esegue il Bot nella disponibilità esclusiva del Titolare;
- backup periodici con eliminazione automatica delle copie più vecchie di 7 giorni.

In caso di violazione dei dati personali (data breach), il Titolare procederà alle notifiche previste dagli artt. 33 e 34 GDPR e informerà Discord secondo quanto previsto dai Termini per sviluppatori di Discord.

---

## 11. Diritti dell'interessato

L'interessato ha diritto, nei casi e nei limiti previsti dal GDPR, di:
- **accesso** ai propri dati (art. 15), incluse eventuali note e stati annotati dallo staff nel Gestionale;
- **rettifica** dei dati inesatti (art. 16);
- **cancellazione** (art. 17);
- **limitazione** del trattamento (art. 18);
- **portabilità** dei dati (art. 20);
- **opposizione** al trattamento fondato sul legittimo interesse (art. 21), in particolare al conteggio della propria attività e alla propria inclusione nei report.

Le richieste possono essere inviate ai contatti di cui al § 1. Il Titolare risponde entro un mese dal ricevimento, prorogabile di due mesi nei casi previsti dall'art. 12, par. 3 GDPR. Per verificare che la richiesta provenga effettivamente dall'interessato, il Titolare potrà chiedere di inviarla dall'account Discord a cui i dati si riferiscono.

La cancellazione di dati contenuti in trascrizioni, candidature o nel registro delle azioni dello staff potrà essere differita ove la loro conservazione sia necessaria per l'accertamento, l'esercizio o la difesa di un diritto (art. 17, par. 3, lett. e GDPR).

L'interessato ha inoltre diritto di proporre reclamo al **Garante per la protezione dei dati personali** (Piazza Venezia 11, 00187 Roma — www.garanteprivacy.it — protocollo@gpdp.it) ai sensi dell'art. 77 GDPR.

---

## 12. Minori

Discord consente l'uso della piattaforma solo a chi ha almeno 13 anni o l'età minima prevista dalla legge del proprio Paese. Il Server, il Bot e il Gestionale sono destinati a utenti che abbiano compiuto almeno **14 anni** (art. 2-quinquies Codice Privacy). Qualora risulti che siano stati trattati dati di un minore di 14 anni, il genitore o il minore stesso possono chiederne la cancellazione ai contatti di cui al § 1.

---

## 13. Natura del conferimento

Il conferimento dei dati di cui ai §§ 3.1, 3.4, 3.5 e 3.6 è necessario per partecipare alla community e utilizzare le funzioni di supporto. Il conferimento del feedback (§ 3.7) è facoltativo. Per il conteggio dell'attività vale il diritto di opposizione di cui al § 11.

---

## 14. Modifiche

Il Titolare può modificare la presente informativa, in particolare in caso di modifiche alle funzionalità del Bot o del Gestionale. La versione aggiornata è pubblicata a questo indirizzo con la data di ultimo aggiornamento. Le modifiche sostanziali saranno comunicate nel Server.

---

*Leggenda Stargonauta e il Gestionale Stargonauti sono strumenti indipendenti e non sono affiliati, sponsorizzati o approvati da Discord Inc.*
