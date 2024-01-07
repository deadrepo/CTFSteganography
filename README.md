#CTFStegranography
-------------------
How to Solve ?
-------------------

- Install stegseek + steghide with `sudo apt install stegseek_0.6-1.deb` + `sudo apt-get install steghide`

- Use stegseek command to brutefroce the passphrase `stegseek '/home/kali/Desktop/stegseek/gojo.jpeg' '/home/kali/Desktop/stegseek/rockyou.txt'`

Output
-------------------
![](stegseek.png)

- Use steghide command with megumi as passphrase `steghide extract -sf '/home/kali/Desktop/stegseek/gojo.jpeg'`

Output
-------------------
![](steghide.png)

- Flag found

Rockyou.txt file
-------------------
https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt

Stegseek deb file
-------------------
https://github.com/RickdeJager/stegseek/releases
