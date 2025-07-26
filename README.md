# 🔐 CyberSec Blue Labs

Labs práticos para quem deseja fortalecer suas habilidades como analista de segurança ofensiva e defensiva, com foco em **monitoramento, detecção, investigação e resposta a incidentes**.

---

## 💡 Objetivo

- Desenvolver competências de Blue Team e SOC
- Praticar análise de logs, SIEM e threat hunting
- Trabalhar com ferramentas como Wazuh, Elastic, Suricata, Splunk, Sysmon
- Simular ataques e aprender a responder eventos reais

---

## 🚀 Projetos disponíveis

| Projeto | Descrição | Tecnologias |
|---------|-----------|-------------|
| Lab Wazuh + Suricata + ELK | SIEM completo com IDS e dashboard de eventos | Wazuh, Suricata, ELK Stack |
| Threat Hunting com Sysmon | Coleta de eventos Windows e análise manual | Sysmon, PowerShell, Sigma |
| Simulação de Ataques com Caldera | Framework de adversário para teste de detecção | MITRE Caldera, ATT&CK |
| Dashboards com Splunk | Ingestão e visualização de logs de segurança | Splunk, Syslog-ng, Log Parser |

---

## 🧰 Stack utilizada

- Wazuh, Suricata, Elastic Stack (ELK)  
- Splunk, Sigma, Sysmon  
- MITRE ATT&CK, Caldera  
- Linux (Ubuntu Server), PowerShell, Docker

---

## 🗂️ Estrutura do projeto

```bash
📁 cybersec-blue-labs/
├── wazuh-elk-lab/
│   ├── docker-compose.yml
│   ├── dashboards/
├── sysmon-threat-hunting/
│   ├── config/sysmon.xml
│   ├── rules/
├── caldera-attack-sim/
│   ├── setup.sh
│   ├── ops_profile.json
├── splunk-log-analysis/
│   ├── parser.conf
│   ├── dashboards/
```

---

## 🧠 Como rodar localmente

Clone o repositório e escolha o lab desejado:

```bash
git clone https://github.com/AndreGoncallez/cybersec-blue-labs.git
cd cybersec-blue-labs/wazuh-elk-lab
```

Suba o ambiente com Docker Compose:

```bash
docker compose up -d
```

Acesse o painel Wazuh: [http://localhost:5601](http://localhost:5601)

---

## 🧪 Em breve

- Regras YARA e análise de malware
- Integração com TheHive e Cortex
- Detecção de Lateral Movement com RDP e PSExec
- Detecção de Beaconing com Zeek + ELK
