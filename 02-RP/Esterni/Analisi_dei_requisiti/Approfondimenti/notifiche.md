##Appunti su notifiche in grafana

Grafana permette di inviare notifiche su Telegram, Microsoft Teams, Discord, Slack (tramite webhook), email, e molti altri servizi...
Per abilitare le notifiche si procede alla configurazione di un canale di notifica (sotto il menù degli alert).

#####Opzioni di un canale di notifica:
- frequenza delle notifiche: imposta l'intervallo di tempo minimo tra una notifica e l'altra
- le notifiche vengono inviate sia all'attivazione che alla disattivazione degli alert, utilizzare l'opzione "disable resolve message" per modificare questo comportamento.
- può essere allegata nella notifica l'immagine dello stato attuale del grafico

####[Tutorial integrazione con Slack](https://medium.com/@_oleksii_/grafana-alerting-and-slack-notifications-3affe9d5f688)

####Integrazione email
È richiesto un account email dal quale verranno inviate le notifiche, va inserito nelle [impostazioni SMTP](https://grafana.com/docs/grafana/latest/installation/configuration/#smtp) nel file di configurazione di Grafana.
A questo punto basterà procedere con la configurazione di un nuovo canale di notifica.

#####Personalizzazione delle notifiche
Dalle impostazioni dell'alert di un pannello è possibile personalizzare il testo e l'aspetto delle notifiche collegate all'alert.
