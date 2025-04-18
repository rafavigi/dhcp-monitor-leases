# dhcp-monitor-leases
Monitor de leases

Monitora em tempo real os IPs que emtram e saem, bem como: MAC address, Data/hora de expiração e hostname (se disponível no DHCP).

-----------------------------------------------------COMO INSTALAR---------------------------------------------------------------

No terminal bash
Extraia o arquivo:
tar -xzvf monitor-dhcp-service.tar.gz -C /
---------------------------------------------------
Recarregue os serviços:
sudo systemctl daemon-reexec
---------------------------------------------------
Ative o serviço:
sudo systemctl enable monitor-dhcp-leases.service
---------------------------------------------------
Inicie:
sudo systemctl start monitor-dhcp-leases.service
---------------------------------------------------
Verifique se está rodando:
sudo systemctl status monitor-dhcp-leases.service
---------------------------------------------------
