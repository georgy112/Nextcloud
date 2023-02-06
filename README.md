# Nextcloud
Установка сервера Nexcloud 23 в Docker.

Компоненты:
- Apache
- SQLite

# Install Docker
https://docs.docker.com/engine/install/ubuntu/
sudo apt install -y docker-compose

# Create directory
  sudo mkdir -p /app/nextcloud/nextcloud/{apps,config,data}  
  sudo chown -R $USER:$USER /app/nextcloud/  
  cd /app/nextcloud  
  vim docker-compose.yml  
  sudo docker-compose up -d  
  sudo docker-compose down  
