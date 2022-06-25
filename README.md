# SGMahjongCalcTele
Telegram bot that helps track winnings based on the Singaporean mahjong rules <br>
https://telegram.me/sg_mj_bot  <br>
Deployed via Heroku webhook

## How to use
1. Clone this project to your server side.
    > git clone https://github.com/RyanTanYiWei/SGMahjongCalcTele.git
2. Install python dependencies with pip
    > pip3 install -r requirements.txt
3. Change the following
    > config.py token = "..." <br>
    > mjbot.py (url='...' + config.token)

## Commands
**/start:** Restart the Bot<br>
**/settings:** Manage Settings<br>
    > payrate, shooter, maxtai<br>
**/play:** Play the Game (start counting)<br>
    > tai, kang, animals, flowers, manual edits<br>
**/end:** End the Game (allocate payment) <br>

## Screenshots
<p align="center">
  /start <br>
  <img height = "400" src=https://github.com/RyanTanYiWei/SGMahjongCalcTele/blob/main/pics/start.jpg/>
</p>
<p align="center">
  /settings <br>
  <img height = "400" src=https://github.com/RyanTanYiWei/SGMahjongCalcTele/blob/main/pics/settings.jpg/>
</p>
<p align="center">
  /play <br>
  <img height = "400" src=https://github.com/RyanTanYiWei/SGMahjongCalcTele/blob/main/pics/play1.jpg/>
  <img height = "400" src=https://github.com/RyanTanYiWei/SGMahjongCalcTele/blob/main/pics/play2.jpg/>
 </p>

<p align="center">
  /end <br>
  <img height = "400" src=https://github.com/RyanTanYiWei/SGMahjongCalcTele/blob/main/pics/end.jpg/>
</p>
