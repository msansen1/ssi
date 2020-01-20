git config --global http.sslVerify false
brctl showstp VLAN100

#voir l'etat des ports spanning tree
watch -n 1 'brctl showstp VLAN100|grep state

arreter l'interface eth0 de S3 et voir l'effet sur S2 qui passe en forwarding sur ses deux interfaces
