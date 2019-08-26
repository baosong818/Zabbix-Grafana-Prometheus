目录结构
```
.
├── agent
│   ├── node-exporter
│   │   └── docker-compose.yaml
│   └── zabbix-agent
│       └── docker-compose.yaml
├── README.md
└── server
    ├── grafana-prometheus
    │   ├── alertmanager.yml
    │   ├── docker-compose.yaml
    │   ├── grafana
    │   ├── node_down.yml
    │   └── prometheus.yml
    └── zabbix-server
        ├── docker-compose.yaml
        └── fonts
            └── DejaVuSans.ttf
```

注意
```
Zabbix server的agent监控接口使用DNS方法zabbix-agent: 10050，否则报错哦
其他服务器的agent监控接口推荐使用IP方法10.10.10.102: 10050
```
