# Raven1_PenetrationTesting

Questo repository contiene tutti gli artefatti prodotti durante l’attività di penetration testing sull’asset **Raven1** ed è organizzato come segue.

---

## 📁 Documentazione

Contiene i documenti prodotti:

- **PT_Metodologie-Raven.pdf**  
  Documento che descrive tutti i passaggi eseguiti durante il penetration testing, al fine di garantire la replicabilità del processo.

- **PT_Report-Raven.pdf**  
  Documento che riporta i risultati ottenuti, le vulnerabilità individuate e le relative raccomandazioni per migliorare la sicurezza del sistema.

- **PT_Presentazione_Digitale_Raven.pdf**  
  Slide utilizzate per la presentazione del progetto.

---

## 📁 Report

Contiene i report generati dai tool utilizzati (es. ZAP, Nessus).

---

## 📁 pentest_process

Contiene gli artefatti tecnici e le risorse utilizzate durante il processo di testing:

- **cve_manuali_Apache.txt**  
  Lista di CVE relative ad Apache utilizzata per la ricerca di exploit tramite Metasploit.

- **cve_manuali_SSH.txt**  
  Lista di CVE relative a OpenSSH utilizzata per la ricerca di exploit tramite Metasploit.

- **cve_manuali_Wordpress.txt**  
  Lista di CVE relative a WordPress utilizzata per la ricerca di exploit tramite Metasploit.

- **flag.txt**  
  Contiene tutte le flag individuate durante la challenge Raven:1.

- **hash_steven.txt**  
  Contiene l’hash dell’utente Steven, utilizzato per password cracking offline tramite John the Ripper.

- **user_identified.txt**  
  Elenco degli utenti validi del sistema identificati tramite WPScan, utilizzati per attività di target exploitation.

- **aggr_raven_scan.html**  
  Output della scansione Nmap aggressiva convertito in formato HTML.
