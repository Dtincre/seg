# seg
Este es el repositorio para la asignatura de Seguridad

# Comprobadores:
iptables -L -n -v
Comprueba los paquetes enviados del equipo

iptables -L
Muestra reglas aplicadas

iptables-save > /etc/iptables/rules.v4
Guarda las reglas directamente en la carpeta /etc/iptables/rules.v4.
Una vez reiniciado el pc las reglas se mantendrán guardadas en ese equipo

iptables-restore < /etc/iptables/rules.v4

# Importante
Instalar "iptables-persistant"
