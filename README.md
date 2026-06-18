# INSTALADOR-WABOOT-FLOW
 
 FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/raphaelbat/INSTALADOR-WABOOT-FLOW && sudo chmod -R 777 INSTALADOR-WABOOT-FLOW && cd INSTALADOR-WABOOT-FLOW && sudo chmod -R 775 atualizador_remoto.sh && sudo chmod -R 775 instalador_apioficial.sh && sudo ./instalador_single.sh
```

Caso for Rodar novamente, apenas execute como root:
```bash 
cd /root/INSTALADOR-WABOOT-FLOW && git reset --hard && git pull &&  sudo chmod -R 775 instalador_single.sh &&  sudo chmod -R 775 atualizador_remoto.sh && sudo chmod -R 775 instalador_apioficial.sh &&./instalador_single.sh
```

Todos os Direitos Reservados. Proibida qualquer tipo de Copia deste Auto Instalador.
