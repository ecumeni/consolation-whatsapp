# Hello World whatsapp-bot - search web

> Create a .env file 
SID=Twilio ACCOUNT SID
KEY=Twilio AUTH TOKEN 
APIKEY=Google API key (https://developers.google.com/custom-search/v1/overview > API key > Get a Key)
CX=Google Search engine ID (https://cse.google.com/cse/all > add > insert www.google.com > Create >>> Click control panel > Switch the ‘search the entire web’ button to on > get Search engine ID)

- npm install

- npm start

> download ngrok: https://ngrok.com/download

- ngrok http 3000

> add new ngrok server 'URL'+'/api/v1/incoming' (https://www.twilio.com/console/sms/whatsapp/sandbox - webhook URL WHEN A MESSAGE COMES IN)