# Linux Useful Commands

### Simple Screen Recorder Command install
```
sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
sudo apt-get update
sudo apt-get install simplescreenrecorder
```

### Lightshot install
```
sudo apt-get install wine wget 
http://app.prntscr.com/build/setup-lightshot.exe
wine ./setup-lightshot.exe
```

### Dropbox Headless Install
```
32-bit:
    cd ~ && wget -O - "https://www.dropbox.com/download?plat=lnx.x86" | tar xzf -
64-bit:
    cd ~ && wget -O - "https://www.dropbox.com/download?plat=lnx.x86_64" | tar xzf -
    
    ~/.dropbox-dist/dropboxd
    
    sudo apt install nautilus-dropbox
    
    Start
         dropbox start [-i]
    Auto Start
        dropbox autostart y
```

### Linux GIMP (Photoshop) install
```
sudo apt-get install gimp 
```

### Avro install
```
wget "https://github.com/maateen/avro/releases/download/v2.0/avro_2.0-1_all.deb"
 
sudo dpkg -i avro_2.0-1_all.deb
  
sudo apt-get install -fy
  
ibus restart

Keyboard Layout
  ১ System Settings এ গিয়ে Keyboard Layout সিলেক্ট করুন।
  ২ Add Layout বাটন এ ক্লিক করুন (নিচে ছোট + চিহ্ন)
  ৩ Choose a Layout স্ক্রিন এ লিখুন Bengali
  ৪ একটি খুব সহজ Layout হচ্ছে Bengali (Probhat), ওটা সিলেক্ট করে ডাবল ক্লিক করুন।
Tips: সহজে Layout পাল্টানোর জন্য Shift+Caps Lock ব্যবহার করুন।
```

### Chromium Browser
```
sudo add-apt-repository ppa:canonical-chromium-builds/stage
sudo apt-get update
sudo apt-get install chromium-browser
```

### Wine Setup
```
sudo dpkg --add-architecture i386 
sudo add-apt-repository ppa:wine/wine-builds
sudo apt-get update
sudo apt-get install --install-recommends winehq-devel
```

### LAMP install
```
sudo apt-get install tasksel
sudo tasksel install lamp-server
```

### Brackets Code Editor Install
```
sudo add-apt-repository ppa:webupd8team/brackets
sudo apt-get update
sudo apt-get install brackets
```

### Unijoy Support
```
sudo apt-get install ibus-m17n m17n-db m17n-contrib ibus-gtk
ibus-daemon -xdr
```

### SASS install
```
sudo apt-get install ruby-full
sudo apt-get install gem
sudo gem install sass
```

### Git install
```
sudo apt-get install git
```

### Gulp install
```
sudo apt-get install npm
sudo npm install --global gulp
```

### Skype install
```
sudo apt-get update
sudo apt-get install skype skype-bin

Skype indicator to work properly:
    sudo apt-get install sni-qt:i386
```

### Sublime install
```
sudo add-apt-repository ppa:webupd8team/sublime-text-3
sudo apt-get update
sudo apt-get install sublime-text-installer
```

### VLC install
```
sudo apt-get install synaptic vlc
```

### Bangla Fonts Support
```
sudo apt-get install fonts-beng fonts-beng-extra fonts-lohit-beng-bengali;
apt-cache search bengali
```

### Unity Internet Speed Meter
```
sudo add-apt-repository ppa:fixnix/netspeed
sudo apt-get update
sudo apt-get install indicator-netspeed-unity
```

### Weather Check
```
~: curl wttr.in/your Location

~: curl wttr.in/brahmanbaria
```