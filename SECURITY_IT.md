# Politica di Sicurezza

## Life Tracker by Bonn

[![English Version](https://img.shields.io/badge/🇬🇧_English_Version-4A90E2?style=flat-square)](./SECURITY.md) &nbsp; [![README](https://img.shields.io/badge/📖_README-009246?style=flat-square)](./README.md)

---

## 🔒 Panoramica sulla Sicurezza

**Life Tracker** prende sul serio la sicurezza e la privacy. Questo documento descrive le nostre pratiche di sicurezza, come proteggiamo i tuoi dati e come segnalare vulnerabilità di sicurezza.

---

## 🛡️ Misure di Sicurezza

### Autenticazione

- **Firebase Authentication** — Sistema di autenticazione standard del settore
- **Verifica email** — Richiesta per l'attivazione dell'account
- **Archiviazione sicura delle password** — Le password sono hashate e mai salvate in chiaro
- **Gestione delle sessioni** — Scadenza automatica delle sessioni e gestione sicura dei token

### Protezione dei Dati

- **Crittografia in transito** — Tutti i dati sono trasmessi tramite HTTPS
- **Crittografia a riposo** — I dati archiviati in Firebase Firestore sono crittografati
- **Isolamento utente** — Ogni utente può accedere solo ai propri dati
- **Firestore Security Rules** — Regole avanzate impediscono accessi non autorizzati

### Infrastruttura

- **Firebase Hosting** — Hosting sicuro e scalabile con certificati SSL automatici
- **Cloud Functions** — La logica backend viene eseguita in ambienti isolati e sicuri
- **Data center europei** — Dati archiviati in Europa (regione: europe-west1)
- **Aggiornamenti regolari** — Dipendenze e librerie sono mantenute aggiornate

### Sicurezza dell'Applicazione

- **Validazione degli input** — Tutti gli input utente sono validati sia lato client che server
- **Prevenzione XSS** — Sanitizzazione HTML per prevenire attacchi cross-site scripting
- **Protezione CSRF** — Firebase Authentication fornisce protezione CSRF integrata
- **Rate limiting** — Protezione contro attacchi brute-force e abusi
- **Audit logging** — Le operazioni critiche sono registrate per il monitoraggio della sicurezza

---

## 🔐 Privacy dei Dati

### Quali dati raccogliamo

Life Tracker raccoglie solo i dati che fornisci esplicitamente:

- **Informazioni account**: Email, nome, dettagli profilo
- **Dati sulla salute**: Peso, sonno, calorie, passi, parametri vitali, pasti, medicine
- **Dati di utilizzo**: Timestamp, informazioni dispositivo (per scopi di sincronizzazione)

### Cosa NON raccogliamo

- ❌ NON tracciamo il tuo comportamento di navigazione
- ❌ NON vendiamo i tuoi dati a terze parti
- ❌ NON utilizziamo i tuoi dati per pubblicità
- ❌ NON condividiamo i tuoi dati senza il tuo consenso

### Archiviazione dei dati

- Tutti i dati sono archiviati in **Firebase Firestore** (Google Cloud)
- I dati sono archiviati in **data center europei** (regione: europe-west1)
- I dati sono **crittografati a riposo** e **in transito**
- Puoi **esportare** o **eliminare** i tuoi dati in qualsiasi momento

### Integrazioni di terze parti

Life Tracker si integra con:

- **Google Fit** (opzionale) — Solo se lo autorizzi esplicitamente
- **Telegram** (opzionale) — Solo se fornisci il tuo bot token e chat ID

Queste integrazioni sono **opt-in** e possono essere disconnesse in qualsiasi momento.

---

## 🚨 Segnalazione di Vulnerabilità di Sicurezza

Se scopri una vulnerabilità di sicurezza in Life Tracker, ti preghiamo di segnalarla in modo responsabile.

### Come segnalare

1. **NON** aprire una issue pubblica su GitHub
2. **Contattami direttamente** tramite il profilo GitHub o email
3. **Fornisci dettagli**: Descrizione, passaggi per riprodurre, potenziale impatto
4. **Attendi risposta**: Confermerò la tua segnalazione entro 48 ore

### Cosa aspettarsi

- **Conferma** entro 48 ore
- **Indagine** e valutazione della vulnerabilità
- **Correzione** distribuita il prima possibile (a seconda della gravità)
- **Riconoscimento** nella sezione ringraziamenti (se lo desideri)

### Divulgazione responsabile

Ti preghiamo di concedere un tempo ragionevole per la correzione della vulnerabilità prima della divulgazione pubblica. Apprezzo la tua collaborazione nel mantenere Life Tracker sicuro per tutti gli utenti.

---

## 🔍 Best Practice di Sicurezza per gli Utenti

Per mantenere il tuo account sicuro:

- ✅ Usa una **password forte e unica** (almeno 8 caratteri, mix di lettere, numeri, simboli)
- ✅ **Verifica la tua email** dopo la registrazione
- ✅ **Disconnettiti** quando usi dispositivi condivisi
- ✅ **Non condividere** la tua password con nessuno
- ✅ **Abilita l'autenticazione a due fattori** (se disponibile in futuro)
- ✅ **Mantieni aggiornato il browser** per le ultime patch di sicurezza

---

## 📋 Checklist di Sicurezza

Life Tracker implementa le seguenti misure di sicurezza:

- [x] Crittografia HTTPS per tutte le connessioni
- [x] Firebase Authentication con verifica email
- [x] Firestore Security Rules per l'isolamento dei dati
- [x] Validazione e sanitizzazione degli input
- [x] Protezione XSS e CSRF
- [x] Rate limiting sulle operazioni sensibili
- [x] Audit logging per azioni critiche
- [x] Aggiornamenti regolari delle dipendenze
- [x] Archiviazione sicura delle password (hashate)
- [x] Gestione delle sessioni e scadenza automatica
- [x] Data center europei (conforme GDPR)
- [x] Capacità di esportazione ed eliminazione dati

---

## 🔄 Aggiornamenti di Sicurezza

Gli aggiornamenti di sicurezza vengono distribuiti automaticamente:

- **Vulnerabilità critiche**: Corrette entro 24-48 ore
- **Problemi ad alta priorità**: Corretti entro 1 settimana
- **Problemi a media priorità**: Corretti entro 2 settimane
- **Problemi a bassa priorità**: Corretti nel prossimo aggiornamento regolare

Gli utenti vengono aggiornati automaticamente quando ricaricano l'applicazione (aggiornamento automatico PWA).

---

## 📜 Conformità

Life Tracker è progettato con privacy e sicurezza in mente:

- **Conforme GDPR** — Dati archiviati in data center europei
- **Portabilità dei dati** — Esporta i tuoi dati in formato CSV
- **Diritto alla cancellazione** — Elimina il tuo account e tutti i dati in qualsiasi momento
- **Trasparenza** — Informazioni chiare sulla raccolta e l'utilizzo dei dati

---

## 📞 Contatti

Per domande o dubbi relativi alla sicurezza:

- **GitHub**: [@AndreaBonn](https://github.com/AndreaBonn)
- **Problemi di sicurezza**: Contattami direttamente tramite il profilo GitHub

Per supporto generale, consulta il [README](./README_IT.md).

---

## 🙏 Ringraziamenti

Vorrei ringraziare i ricercatori di sicurezza e gli utenti che hanno contribuito a migliorare la sicurezza di Life Tracker.

Se hai segnalato una vulnerabilità e desideri essere riconosciuto, fammelo sapere.

---

**Ultimo aggiornamento:** Gennaio 2025

**© 2025 Andrea Bonacci — Tutti i diritti riservati**

[![English Version](https://img.shields.io/badge/🇬🇧_English_Version-4A90E2?style=flat-square)](./SECURITY.md) &nbsp; [![README](https://img.shields.io/badge/📖_README-009246?style=flat-square)](./README.md)
