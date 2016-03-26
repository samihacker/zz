IndexTG

A Telegram Bot based on plugins using [tg](https://github.com/vysheng/tg).

==================

```bash
# Tested on Ubuntu 14.04, for other OSs check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```

```bash
# After those dependencies, lets install the bot
cd $HOME #Do not write this if you are using c9 or not root accounts
git clone https://github.com/IndexTM/index.git
cd index
./launch.sh install
./launch.sh # Will ask you for a phone number & confirmation code.
```
You can also use this command to install the bot in just one step.
```bash
sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get autoremove && sudo apt-get autoclean && sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev -y && cd $HOME && rm -rf index && rm -rf .telegram-cli && git clone https://github.com/IndexTM/index.git && cd index && ./launch.sh install && ./launch.sh
```
Then, you have to install a bot language like this:
```
#install english_lang
#lang en
```

Enable more [`plugins`](https://github.com/yagop/Talibot/tree/supergroups/plugins)

------------

If your Linux/Unix comes with [upstart](http://upstart.ubuntu.com/) you can run the bot by this way
```bash
$ sed -i "s/yourusername/$(whoami)/g" etc/telegram.conf
$ sed -i "s_telegrambotpath_$(pwd)_g" etc/telegram.conf
$ sudo cp etc/telegram.conf /etc/init/
$ sudo start telegram # To start it
$ sudo stop telegram # To stop it
```

-------------------------------------

[![https://telegram.me/joinchat/DRVuDAjDa98OGV4UMRuFkw]

suport Group Index
-----------------
   thanx :

DBTeam

@Mammothcode

@FarsGeneral

@napson

@HackeD_o

@error_log

@black_hat_admin1

-------------------

   Sudo :

@black_hat_admin02 ( @SuperDeveloper )

@black_hat_admin03 (off)

-------------------

   chaneel :
   
   @BlackHatchannel
   
-------------------

   shared Github To channel :
   
   @PluginLua
   
 ------------------
 :-D
