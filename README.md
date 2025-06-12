# coding_chalenge

## TEIL 1 ##
Repositoy erstellen. In Settings unter Security pubic Key hinzufügen. Der Key ist erzeugt durch Kommando 
```
~/.ssh λ ssh-keygen -t ed25519 -f ./code_chalenge
```
Danach, ist mit 
```
cat code_chalenge.pub
```

## Teil 2: Ansible-Rolle ##

Nginx_play ist einfache Role für NGINX instalieren. 
Für .html file und NGINX config sind Vorlage genutzt.

## Teil 3: CI/CD Action ##

Workflow uses Docker Container für Ansible-lint um automatisch Code zu checken bei push.

## Teil 4: Dokumentation ##

Diese README ist kurz zusammengefasst was in Repo stehet.

