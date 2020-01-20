git config --global http.sslVerify false
brctl showstp VLAN100

#voir l'etat des ports spanning tree
watch -n 1 'brctl showstp VLAN100|grep state
