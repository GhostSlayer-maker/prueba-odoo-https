
# Docker Odoo 17.0 With PostgreSQL 16
by Angel

Primero instalar docker si no lo tiene
```
apt  install docker.io docker-compose -y
```

Descargar repositorio
```
git clone https://github.com/GhostSlayer-maker/prueba-odoo-https
```

Entrar al directorio
```
cd prueba-odoo-https
```
Iniciar docker por cualquiera de las vias que aportan diferentes fucionalidades
```
docker compose up -d
docker compose up -d --build
docker compose up --build
```

Detener odoo
```
docker compose down
```

Sitio local
```
http://localhost:10017/
```

Contraseña maestra de Odoo:
```
minhng.info
```
