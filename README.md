<h2><span style="text-decoration: underline;"><strong>🧑🏻 ha_person_card card for home assistant</strong></span></h2>

<p><img src="example/example1.jpg" alt="" /></p>

<p>Volevo condividere una scheda che ho creato con l'aiuto delle varie community per visualizzare le informazioni di una persona tramite l'utilizzo dell'app HA companion.</p>

<p dir="auto">Istruzioni:</p>

da Hacs, installare:
1. stack-in-card
2. mushroom

poi ...
1. nel file HA sensor.yaml, inserire il contenuto di person_card_lite_sensor.yaml, se non si dispone del file sensor.yaml è necessario creare sensor.yaml nella cartella config/, aprire il file configuration.yaml e inserire questa riga: sensor: !include sensor.yaml
2. sul vostro smartphone installare l'app Home Assistant companion
3. dall'app andate in impostazioni, app complementare, gestione sensori
4. abilitate tutti i sensori che servono e che trovare nei vari file di configurazioni: sensori di rete, sensori batteria, sensori di archiviazione, sensori di posizione.
5. in HA create una card manuale e incollate il contenuto del file: person_card_lite.yaml
6. all'interno del codice della card e del codice inserito nel sensor.yaml, dovete andare a sostituire tutti i miei sensori chiamati simone, con i vostri appena abilitati

<strong>Alla fine ci troveremo ad avere:</strong><br />
1. Persona con simbolo se è in casa o no (quindi nascosto la zona dove si trova, fa capire SOLO se è in casa o non in casa), nome, ultimo aggiornamento dei dati.
2. % batteria con cambio colore in base al livello, % memoria libera interna dello smartphone, tipo di rete (se è wifi o 5G)

Risultato finale:

<p><img src="example/example1.jpg" alt="" /></p>

<p>Enjoy!</p>

----------------------------------------
<p>Would you like to give me a hand?<br />The content of this page is completely free of charge and the purpose is certainly not to make money.<br />If you would like to lend me a hand to help with expenses and lost time, you have the following ways:</p>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C713VTGJ)

[![PayPal](https://github.com/Simonz82/desktop-tutorial/blob/main/paypal.svg)](https://www.paypal.com/paypalme/simongmail)

Make your Amazon purchases from this link:

[![Amazon](https://github.com/Simonz82/desktop-tutorial/blob/main/Amazon_logo.jpg)](https://amzn.to/3XWWTgz)

Join our Telegram channel dedicated to Home Assistant news:

[![Home_Assistant_News](https://github.com/Simonz82/desktop-tutorial/blob/main/home_assistant_news.jpg)](https://t.me/Home_Assistant_News)

Join our Telegram channel dedicated to home automation products, there are lots of offers:

[![Offerte Domotica](https://github.com/Simonz82/desktop-tutorial/blob/main/offerte_domotica.jpg)](https://t.me/offerte_domotica_ita)

