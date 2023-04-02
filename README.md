# tor-grafana
Monitoring TOR relays mit Grafana


Eine gute Möglichkeit um seine TOR relays zu überwachen (Bandbreite, Verbindungen usw.) ist Grafana. 
Da man einige Dinge beachten und einrichten muss um TOR relays mit Grafana überwachen zu können habe ich einmal alles zusammengestellt und beschrieben was man machen muss um das ganze aufzusetzen. 

Wenn Ihr Fragen habt könnt Ihr mich gerne unter relay7791@gmail.com - ich bin euch gerne behilflich. 

Ihr müsst verschiedene Dinge installieren und Dateien anpassen - das ganze muss sorgfältig passieren da Ihr sonst keinen Erfolg haben werdet. 

Ich habe das ganze mit Docker aufgesetzt - Ihr könnt die Installation aber auch auf konventionellem Weg anpassen. 

Benötigte Software: 

- Grafana
- Prometheus
- Nginx
- Prometheus-Node-Exporter
- apache2-utils

Bei Nutzung von Docker: 

- Docker
- Docker Compose 
- evtl. Portainer


Diese Beschreibung ist für einen Server mit Debian gedacht - bei RHEL etc. können einige Dinge anders sein. 
