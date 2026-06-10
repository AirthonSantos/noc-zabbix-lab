# 📡 Laboratório NOC com Zabbix

Este projeto tem como objetivo simular um ambiente básico de NOC (Network Operations Center) usando tecnologias amplamente usadas em operações de infraestrutura e monitoramento.

O laboratório foi construído em uma infraestrutura virtualizada com Ubuntu Server, VMware Workstation e Zabbix, permitindo a prática de monitoramento, troubleshooting, administração Linux e análise de incidentes em um ambiente controlado. Além da implementação técnica, procurei documentar todo o processo, incluindo problemas encontrados, decisões tomadas e soluções aplicadas durante a implementação do ambiente.

Posteriormente, pretendo expandir o laboratório com dashboards avançados com Grafana e automações operacionais com Ansible.

> [!IMPORTANT]
> **Status do Lab:** 🚧 Em desenvolvimento

---
# 🎯 Objetivos

- Implementar uma plataforma de monitoramento baseada em Zabbix
- Monitorar hosts, métricas e serviços críticos
- Criar dashboards para visualização operacional
- Simular incidentes e validar mecanismos de detecção
- Desenvolver e testar triggers personalizadas
- Praticar troubleshooting em ambientes Linux
- Implementar visualizações avançadas com Grafana
- Automatizar tarefas administrativas com Ansible
- Documentar todo o processo de implementação e evolução do laboratório

---
# 🧱 Tecnologias Usadas

| Tecnologia          | Função                      |
| ------------------- | --------------------------- |
| Ubuntu Server 24.04 | Sistema Operacional         |
| Zabbix 6.4          | Plataforma de monitoramento |
| Grafana             | Visualização de métricas    |
| Ansible             | Automação e gerenciamento   |
| MariaDB             | Banco de dados              |
| Apache2             | Frontend Web                |
| VMware Workstation  | Virtualização               |
| WSL2                | Host Linux adicional        |
| Netplan             | Configuração de rede        |

---
# 📚 Documentação

| Documento                                                        | Descrição                                                                                                                |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [01 - Setup Inicial](./docs/01-setup-inicial.md)                 | Configuração inicial da infraestrutura e rede                                                                            |
| [02 - Instalação do Zabbix](./docs/02-instalacao-zabbix.md)      | Instalação e configuração do Zabbix Server                                                                               |
| [03 - Monitoramento Parte 1](./docs/03-monitoramento-parte-1.md) | Configuração do primeiro host, validação de métricas e triggers, e consequentemente a validação do ambiente como um todo |
| [04 - Monitoramento Parte 2](./docs/04-monitoramento-parte-2.md) | Adição de segundo host, dashboard personalizado, trigger customizada e monitoramento de serviços                         |
| [05 - Integração com Grafana](./docs/05-grafana.md)              | Dashboards avançados e visualização de métricas *(em desenvolvimento)*                                                   |
| [06 - Automação com Ansible](./docs/06-ansible.md)               | Automação operacional e playbooks *(em desenvolvimento)*                                                                 |

---
# 📸 Screenshots

## Dashboard Global View
<p align="center">
  <img src="./assets/02-instalacao-zabbix/zabbix-dashboard.png" alt="Dashboard padrão do Zabbix" width="900">
</p>

## Dashboard operacional personalizado durante teste de monitoramento
<p align="center">
  <img src="./assets/04-monitoramento-p2/memory_trigger_comparison.png" alt="Dashboard personalizado" width="900">
</p>

---
# 🚧 Próximos Passos

- Integrar Zabbix e Grafana
- Criar dashboards operacionais no Grafana
- Automatizar tarefas administrativas com Ansible
- Desenvolver playbooks de configuração e operação

---

# 📌 Observações

Este projeto possui foco educacional e prático, com documentação incremental baseada nas etapas reais de implementação do laboratório.
