# dhcp-monitor-leases
Monitor de leases

COMO INSTALAR

Extraia o arquivo:
tar -xzvf monitor-dhcp-service.tar.gz -C /

Recarregue os serviços:
sudo systemctl daemon-reexec

Ative o serviço:
sudo systemctl enable monitor-dhcp-leases.service

Inicie:
sudo systemctl start monitor-dhcp-leases.service

Verifique se está rodando:
sudo systemctl status monitor-dhcp-leases.service
