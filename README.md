# Instalation
1. clone repository
2. copy .env.original to .env
3. change owner of data to 1001:root `chown 1001:root data` 
4. start the container `docker compose up --build`

Maintenance
The container starts automatically on boot and restarts unless explicitly stopped
