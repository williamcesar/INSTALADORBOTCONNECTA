# INSTALADORBOTCONNECTA
 
 FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/williamcesar/INSTALADORBOTCONNECTA && sudo chmod -R 777 INSTALADORBOTCONNECTA && cd INSTALADORBOTCONNECTA && sudo chmod -R 775 atualizador_remoto.sh && sudo chmod -R 775 instalador_apioficial.sh && sudo ./instalador_single.sh
```

Caso for Rodar novamente, apenas execute como root:
```bash 
cd /root/INSTALADORBOTCONNECTA && git reset --hard && git pull &&  sudo chmod -R 775 instalador_single.sh &&  sudo chmod -R 775 atualizador_remoto.sh && sudo chmod -R 775 instalador_apioficial.sh &&./instalador_single.sh
```

Todos os Direitos Reservados aberto pode copiar e usar a vontade.
