## Manual :
This is a very basic and simple Keylogger which simply sends the keystrokes recorded by the keylogger to the attacker over SMTP

-----
## How to execute this :
1. Clone the repo :
```bash
git clone https://github.com/sulaimanxmb/Side-Projects.git
cd Side-Projects/Keylogger
```

2. Change the EMAIL and EMAIL_APP_KEY in your [zlogger.py](zlogger.py) script

3. Send this to the victim (Might be via social engineering or packed in executable)

-----
## Note :
1. For this to run both [keylogger.py](keylogger.py) and [zlogger.py](zlogger.py) must be in same directory

2. Your Email and Email app key are not encrypted and are in plain text so this is more dangerous than the Keylogger itself

3. If packed into executable this is a very basic Keylogger so might be detected easily through signature
------