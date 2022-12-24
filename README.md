# Managing-a-door-contact-

In questo progetto cercho di sfruttare un sensor porta per più utilizzi. 

L'automazione è divisa in due parti: 
1)  Accende una luce quando si apre la porta per un tempo personalizzabile rispettando delle regole:
- Che sia topo il tramonto
- Puoi inserire switch e lisght
- La luce viene accesa/spenta solo se lo stato iniziale non era on
- La luce viene spenta dopo un tempo personalizzabile che inizia dal momento in cui viene chiusa la porta

2) Ricevere una avviso nel caso la porta fosse rimasta aperta per un tempo personalizzabile:
- Puoi decidere se abilitare notifica push.
- Puoi decidere se abilitare notifica TTS.
- Puoi decidere se abilitare notifica Alexa.
- Puoi personalizzare il testo della notifica.

### Requisiti:

Per poter utilizzare il progetto:
- Il sensore porta deve essere *device_class: door*.
- Avere almeno un'entità *media_player*.
- Almeno un dispositivo deve eseguire l'*app ufficiale* Home Assistant per ricevere le notifiche.

### Installazione

Per poter installare il progetto puoi importarlo tramitè il tasto ........
In alternativa puoi compiare il FILExxxxx  nella directory \config\blueprints\automation 
