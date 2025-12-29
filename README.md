# cloudmachine-website
Azure VM website met Docker en Traefik

# CloudMachine Website

Live website: https://CloudMachine.crabdance.com

## Technologieën
- Azure Virtual Machine (Ubuntu 24.04)
- Docker & Docker Compose
- Traefik Reverse Proxy
- Let's Encrypt SSL certificaten
- Nginx webserver

## Projectstructuur
- `Dockerfile` - Website container configuratie
- `docker-compose.yml` - Multi-container orchestration
- `traefik.yml` - Reverse proxy configuratie
- `index.html` - Website inhoud

## Automatische deployment
GitHub Actions workflow bij elke push.

## License
MIT License - zie LICENSE bestand.