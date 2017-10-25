# linux-stuff

code install
x86
wget  "https://az764295.vo.msecnd.net/stable/b813d12980308015bcd2b3a2f6efa5c810c33ba5/code_1.17.2-1508162326_i386.deb"
sudo dpkg -i code_1.17.2-1508162326_i386.deb
sudo apt-get install -f
sudo apt-get install libxss1
sudo sed -i 's/BIG-REQUESTS/_IG-REQUESTS/'  /usr/lib/i386-linux-gnu/libxcb.so.1
code

amd64
same as x86 vscode ms site


make a backup first
sudo sed -i 's/BIG-REQUESTS/_IG-REQUESTS/' /usr/lib/x86_64-linux-gnu/libxcb.so.1


sync settings extension -> 3a555813b2c69daaf78d9c83cb050c76

file->preferences->settings(ctrl+,) "keyboard.dispatch": "keyCode"

/usr/lib/x86_64-linux-gnu/libxcb.so.1
