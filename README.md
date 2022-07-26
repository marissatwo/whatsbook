# whatsbook 
WhatsApp BOT write in a book easily 💗

## Installation 
```
1. *optional Update your ubuntu server : 
$ apt update -y && apt upgrade -y

2. Install dependency :
$ apt install ffmpeg webp imagemagick git -y

3. *optional for ipv6 vps, you must install warp : 
$ wget -N https://cdn.jsdelivr.net/gh/fscarmen/warp/menu.sh && bash menu.sh

4. Go to Home (opsional):
$ cd $HOME

5. Download nodejs, for now i am using stable version (v16.13.2) and extract to /opt directory :
$ wget https://nodejs.org/dist/v16.13.2/node-v16.13.2-linux-x64.tar.xz

6. Extrack Nodejs :
$ tar -xf node-v16.13.2-linux-x64.tar.xz

7. Move to /opt :
$ mv node-v16.13.2-linux-x64 /opt/

8. edit ~/.profile :
$ nano ~/.profile

9. add this two lines then save :
export NODEJS_HOME=/opt/node-v16.13.2-linux-x64/bin
export PATH=$NODEJS_HOME:$PATH

10. after Save, dont forget to source your .profile file : 
$ source ~/.profile

11. Download script bot :
$ git clone https://github.com/imhunterand/whatsbook.git

12. go to Wangap directory :
$ cd whatsbook

13. Install library and dependency project :
$ npm install

14. *optional if you found vulnerabilities:, just audit fix
$ npm audit fix

15.Run Your bot:
$ node . 

16. Scan your QRCODE with your device to make your number as a bot, until success

17. And your bot ready to use, to test your bot work, just send a text to your bot number,type menu then enter.

18. how to make your bot script always running in background :

- stop your bot script with click ctrl + c
- go to your project bot whatsapp and install package : 
$ npm install forever -g
- type then enter : 
$ forever start index.js
- now your bot run in background, so you can exit or logout from your vps and bot still running.
- if you want to stop your bot : 
$ forever stop index.js 
```
After installation scan your ``QR-CODE`` 

### Credits
Thanks to all the amazing community [contributors for sending PRs](https://github.com/imhunterand/whatsbook/contributors).

<h1 align="left">
  <a href="https://wa.me/+6282113409538"><img src="https://www.transparentpng.com/download/whatsapp/d9NoMp-mobile-chat-whatsapp-clipart-transparent.png" width="380" alt="Contact WhatsApp"></a>
</h1>
