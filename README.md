# Nextcloud
Установка сервера Nexcloud 23 в Docker.

Компоненты:
- Apache
- SQLite

# Install Docker

# Create directory
sudo mkdir -p /app/nextcloud/nextcloud/{apps,config,data}
sudo chown -R $USER:$USER /app/nextcloud/

sudo docker-compose up -d
sudo docker-compose down
