# Docker-Konfiguration

Dieses Verzeichnis enthält alle Docker-bezogenen Dateien zur Containerisierung und Orchestrierung des Projekts.

## Inhalt

- **Dockerfiles:**  
  Separate Dockerfiles für Frontend, Backend und Python-Service.
- **Docker Compose:**  
  Eine `docker-compose.yml`-Datei, die alle Services (Frontend, Backend, Python-Service, MySQL) zusammen startet.

## Erste Schritte

1. Stelle sicher, dass Docker auf deinem System installiert ist.
2. Navigiere in diesen Ordner.
3. Starte das gesamte Setup mit:  
   ```bash
   docker-compose up --build
