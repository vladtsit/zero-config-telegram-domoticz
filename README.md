# zero-config-telegram-domoticz

This is first try to make zero-config telegram bot based on information which is already exists in Domoticz
Requirements:
- Node-Red and Domoticz installed on same PC/RRi. Google for instrictions.
- Additional nodes: node-red-contrib-moment, node-red-contrib-telegrambot

To install - copy from flow.txt and past into tne flow in your Node-Red
Add Telegram bot config according to https://flows.nodered.org/node/node-red-contrib-telegrambot. You will need to create new bot via BotFather and obtail API token.

Voila!

Commands:
help - for this help
swt "name part" - show actionable list of swithes selected by "name"
sen "name part" - show sensors 
