INTRUCTIONS TO HARD RESTART: 


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
source bin/activate
cd relay-server
nohup python app.py &
cd 




```