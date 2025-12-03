# 🏋🏻‍♂️ Life Tracker (PWA)

<div align="center">

**Web App per la gestione delle della salute**

🌐 [**Prova l'App**](https://personal-health-by-bonn.web.app) • 📱 Installabile • ☁️ Sincronizzazione Cloud

</div>

---

## ℹ️ Descrizione

**Life Tracker** è una PWA completa per il monitoraggio della salute personale. Sviluppata con **HTML5, CSS3 e JavaScript vanilla**, utilizza **Firebase** per il backend, **Chart.js** per le visualizzazioni interattive e si integra con **Google Fit** e **Telegram**.

L'app offre un'esperienza utente moderna e intuitiva.

---

## ✨ Caratteristiche Principali

### 💪 Monitoraggio Completo della Salute
- **Peso Corporeo** - Traccia il tuo peso con storico completo, grafici di andamento e calendario mensile visuale con codice colore per le variazioni
- **Parametri Vitali** - Monitora pressione sanguigna, frequenza cardiaca e glicemia con grafici dettagliati
- **Piano Alimentare** - Sistema completo di gestione pasti con alternative giornaliere organizzate per giorno della settimana
- **Diario Alimentare** - Registra ogni pasto consumato con dettagli su peso, quantità e calorie
- **Calorie e TDEE** - Calcolo automatico del fabbisogno calorico giornaliero con insights personalizzati
- **Dieta Dettagliata** - Tracciamento acqua, caffè, alcol e sigarette con statistiche giornaliere e settimanali
- **Attività Fisica** - Tracciamento passi, sonno e workout completati con schede personalizzate
- **Sonno Avanzato** - Registra ore di sonno con picker intuitivo ore/minuti, oppure orari precisi di inizio e fine sonno
- **Medicine** - Sistema di promemoria con rinnovo automatico ogni 3 mesi

### 📊 Visualizzazioni Interattive

#### Grafici Trend Temporali
Monitora l'andamento di peso, calorie, passi e sonno con grafici a linee interattivi. Filtra per settimana, mese o anno.

#### Calendario Mensile Peso
Visualizza il tuo peso in un calendario mensile con codice colore: verde per le variazioni positive verso il tuo obiettivo, rosso per quelle negative. L'intensità del colore indica la gravità della variazione.

#### Dashboard Parametri Vitali
Visualizza pressione, frequenza cardiaca e glicemia con grafici dedicati. Clicca su ogni punto per vedere i dettagli della misurazione.

#### Analisi Dieta
Traccia acqua, caffè, alcol e sigarette con contatori giornalieri e statistiche settimanali.

### 🎯 Obiettivi e Motivazione

- **Peso Desiderato** - Imposta il tuo obiettivo e monitora i progressi
- **Streak System** - Mantieni la motivazione con streak giornalieri
- **Badge e Celebrazioni** - Sblocca riconoscimenti per obiettivi raggiunti
- **Insights Personalizzati** - Suggerimenti basati sui tuoi dati

### 🤖 Insights Intelligenti

Il motore di analisi automatica ti aiuta a:
- 📈 Identificare pattern nelle tue abitudini di salute
- 🔍 Scoprire correlazioni tra peso, calorie e attività
- 📅 Confrontare periodi diversi (settimana corrente vs precedente)
- 💡 Ricevere suggerimenti personalizzati per migliorare il benessere

### 🔗 Integrazioni Avanzate

- **Google Fit** - Sincronizzazione automatica di peso, passi, calorie, sonno, glicemia, pressione sanguigna, frequenza cardiaca e workout completati
- **Notifiche Medicine** - Promemoria per l'assunzione di farmaci con sistema di rinnovo automatico ogni 3 mesi
- **Export Dati** - Esporta piano alimentare e dati di salute in formato CSV per backup completo

### 🌍 Multilingua

Interfaccia completamente tradotta in:
- 🇮🇹 **Italiano**
- 🇬🇧 **English**

Switch istantaneo tra le lingue con traduzione automatica di tutti i messaggi.

### 📱 Progressive Web App

- **Installabile** - Aggiungi alla home screen come app nativa
- **Offline First** - Funziona anche senza connessione internet
- **Responsive Design** - Ottimizzata per mobile, tablet e desktop
- **Performance** - Caricamento veloce e animazioni fluide

---


## 🛠️ Tecnologie Utilizzate

### Frontend
- **HTML5, CSS3, JavaScript** - Vanilla JS per massime performance
- **Chart.js** - Libreria per grafici interattivi e responsive
- **PWA APIs** - Service Worker, Web App Manifest, Cache API

### Backend & Storage
- **Firebase Firestore** - Database NoSQL real-time
- **Firebase Authentication** - Sistema di autenticazione sicuro con verifica email
- **Firebase Cloud Functions** - Serverless functions per notifiche e integrazioni
- **Firebase Hosting** - Hosting veloce e affidabile con HTTPS

### Integrazioni
- **Google Fit API** - Sincronizzazione automatica dati fitness
- **OAuth 2.0** - Autenticazione sicura per Google Fit

### Architettura
- **Single Page Application** - Navigazione fluida senza reload
- **Offline First** - Persistenza locale con sincronizzazione cloud
- **Responsive Design** - Mobile-first approach
- **Real-time Updates** - Sincronizzazione istantanea tra dispositivi

---

## 🚀 Come Funziona

### 1. Registrazione e Login
Crea un account con email e password. Verifica la tua email per accedere all'app.

### 2. Completa il Tuo Profilo
Imposta informazioni personali:
- Nome, data di nascita, genere
- Città di residenza
- Livello di attività fisica
- Condizioni mediche (opzionale)

### 3. Imposta Obiettivi
Definisci:
- Peso desiderato
- Obiettivo calorie giornaliere
- Target passi giornalieri
- Ore di sonno ideali

### 4. Crea il Tuo Piano Alimentare
Organizza i tuoi pasti:
- Crea alternative per colazione, spuntini, pranzo e cena
- Organizza per giorno della settimana (es. Colazione Lunedì, Pranzo Martedì)
- Aggiungi ingredienti con grammature precise
- Seleziona l'alternativa da consumare oggi
- Esporta il piano in CSV

### 5. Traccia i Tuoi Dati
Registra quotidianamente:
- Peso corporeo (visualizzabile anche nel calendario mensile)
- Calorie bruciate
- Passi e attività fisica
- Ore di sonno con picker intuitivo (ore e minuti separati) o orari precisi
- Parametri vitali (pressione, frequenza cardiaca, glicemia)
- Dieta (acqua, caffè, alcol, sigarette)
- Pasti consumati nel diario alimentare
- Medicine assunte (con rinnovo automatico ogni 3 mesi)

### 6. Connetti Google Fit (Opzionale)
Sincronizza automaticamente peso, passi, calorie, sonno, glicemia, pressione, frequenza cardiaca e workout dal tuo dispositivo.

### 7. Ricevi Insights e Notifiche
- Analisi automatica dei tuoi progressi con correlazioni intelligenti
- Suggerimenti personalizzati basati sui tuoi dati
- Promemoria medicine con avvisi automatici per il rinnovo (ogni 3 mesi)


---

## 🎯 Prova Subito l'App!

<div align="center">

### 👉 [**APRI LIFE TRACKER**](https://personal-health-by-bonn.web.app) 👈

**Nessuna installazione richiesta • Funziona su tutti i dispositivi • Dati sincronizzati nel cloud**

[![Prova Ora](https://img.shields.io/badge/🚀_INIZIA_GRATIS-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=1a73e8)](https://personal-health-by-bonn.web.app)

</div>

---



## 📬 Contatti

Per maggiori informazioni, collaborazioni o feedback:

📧 **Email:** [andreabonacci95@protonmail.com](mailto:andreabonacci95@protonmail.com)

---

<div align="center">

**© 2025 Andrea Bonacci - Tutti i diritti riservati**

</div>
