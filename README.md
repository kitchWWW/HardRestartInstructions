# INTRUCTIONS TO HARD RESTART: 


```
sudo systemctl start nginx


tmux new-session -d -s my_website_session 'cd /home/ec2-user/BrianEllisSound/myActualWebsite/app; node app.js'
tmux new-session -d -s eartalk_session 'cd /home/ec2-user/EarTalk/; node app.js'
tmux new-session -d -s my_website 'cd /home/ec2-user/sounds.pink/app; node app.js'

cd /home/ec2-user/databending
source bin/activate
cd databendingserver
nohup python app.py &
cd 


cd /home/ec2-user/relay
source bin/activate
cd relay-server
nohup python app.py &
cd 


cd /home/ec2-user/veemees
source bin/activate
cd /home/ec2-user/veemees/veemee.es
nohup python main.py &
cd 


export TMPDIR=/home/ec2-user/tmp

cd /home/ec2-user/ai-deep-listening/
source bin/activate
cd /home/ec2-user/ai-deep-listening/ai-deep-listening/audiocap
nohup python app.py &

```

Old version with using tmux directly:
```

tmux new-session
cd /home/ec2-user/BrianEllisSound/myActualWebsite/app
node app.js
Ctrl+b d


tmux new-session
cd /home/ec2-user/EarTalk/
node app.js
Ctrl+b d


tmux new-session
cd /home/ec2-user/sounds.pink/app
node app.js
Ctrl+b d
```