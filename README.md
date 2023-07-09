# MonitoreoConBlackBox
Monitoreo de pagina de Blackbox con Grafana

# Tools
Dashboard Grafana de blackbox: https://grafana.com/grafana/dashboards/7587-prometheus-blackbox-exporter/

Repo de Blackbox: https://github.com/prometheus/blackbox_exporter

# Configuraciones Previas

En el Archivo docker-compose configuramos las paginas que seran monitoriadas
      - targets:
        - http://prometheus.io
        - http://caosbinario.com


# Ejecutar el Docker (Ejecutar con PowerShell)
    
    docker compose up
    

# Configuracion

### Prometheus

Se debe conectar el data sources
    
    http://prometheus:9090

### Grafana

    http://localhost:3000/
   
  
Configurar el Dashboard 7587





