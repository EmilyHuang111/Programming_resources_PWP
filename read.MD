Router ip stuff
https://iotbytes.wordpress.com/raspberry-pi-ip-network-configuration/ 
route -n to check the ip address connection
sudo route add default gw 192.168.1.1 wlan0
For editing in vi: vi filename.python copy paste or k to go up, j to go down, i to insert and make changes, esc to escape insert mode and :wq to save 
https://www.redhat.com/sysadmin/introduction-vi-editor#:~:text=Vi%20edit%20modes&text=To%20enter%20Insert%20mode%2C%20press,press%20the%20Esc%20key%20once.
For deleting vi stuff :%d, :wq 
https://www.tutorialspoint.com/how-to-delete-all-text-in-a-file-using-vi-vim-editor 
Basically if git gets too complicated its better to use these commands, than git pull git fetch --all, git reset --hard origin/main
https://tomkadwill.com/git-reset-or-git-pull
Link for setting static ip address
https://www.tomshardware.com/how-to/static-ip-raspberry-pi 
pip install pytz

https://stackoverflow.com/questions/3961859/how-to-copy-to-clipboard-in-vim 
copy selected part: visually select text(type v or V in normal mode) and type :w !pbcopy
copy the whole file :%w !pbcopy
paste from the clipboard :r !pbpaste
ssh-keygen -R {hostname} (for security error VERY DANGEROUS)
find /etc | grep swp
rm filename
https://iotbytes.wordpress.com/raspberry-pi-ip-network-configuration/ for static ip		
NEW PASSWORD: BETA

In order to run the server:
-cd GUI_Python_Project
-python3 app2.py
-used git clone for the server

In order to run the python client
-NO NEED TO SSH (client is on the terminal)
-(These are the files in the directory) main.py, GUI.py, login.py, register.py
-python3 main.py
-used vi
Libraries that are needed to be imported:
-pip3 install requests
-sudo apt-get update
-sudo apt-get install python3-tk
-pip3 install pytz
git clone https://github.com/EmilyHuang111/pythonclientFinal.git
-pip3 install urllib3==1.26.7

In order to run the webcam stuff

-used vi
-imported adafruit and solved some errors


Web Server
-cd GUI_Python_Project
-through github
-python3 new_app.py
Git clone

Python Client
-vi on terminal
-python3 main.py
-Paste the files directly into the terminal 

pip3 install requests
pip3 install scikit-image
pip3 install numpy
pip3 install Pillow
pip3 install pytz
pip3 install Flask
pip3 install Flask-Bcrypt
pip3 install Flask-CORS
pip3 install adafruit-circuitpython-motor
-Also all the opencv libraries








