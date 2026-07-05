# Linux - Scripts e Guias de Implantacao

Repositorio centralizado com scripts e documentacao para configuracao de servidores Linux.

---

## Estrutura

```
Linux ZBX + GRAFANA/
│
├── zbxgrafana/           # Versao classica: Zabbix 6.2 + Grafana (Ubuntu 22.04 LTS)
│   ├── zbx23             # Script principal de instalacao automatizada
│   ├── installzbxgrafana # Script alternativo de instalacao
│   └── zbx6grafana10.sh  # Script de instalacao Zabbix 6 + Grafana 10
│
└── zbxgrafana7/          # Versao moderna: Zabbix 7.0 LTS + Grafana 11.x (Ubuntu 24.04 LTS)
    └── zbx70             # Script atualizado de instalacao automatizada
```

---

## Instalacao Rapida

### Versao Classica (Ubuntu 22.04.1 LTS - Zabbix 6.2 + Grafana)
```bash
wget https://raw.githubusercontent.com/MJTecnologia/zbxgrafana/main/zbx23
bash zbx23
```

### Versao Atualizada (Ubuntu 24.04 LTS - Zabbix 7.0 LTS + Grafana 11.x)
```bash
wget https://raw.githubusercontent.com/MJTecnologia/zbxgrafana7/main/zbx70
bash zbx70
```

---

**MJTecnologia** | Infraestrutura e Monitoramento
