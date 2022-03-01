# HackCam
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![HackCam](https://techchip.net/wp-content/uploads/2020/04/HackCam.jpg)

# What is HackCam?
<p>HackCam is techniques to take cam shots of target's phone front camera or PC webcam. HackCam Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux/Termux):

```
git clone 
cd HackCam
bash HackCam.sh
```

## Change Log:

<p><b>Version: 1.0:</b> Add new online meeting template</p>
<p><b>Version: 1.0:</b> Ngrok authtoken update</p>
<p><b>Version: 1  :</b> Fix ngrok direct link</p>

### Video Demo

#### For More Video subcribe <a href="https://www.youtube.com/channel/UCz0kcxxp9gRbjnSZc7ID0SA">ITCyberClub YouTube Channel</a>
<p>HackCam is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
<p>HackCam is inspired by https://github.com/thelinuxchoice/ Big thanks to @thelinuxchoice</p>
