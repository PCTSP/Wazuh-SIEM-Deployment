## Wazuh SIEM Deployment

Objetivo:
Implementar uma plataforma SIEM para monitoramento centralizado de eventos de segurança.

Infraestrutura:
- Ubuntu Server 24.04 LTS
- Wazuh Manager
- Wazuh Indexer
- Wazuh Dashboard

Atividades realizadas:
- Instalação do Wazuh
- Troubleshooting de incompatibilidade de versão
- Diagnóstico de problemas de armazenamento
- Configuração de rede Host-Only
- Validação dos serviços

Resultados:
- Dashboard operacional
- Indexer operacional
- Manager operacional

Aprendizados:
- SIEM Architecture
- Log Management
- Security Monitoring
- Linux Troubleshooting
- Capacity Planning


## Wazuh Agent Integration

### Objetivo
Integrar o Domain Controller ao Wazuh SIEM.

### Atividades
- Instalação do agente Windows
- Registro do endpoint DC01
- Comunicação com o Wazuh Manager
- Validação da conectividade

### Resultado
- Endpoint ativo
- Logs sendo enviados para o SIEM

### Tecnologias
- Active Directory
- Windows Server
- Wazuh Agent
- Wazuh Manager
- Linux


feat(wazuh): configure Security Configuration Assessment (SCA) for Windows Server 2025

- Deployed Wazuh agent
- Troubleshot enrollment and connectivity issues
- Validated FIM and Rootcheck modules
- Adapted CIS benchmark from Windows Server 2022 to Windows Server 2025
- Successfully executed SCA scan
- Collected 359+ security checks
