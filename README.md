Script para configuración de cPanel

Este script instala y configura cPanel según las buenas prácticas recomendadas por WNPower

Modo de uso: wget raw.githubusercontent.com/gdlservers/Cpanel/main/install_cpanel.sh -O ./install_cpanel.sh  && bash install_cpanel.sh

NOTA: Instalar sólo en CentOS 7 Minimal

Tareas que realiza:
Optimización de configuración de red
Configura los DNS
Instala el paquete "Base" y otros más recomendados
Optimización de configuración de SSH
Instala cPanel si no lo detecta
Configura Tweak Settings con los valores recomendados
Configura AWStats como sistema de estadísticas
Deshabilita compiladores
Configura complejidad mínima de passwords
Habilita php open_basedir protection
Deshabilita Shell Fork Bomb Protection (genera problemas con los límites en servidores con alto consumo)
Deshabilita SMTP Restrictions (en pos de utilizar SMTP_BLOCK de CSF)
Configura Apache con los valores recomendados
Configura Exim con los valores recomendados
Configura Pro-FTPd con los valores recomendados
Configura los features "disabled" y "default" con los valores recomendados
Instala y configura CSF Firewall con los valores recomendados
Configura valores recomendados de MySQL
Configura todos los php.ini con los valores recomendados
Crea el paquete "default" con los valores recomendados
Sincroniza la hora del servidor con un servidor NTP
