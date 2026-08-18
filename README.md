<div align="center">

<br>

# Youssef Guerniou

**Detection Engineering · Security Automation · Blue Team**

<sub>Je conçois des outils qui transforment des signaux bruts en décisions vérifiables — détection, audit, reporting — sans jamais retirer l'humain de la boucle.</sub>

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=flat-square&logoColor=white)](https://yukouf.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0F172A?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/youssefguerniou)
[![GitHub](https://img.shields.io/badge/GitHub-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/Yukouf)

<br>

</div>

---

## Positionnement

Analyste cybersécurité orienté **détection et ingénierie défensive**. Mon travail se concentre sur trois axes : réduire le bruit d'alerte sans perdre de signal, rendre l'audit de sécurité reproductible, et industrialiser le reporting.

Chaque dépôt public ci-dessous suit la même exigence : **tests reproductibles, limites documentées, aucune action destructive automatique**.

<br>

## Domaines

| Détection & SIEM | Automatisation | Sécurité système |
|:---|:---|:---|
| Wazuh (règles, tuning, active response) | Python · API REST · webhooks | Durcissement Linux |
| Suricata (NIDS) | n8n · Telegram · reporting Excel | Active Directory (PingCastle) |
| Gestion des vulnérabilités / CVE | IA locale (Ollama) pour la synthèse | DNS · réseau · Docker |

<br>

## Projets sélectionnés

<table>
<tr>
<td width="50%" valign="top">

### HardAudit
Audit de sécurité Linux lisible et exploitable, conçu pour être lancé sans installer quoi que ce soit.

`9 modules` · `20 tests` · `sortie JSON` · `zéro dépendance`

[→ Voir le dépôt](https://github.com/Yukouf/hardaudit)

</td>
<td width="50%" valign="top">

### DNS Sentinel
Détection des divergences de résolution DNS entre résolveurs classiques et DoH, avec scoring de risque.

`9 tests` · `DNSSEC` · `score de risque` · `JSON`

[→ Voir le dépôt](https://github.com/Yukouf/dns-sentinel)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Wazuh CVE Alerter
Pipeline d'alerte email sur vulnérabilités critiques, avec rappels J+3 / J+7 et garde-fous contre les fausses résolutions.

`pipeline testé` · `remédiation jamais automatique`

[→ Voir le dépôt](https://github.com/Yukouf/wazuh-cve-alerter-mail)

</td>
<td width="50%" valign="top">

### Agent IA SOC
Webhook SOC avec validation humaine obligatoire via Telegram avant toute action.

`11 tests de sécurité` · `remédiation désactivée par défaut`

[→ Voir le dépôt](https://github.com/Yukouf/agent-ia-soc)

</td>
</tr>
</table>

<details>
<summary><b>Autres réalisations</b></summary>

<br>

| Projet | Description |
|:---|:---|
| [Zabbix Auto Report AI](https://github.com/Yukouf/zabbix-auto-report-ai) | Reporting de supervision automatisé (Excel), référentiel déterministe, synthèse par IA locale Ollama |
| [AutoApply Studio](https://github.com/Yukouf/autoapply-studio) | Adaptation locale de CV et lettres — n'invente rien, ne soumet rien. 13 tests TAP, contrôle de confidentialité |
| [AutoApply Extension](https://github.com/Yukouf/autoapply-extension) | Pré-remplissage Chrome FR/EN, sans soumission automatique |
| [Fine-Tuning CPU](https://github.com/Yukouf/fine-tuning-cpu) | Démonstration Seq2Seq / LoRA sur CPU, dataset SOC contrôlé |

</details>

<br>

## Architecture type

```
   Alertes · logs · télémétrie système
                  │
                  ▼
   Collecte  ──►  Normalisation  ──►  Règles déterministes
                                              │
                                              ▼
                                      Analyse assistée (IA locale)
                                              │
                  ┌───────────────────────────┘
                  ▼
   Preuves, tests, journalisation  ──►  Validation humaine  ──►  Rapport
```

Le déterminisme décide. L'IA résume et priorise. L'humain valide.

<br>

## Stack

**Sécurité** — Wazuh · Suricata · Active Directory · gestion des vulnérabilités · durcissement Linux
**Développement** — Python · Bash · API REST · webhooks
**Infrastructure** — Linux · Docker · Zabbix · réseaux
**IA appliquée** — Ollama · modèles locaux · agents spécialisés

<br>

## Contact

Ouvert aux opportunités **Blue Team / Detection Engineering / SOC** à partir d'octobre 2026 — Île-de-France, Luxembourg, Suisse.

[LinkedIn](https://www.linkedin.com/in/youssefguerniou) · [Portfolio](https://yukouf.github.io/portfolio/)
