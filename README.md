# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `config.json`
```json
{
  "port" : "3000",
  "channelAccessToken": "rAygb31Mi5QB0gUMZbnSFFrgM4tUilAYOf/CSUwkEzSfgjq1VyUFNXqzOf3JUijlsmwTW5ds0C9ndn30di82v4Ylsyp5TUlQhKDXT/qioTJIrfmfl2NrOQysjSSCpuZIwIUpavGxRnSekLBySkjmywdB04t89/1O/w1cDnyilFU=",
  "channelSecret": "c2e6575736947bec5d525456ffed6479"
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://ngrok.com/) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
