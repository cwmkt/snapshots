<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2023/08/logo-github-cwmkt.svg" alt="DispZap Whats Marketing" width="240" />
<p align="center">Script bash simples para criar seu Snaps Hots na Contabo 🚀</p>
</p>
  
<p align="center">
<img src="https://whatsapp.com/favicon.ico" alt="WhatsAPP-logo" width="32" />
<span>Grupo WhatsaAPP: </span>
<a href="https://link.cwmkt.com.br/grupo-whats" target="_blank">Grupo</a>
</p>

<hr />
<hr />


Contabo: [Contabo VPS](https://contabo.com/en/vps/) Documentação: [Contabo API](https://api.contabo.com/).

```bash
git clone https://github.com/thenik/contabo-snapshot
```

```bash
nano /contabo-snapshot/config.conf
```

# credentials to use Contabo API

```bash
CLIENT_ID=my-ID-client
CLIENT_SECRET=my-client-secret
API_USER=my-contabo-API-username
API_PASSWORD='my-contabo-API-password
```

```bash
sudo apt install jq
```

## Executando o Script

1. Abra o arquivo de configuração do cron com o seguinte comando:
:~# crontab -e

2. Adicione a seguinte linha ao arquivo para executar o agendamento todos os dias à meia-noite (você pode ajustar o horário conforme necessário):
0 0 * * * /root/contabo-snapshot/contabo_snapshot.sh

ou

Caso possua N8N suba Worflow ContaboVPSSnapshot

Coloque suas crediciais do SSH 



















