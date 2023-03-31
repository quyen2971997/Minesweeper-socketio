
# Just a Minesweeper Socketio Game
## March 31th 2023
### [💣 TRY IT OUT 💣](https://minesbg.click/)

![image](https://github.com/quyen2971997/Minesweeper-socketio/raw/main/images/minesbg.png)

### Rules ###
- It's Simple As An Ordinary Minesweeper Like [This](https://www.minesweeper.info/wiki/Strategy) **but**
- With a **big** big map (I'm currently testing in 1500x1500, it could be 10-times bigger)
- Adding some Battle royale feature (not really). To be little more competited, each 60s an amount of mines are pushed into the game.
- Every phase (60s), you will get an extra life ♥. If run out of ♥, you are Executed **☠**!
- Each 1 mine you've flagged, you're receiving some points
- At Ending-phases, which 2 last phases, you'll need to reach minimum of points.


### How it's made ###
- I chose **Django** as Backend to serve Socketio and **Phaser 3** as the face of the game
- Along with Django, **Python-socketio** is used and all are configured with **Nginx + Gunicorn**
- **Deployment** I deploy the game on a minimum cost Cloud Service (1 vCPU, 1GB Memory)
- I tested the game with 10 players in real-time and it takes about 8% of CPU (fast enough)
- **Phaser 3** is also important to make the game work, why I chose it instead of other JS frameworks? Cuz the documents are [insanely huge](https://phaser.io/learn) and [easy to find](https://labs.phaser.io/). Join the [Community](https://discord.gg/phaser)



### Other Demo Projects ###
- [**Even Odd Game — The Simple Gambling Smart Contract (Part I)**](https://github.com/quyen2971997/solidity-simple-roll-the-dice-game)
- [**Even Odd Game — Interact with Smart Contract (Part II)**](https://github.com/quyen2971997/django-even-odd-game-blockchain)



### About Me ###
- 💼 [LinkedIn](https://www.linkedin.com/in/quyen2971997)
- 📫 [Email: quyen2971997@gmail.com](https://gmail.com)
- 🚩 [Hackerrank](https://www.hackerrank.com/quyen2971997)
- 🖥 [Github](https://github.com/quyen2971997)

### THANK YOU! ♥♥♥
