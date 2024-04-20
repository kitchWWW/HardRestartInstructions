# INTRUCTIONS TO HARD RESTART: 


```
sudo systemctl start nginx



tmux new-session
cd BrianEllisSound/myActualWebsite/app/
node app.js
Ctrl+b d


tmux new-session
cd EarTalk/
node app.js
Ctrl+b d


tmux new-session
cd /home/ec2-user/sounds.pink/app
node app.js
Ctrl+b d


cd databending
source bin/activate
cd databendingserver
nohup python app.py &
cd 


cd relay
cd relay-server
nohup python app.py &
cd 


cd veemees
source bin/activate
cd /home/ec2-user/veemees/veemee.es
nohup python main.py &
cd 


export TMPDIR=/home/ec2-user/tmp

cd ai-deep-listening/
source bin/activate
cd /home/ec2-user/ai-deep-listening/ai-deep-listening/audiocap
nohup python app.py &

```