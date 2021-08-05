# Aysu

Aysu is GPT-2 Telegram chatbot that's been relatively tuned for chatting. Feel free to make me PRs and I'll check out your code! The bot isn't 100% accurate all the time (why I coded in a /retry function.)

Since the bot consumes so much memory, I have it programmed in a round-robin sort of mode. Each input will reset a timer on your account ID, once the timer runs down the bot is free for other users to use. You will be notified when the timer runs down, and other users can see how much time is left and if the bot is in use.
