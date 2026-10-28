[![OSINT Course Banner](https://raw.githubusercontent.com/jericho1965-droid/osint_course/main/osint_banner.jpeg)](https://raw.githubusercontent.com/jericho1965-droid/osint_course/main/osint_banner.jpeg)

# 🔍 OSINT – Manuale Pratico | Corso Interattivo

Corso interattivo di Open Source Intelligence (OSINT): un percorso completo strutturato in **16 lezioni**, quiz di autovalutazione, strumenti pratici, script in Python e tecniche avanzate per l'analisi delle fonti aperte, nel pieno rispetto del quadro legale ed etico italiano ed europeo.

## 📖 Libro del Corso

Il manuale cartaceo / digitale completo che accompagna questo corso è disponibile su Amazon:

[![Libro del Corso su Amazon](https://img.shields.io/badge/Amazon-Compra%20il%20Libro-orange?style=for-the-badge&logo=amazon&logoColor=white)](https://www.amazon.it/dp/B0HP6MQP3R)

## 📚 Struttura del Corso

Il corso è suddiviso in 16 moduli progressivi, pensati per accompagnare lo studente dai fondamenti teorici fino alle tecniche avanzate di ricognizione digitale. Ogni lezione termina con un quiz: serve almeno il **75%** di risposte corrette per sbloccare la lezione successiva.

1. **Introduzione all'OSINT**: cos'è l'intelligence da fonti aperte, il pensiero critico e la mitigazione dei bias cognitivi.
2. **Il Ciclo dell'Intelligence**: le 5 fasi del processo analitico, stesura dei requisiti (RFI) e gestione del piano di raccolta.
3. **Motori di Ricerca e Dork**: uso avanzato di Google, Bing, Yandex, DuckDuckGo (!bang), Shodan, Censys, URLScan e VirusTotal.
4. **La Ricerca degli Username**: anatomia dei nickname, pattern di riutilizzo, strumenti di enumerazione (WhatsMyName, Maigret, BlackBird) e generazione di ipotesi e-mail.
5. **E-mail e Profili Associati**: analisi strutturale delle e-mail, lettura degli header, signup check (Holehe), breach intelligence (IntelX, LeakCheck) e pivot completi.
6. **Identificazione Telefonica e B2B**: formato E.164, servizi CallerID (Truecaller, GetContact), analisi di liste in batch e ricognizione aziendale B2B.
7. **Telegram**: bot, utenti, gruppi e canali, ricerca dei link d'invito, TGStat, strumenti come Telepathy e TeleRecon, scraping e normative, analisi degli ID.
8. **Ricerca Inversa e Analisi di Immagini**: ricerca inversa per immagini, riconoscimento facciale, dati EXIF e steganografia.
9. **Facebook OSINT**: ricerca ricorsiva, Sowsearch, dork, Facebook ID, Ads Library, Marketplace, sock puppet ed etica.
10. **Python per OSINT**: strumenti di analisi, automazione e utilizzo avanzato dei dati.
11. **SIGINT: Aeromobili**: tracking ADS-B, database ufficiali e non, incidenti, aeroporti, licenze dei piloti e tracking cargo.
12. **Social Engineering**: tecniche di persuasione ed elicitazione, bisogni umani e difese.
13. **Intelligence Aziendale e Registri Pubblici**: Registro Imprese, Catasto, PRA, ANAC, VIES, OpenCorporates, metodo di indagine su un'impresa e segnali di società di comodo.
14. **Intelligence Tecnica: Domini e Infrastruttura**: WHOIS, record DNS, Certificate Transparency (crt.sh), Shodan e Censys nei limiti di legge, pivoting.
15. **Criptovalute e Blockchain**: pseudonimia, block explorer, clustering, mixer e privacy coin, aspetti legali.
16. **OPSEC, Prove e Reportistica**: separazione degli ambienti, hash e catena di custodia, verifica delle fonti, struttura del rapporto, principi etici.

## 🛠️ Strumenti e Script Inclusi

All'interno del corso sono forniti script in Python 3 pronti all'uso (che sfruttano esclusivamente la libreria standard o librerie ufficiali) per automatizzare la fase di raccolta e gestione dei dati:

- `diario_osint.py`: registro d'indagine con generazione automatica di timestamp UTC e impronte SHA-256 delle prove (screenshot).
- `collection_plan.py`: gestione strutturata del piano di raccolta (EEI) tramite file JSON.
- `google_dork_builder.py`: costruttore guidato di query di ricerca avanzate.
- `shodan_osint.py`: interrogazione dell'API ufficiale di Shodan.
- `urlscan_osint.py`: automazione delle ricerche e scansioni su URLScan.io.
- `virustotal_osint.py`: analisi di domini e indirizzi IP tramite VirusTotal.
- `censys_osint.py`: ricerca di host e certificati TLS su Censys.
- `wmn_check.py`: verifica username basata sul dataset di WhatsMyName.
- `maigret_launcher.py`: lanciatore e gestore dei report generati da Maigret.
- `email_generator.py`: generatore di ipotesi di e-mail aziendali e personali con verifica Gravatar/HIBP.
- `hunter_verify.py`: integrazione con l'API di Hunter.io per la verifica formale degli indirizzi.
- `numverify_lookup.py` e `batch_carrier_lookup.py`: strumenti per il carrier lookup dei numeri telefonici.
- `normalize_phones.py`: normalizzazione di liste massive di numeri in formato internazionale E.164.

## ⚖️ Quadro Legale ed Etico

Ogni lezione integra sezioni dedicate alla conformità normativa. L'attività OSINT in Italia e nell'Unione Europea deve rigorosamente rispettare:

- **GDPR (Regolamento UE 2016/679)**: trattamento dei dati personali, principi di minimizzazione e limitazione delle finalità.
- **Codice Privacy (D.Lgs. 196/2003 e s.m.i.)**: sanzioni relative al trattamento illecito o all'acquisizione fraudolenta di dati.
- **Codice Penale Italiano**: limiti invalicabili relativi all'accesso abusivo a sistemi informatici (art. 615-ter c.p.), sostituzione di persona (art. 494 c.p.), intercettazione illecita (art. 617-quater c.p.) e atti persecutori / stalking (art. 612-bis c.p.).

> **Regola d'oro dell'analista:** lecito non significa automaticamente pubblico, e raccogliere informazioni non autorizza mai ad accedere a sistemi protetti o a violare la privacy dei soggetti indagati.

## 🤝 Come Contribuire

Leggi il file `CONTRIBUTING.md` per conoscere le linee guida su come inviare una Pull Request o segnalare Issue. Ti chiediamo inoltre di rispettare il `CODE_OF_CONDUCT.md` e la `SECURITY.md`.

## 🚀 Come iniziare

1. Clona o scarica il repository sul tuo ambiente di lavoro (si consiglia una macchina virtuale Linux dedicata, ad esempio Trace Labs OSINT VM o CSI Linux).
2. Apri il file `index.html` nel tuo browser preferito per accedere alla piattaforma didattica interattiva con quiz e verifiche di apprendimento.
3. Configura un browser isolato con estensioni di privacy (ad esempio uBlock Origin) e mantieni sempre un rigoroso regime di OPSEC (Operational Security).
