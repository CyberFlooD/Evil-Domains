# Evil-Domains by DUDIX CTI

<p align="center">
<img src="./Img/evil_domains.webp" width="300"/>
<p align="center">
  
![Powered by DudixCTI](https://img.shields.io/badge/powered%20by-DudixCTI-0052cc?style=for-the-badge&logo=apachekafka)
![Made with ❤️ by Dudix](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F-by%20Dudix-darkred?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/CyberFlood/evil-domains?label=Cyber%20Threat%20Intel%20%E2%80%93%20Last%20Update&color=informational&style=for-the-badge&logo=github)

</p>

---

Evil-Domains par DUDIX CTI est un flux public et mis à jour de domaines identifiés comme malveillants, conçu pour le threat-hunting, le blocage et l’ingestion SIEM. Usage non commercial uniquement.

---

## Objectif

- Fournir un flux public et défensif de **domaines malveillants** collectés par DUDIX CTI (exports OpenCTI, STIX, CSV).
- Usage attendu: threat hunting, blocage, corrélation, recherche. 
- Usage commercial interdit.


---


## Contenu du dépôt

- `evil_domains.csv` — CSV simple : `type,domaine,decrtiption,opencti_score`.
- `evil_domains.txt` — un domaine par ligne (raw, prêt à curl/wget).
- `evil_domains.stix.json` — STIX2 bundle pour ingestion (OpenCTI / MISP / SIEM).

## Usage
- Usage défensif uniquement (threat hunting, blocage, corrélation).
- Vérifiez la qualité et la pertinence avant ingestion automatique.

---

## 🔖 Licence

📝 Licence libre [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
> *Utilisation personnelle, adaptation autorisée, mais pas d’usage commercial sans accord.*

---
