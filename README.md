# OSINT CHECK

OSINT CHECK è un tool **"Plug & Play"** per l'analisi rapida della reputazione di **Indirizzi IP**, **Domini (URL)** e **File Hash** (MD5, SHA1, SHA256).  
Il programma incrocia i dati di **3 database mondiali** per indicare se un target è **sicuro** o **malevolo**.

---

## 1. CONFIGURAZIONE INIZIALE (API KEYS)

Al primo avvio devi inserire le tue **chiavi API gratuite**.  
Senza di esse il programma non può scaricare i dati.

Registrati gratuitamente ai seguenti servizi:

1. **VirusTotal**  
   https://www.virustotal.com/gui/join-us  
   *(Profilo → API Key)*

2. **AbuseIPDB**  
   https://www.abuseipdb.com/register  
   *(API → Create Key)*

3. **IPQualityScore**  
   https://www.ipqualityscore.com/create-account  
   *(Dashboard → API Settings)*

### Inserimento delle chiavi

1. Apri *OSINT CHECK*  
2. Clicca su **API** (in alto a destra)  
3. Incolla le chiavi nei campi dedicati  
4. Clicca su **SALVA**

> Le API vengono salvate nel file `config.json`: **non cancellarlo** altrimenti perderai la configurazione.

---

## 2. COMANDI E SCORCIATOIE

Il programma è progettato per essere veloce e **controllabile da tastiera**.

### Avviare una scansione

- Incolla una lista di IP/Hash nel box
- Premi **▶ AVVIA ANALISI**
- Oppure usa la scorciatoia: **CTRL + INVIO**

### Modalità Ghost (nascondi/mostra)

- Premi **CTRL + O** in qualsiasi momento  
  (anche mentre usi altri programmi)

---

## 3. GESTIONE FINESTRA E CHIUSURA

Il programma lavora in background per essere sempre pronto.

### Tasto **X** della finestra

Non chiude il programma — lo **minimizza** nella tray (barra vicino all'orologio).

### Tasto **ESCI**

Chiude definitivamente il programma e arresta i processi.

### Icon Tray

- **Click singolo** → riapre l'app
- **Tasto destro → Chiudi** → termina l'app

---

## NOTE TECNICHE

- Richiede connessione internet
- Le API gratuite hanno dei limiti giornalieri (es. 500 richieste/giorno)
- In caso di errore, verifica la quota sul sito dei provider API

---

# **ENGLISH VERSION**

OSINT CHECK is a **Plug & Play tool** for fast reputation checks on **IP addresses**, **domains (URLs)**, and **file hashes** (MD5, SHA1, SHA256).  
The program correlates data from **three global threat-intelligence databases** to determine whether a target is **safe** or **malicious**.

---

## 1. INITIAL CONFIGURATION (API KEYS)

On first launch, you must enter your **free API keys**.  
Without them, the program cannot retrieve data.

Register for free at the following services:

1. **VirusTotal**  
   https://www.virustotal.com/gui/join-us  
   *(Profile → API Key)*

2. **AbuseIPDB**  
   https://www.abuseipdb.com/register  
   *(API → Create Key)*

3. **IPQualityScore**  
   https://www.ipqualityscore.com/create-account  
   *(Dashboard → API Settings)*

### How to insert the keys

1. Open *OSINT CHECK*
2. Click **API** (top-right)
3. Paste the keys into the input fields
4. Click **SAVE**

> Keys are stored in `config.json` — **do not delete** it or your configuration will be lost.

---

## 2. COMMANDS & SHORTCUTS

The tool is designed to be fast and **keyboard-friendly**.

### Run an analysis

- Paste a list of IPs/Hashes into the text field
- Click **▶ RUN ANALYSIS**
- Or press **CTRL + ENTER**

### Ghost Mode (hide/show)

- Press **CTRL + O** at any time  
  (even while using other applications)

---

## 3. WINDOW MANAGEMENT & EXIT

The tool works in background to stay ready.

### Window **X** button

Does not close the tool — it **minimizes** it to the tray.

### **EXIT** button

Closes the program completely and stops all processes.

### Tray Icon

- **Single click** → reopens
