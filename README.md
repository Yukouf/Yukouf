<div align="center">

# Youssef Guerniou

### Cybersecurity Automation · Security AI · Defensive Engineering

[![Portfolio](https://img.shields.io/badge/Portfolio-Projets%20et%20preuves-111827?style=for-the-badge)](https://yukouf.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Youssef%20Guerniou-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/youssefguerniou)

</div>

Je construis des outils qui transforment les signaux de sécurité en **décisions vérifiables** : audit Linux, détection DNS, reporting SIEM et automatisation assistée par IA. Mon fil conducteur : automatiser le travail répétitif sans masquer les limites ni supprimer le contrôle humain.

## Projets à voir en premier

| Projet | Valeur démontrée | Preuves publiques |
|---|---|---|
| **[HardAudit](https://github.com/Yukouf/hardaudit)** | Audit de sécurité Linux lisible et exploitable | 9 modules · 20 tests · JSON · zéro dépendance |
| **[DNS Sentinel](https://github.com/Yukouf/dns-sentinel)** | Détecte les divergences DNS avec plusieurs résolveurs DoH | 9 tests · DNSSEC · score de risque · JSON |
| **[AutoApply Studio](https://github.com/Yukouf/autoapply-studio)** | Adapte CV et lettres localement sans inventer de faits ni soumettre automatiquement | 13 tests TAP · 8 scripts d'assertions · privacy check |
| **[Agent IA SOC](https://github.com/Yukouf/agent-ia-soc)** | Webhook SOC, analyse assistée et validation humaine Telegram | 11 tests de sécurité · remédiation désactivée par défaut |

## Ce que je sais construire

```text
Alertes / logs / système
          │
          ▼
Collecte et normalisation ──► règles déterministes ──► analyse IA locale/API
          │                                              │
          └──────────── preuves, tests et logs ◄─────────┘
                                 │
                                 ▼
                     validation humaine / rapport
```

- **Security engineering :** Wazuh, Suricata, audit Linux, DNS, vulnérabilités
- **Automation :** Python, API, webhooks, Telegram, n8n
- **AI appliquée :** Ollama, DeepSeek, agents spécialisés, classification assistée
- **Infrastructure :** Linux, Docker, réseaux, Zabbix

## Autres réalisations

- **[Wazuh CVE Alerter](https://github.com/Yukouf/wazuh-cve-alerter-mail)** — alertes email et rappels J+3/J+7, sans dépendance Python externe.
- **[Zabbix Auto Report AI](https://github.com/Yukouf/zabbix-auto-report-ai)** — reporting Excel, référentiel déterministe et IA locale Ollama.
- **[AutoApply Extension](https://github.com/Yukouf/autoapply-extension)** — pré-remplissage Chrome FR/EN, sans soumission automatique.
- **[Fine-Tuning CPU](https://github.com/Yukouf/fine-tuning-cpu)** — démonstration Seq2Seq/LoRA sur CPU avec dataset SOC contrôlé.

> Chaque dépôt principal contient un démarrage rapide, des limites explicites et des preuves de test reproductibles.
