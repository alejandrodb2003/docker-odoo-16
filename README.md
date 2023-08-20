# Docker Odoo 16.0 With PostgreSQL 13
by Marlon Falcón

![Alt text](https://github.com/falconsoft3d/images/blob/main/odoo-docker-post.png?raw=true "Marlon Odoo")
```
apt  install docker.io docker-compose -y
git clone https://github.com/alejandrodb2003/docker-odoo-16.git
cd docker-odoo-16
docker compose up -d
docker compose up -d --build
docker compose up --build
```

Stop Odoo
```
docker compose down
```

```
git submodule add https://github.com/falconsoft3d/odoo_addons_3ros.git addons-customize/odoo_addons_3ros
git commit -m "Added the submodule to the project."
git push
```
http://localhost:8069/web/database/selector


```
admin password:
x1234567890
```
