# s11-test-doc-BOURQUIN_OZGUN

## Ce qui différait de la documentation

Comme nous sommes sur Omarchy, nous avons dû remplacer apt par pacman -S.

Nous n’avons pas eu besoin d’effectuer cette commande : sudo ufw allow OpenSSH.

Pour OpenSSH, nous n’avons pas installé openssh-server, mais simplement openssh.

Le code qui devait être placé dans /etc/nginx/sites-available/monsite a dû être mis directement dans nginx.conf.

Mais toutes ces petites modifications étaient dues au fait que nous étions sur Omarchy.

Sinon, tout était très clair.
