# 🔍 OSINT – Manuale Pratico | Corso Interattivo

Corso interattivo di **Open Source Intelligence (OSINT)**: un percorso completo strutturato in 12 lezioni, quiz di autovalutazione, strumenti pratici, script in Python e tecniche avanzate per l'analisi delle fonti aperte nel pieno rispetto del quadro legale ed etico italiano ed europeo.

---

## 📚 Struttura del Corso

Il corso è suddiviso in 12 moduli progressivi, pensati per accompagnare lo studente dai fondamenti teorici fino alle tecniche avanzate di ricognizione digitale:

1. **Introduzione all’OSINT**: Cos'è l'intelligence da fonti aperte, il pensiero critico e la mitigazione dei bias cognitivi.
2. **Il Ciclo dell’Intelligence**: Le 5 fasi del processo analitico, stesura dei requisiti (RFI) e gestione del piano di raccolta.
3. **Motori di Ricerca Avanzati e Dork**: Uso avanzato di Google, Bing, Yandex, DuckDuckGo (!bang), Shodan, Censys, URLScan e VirusTotal.
4. **La Ricerca degli Username**: Anatomia dei nickname, pattern di riutilizzo, strumenti di enumerazione (*WhatsMyName*, *Maigret*, *BlackBird*) e generazione di ipotesi e-mail.
5. **E-mail e Profili Associati**: Analisi strutturale delle e-mail, lettura degli header, signup check (*Holehe*), breach intelligence (*IntelX*, *LeakCheck*) e pivot completi.
6. **Identificazione Telefonica e B2B**: Formato E.164, servizi CallerID (*Truecaller*, *GetContact*), analisi di liste in batch e tecniche di ricognizione aziendale B2B.
7. **Telegram e le Sue Specificità**: *(Lezione successiva del programma interattivo)*
8. **Ricerca Inversa e Analisi di Immagini**: *(Lezione successiva del programma interattivo)*
9. **Geolocalizzazione Visiva e Dati Geospaziali**: *(Lezione successiva del programma interattivo)*
10. **Tracciamento di Aeromobili e Navi (SIGINT Aperta)**: *(Lezione successiva del programma interattivo)*
11. **Python per l'OSINT e Automazione**: *(Lezione successiva del programma interattivo)*
12. **Etica, OPSEC e Reporting Finale**: *(Lezione successiva del programma interattivo)*

---

## 🛠️ Strumenti e Script Inclusi

All'interno del corso sono forniti script in **Python 3** pronti all'uso (che sfruttano esclusivamente la libreria standard o librerie ufficiali) per automatizzare la fase di raccolta e gestione dei dati:

* `diario_osint.py`: Registro d'indagine con generazione automatica di timestamp UTC e impronte SHA-256 delle prove (screenshot).
* `collection_plan.py`: Gestione strutturata del piano di raccolta (EEI) tramite file JSON.
* `google_dork_builder.py`: Costruttore guidato di query di ricerca avanzate.
* `shodan_osint.py`: Interrogazione dell'API ufficiale di Shodan.
* `urlscan_osint.py`: Automazione delle ricerche e scansioni su URLScan.io.
* `virustotal_osint.py`: Analisi di domini e indirizzi IP tramite VirusTotal.
* `censys_osint.py`: Ricerca di host e certificati TLS su Censys.
* `wmn_check.py`: Script di verifica username basato sul dataset di *WhatsMyName*.
* `maigret_launcher.py`: Lanciatore e gestore dei report generati da *Maigret*.
* `email_generator.py`: Generatore di ipotesi di e-mail aziendali e personali con verifica Gravatar/HIBP.
* `hunter_verify.py`: Integrazione con l'API di Hunter.io per la verifica formale degli indirizzi.
* `numverify_lookup.py` & `batch_carrier_lookup.py`: Strumenti per il carrier lookup dei numeri telefonici.
* `normalize_phones.py`: Normalizzazione di liste massive di numeri in formato internazionale E.164.

---

## ⚖️ Quadro Legale ed Etico

Ogni lezione integra sezioni dedicate alla conformità normativa. L'attività OSINT in Italia e nell'Unione Europea deve rigorosamente rispettare:

* **GDPR (Regolamento UE 2016/679)**: Trattamento dei dati personali, principi di minimizzazione e limitazione delle finalità.
* **Codice Privacy (D.Lgs. 196/2003 e s.m.i.)**: Sanzioni relative al trattamento illecito o all'acquisizione fraudolenta di dati.
* **Codice Penale Italiano**: Limiti invalicabili relativi all'accesso abusivo a sistemi informatici (**Art. 615-ter c.p.**), sostituzione di persona (**Art. 494 c.p.**), intercettazione illecita (**Art. 617-quater c.p.**) e atti persecutori / stalking (**Art. 612-bis c.p.**).

> *Regola d'oro dell'analista:* **Lecito non significa automaticamente pubblico**, e raccogliere informazioni non autorizza mai ad accedere a sistemi protetti o a violare la privacy dei soggetti indagati.

---

## 🚀 Come iniziare

1. Clona o scarica il repository sul tuo ambiente di lavoro (si consiglia l'uso di una macchina virtuale Linux dedicata, es. *Trace Labs OSINT VM* o *CSI Linux*).
2. Apri il file `index.html` nel tuo browser preferito per accedere alla piattaforma didattica interattiva completa di quiz e verifiche di apprendimento.
3. Configura un browser isolato con estensioni di privacy (es. *uBlock Origin*) e mantieni sempre un rigoroso regime di **OPSEC** (Operational Security).
