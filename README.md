# Odoo-17-community

## Ubuntu • Debian

# Actualizamos el servidor ubuntu
> `sudo apt update && sudo apt upgrade -y`

# Instalamos POSTGRESQL
> `sudo apt-get install postgresql -y`

# Instalamos wkhtmltopdf
> `sudo apt-get -y install wkhtmltopdf`

# Clonamos el repositorio
> `wget -O odoo_17.0.latest_all.deb "https://nightly.odoo.com/17.0/nightly/deb/odoo_17.0.latest_all.deb"`


# Ejecuta el comando de instalación del paquete .deb usando el siguiente formato:
> `sudo dpkg -i odoo_17.0.latest_all.deb`

# Si aparece un mensaje de error indicando que faltan dependencias, ejecuta el siguiente comando para instalar las dependencias faltantes:
> `sudo apt-get install -f`
