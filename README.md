# Nextcloud
Установка сервера Nexcloud 23 в Docker.

Компоненты:
- Apache
- SQLite или PostgreSQL

# Install Docker
  https://docs.docker.com/engine/install/ubuntu/  
  sudo apt install -y docker-compose  
  sudo systemctl start docker && sudo systemctl enable docker  
  sudo groupadd docker  
  sudo usermod -aG docker $USER  

# Create directory
  sudo mkdir -p /app/nextcloud/nextcloud/{apps,config,data}  
  sudo chown -R $USER:$USER /app/nextcloud/  
  cd /app/nextcloud  
  vim docker-compose.yml  
  sudo docker-compose up -d  
  sudo docker-compose down  
