# Aysu

Aysu is GPT-2 Telegram chatbot that's been relatively tuned for chatting. Feel free to make me PRs and I'll check out your code! The bot isn't 100% accurate all the time (why I coded in a /retry function.)

Since the bot consumes so much memory, I have it programmed in a round-robin sort of mode. Each input will reset a timer on your account ID, once the timer runs down the bot is free for other users to use. You will be notified when the timer runs down, and other users can see how much time is left and if the bot is in use.

### Installation/How to use:

Brief install instructions on Ubuntu 20/WSL.

I highly reccomend looking at the jupyter notebook/ipynb on google collab instead.

Install python3.7 (I think 3.6 might work as well, but not 3.8):

```
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.7
```

Install pip on python 3.7:

```
wget https://bootstrap.pypa.io/get-pip.py
python3.7 get-pip.py
```

Install requirements inside of bot folder after cloning repository:
```
python3.7 -m pip install -r requirements.txt
```

Note: You realistically need 16GB of ram or a 8GB video card. Otherwise you will wait forever.
You can use GPU functions with atleast a 8GB video card that supports cuda tooklit 10.0 and cudnn for cuda toolkit 10. This install also works on windows with python 3.7 and nvidia, you must run command prompt as admin running python 3.7 on windows.

Download the model:
```
python3.7 download_model.py 1558M
```

Set your telegram bot API key in src/GPT2-Learning.py
```
Replace "BOTKEY" with telegram bot token i.e. "1827396499:AAHifc06oS31oQ9L3TuCiZxD9EIfKPi0oWQ"
```

Run the bot:

If using python3 command:
```
./start.sh
```

If using python3.7 command:
```
python3.7 src/GPT2-Learning.py
```

You can edit start.sh to match your python command as you wish.

### Notes:

```
Aysu has a neural intelligence, she can think and decide. You can train X and Y train routes
```
