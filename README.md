![image](https://raw.githubusercontent.com/instagrambot/instabot.ai/master/img/banner.png)
[![Telegram Chat](https://camo.githubusercontent.com/67fd2a1c7649422a770e7d82cb35795c2a8baf32/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636861742532306f6e2d54656c656772616d2d626c75652e737667)](https://t.me/instabotai)
---
### [Website](https://instascraper.github.io/) | [Read the Docs](https://instascraper.github.io/docs/) | [Contribute](https://github.com/instagrambot/docs/blob/master/CONTRIBUTING.md) | [Buy Instagram Expert Marketing](https://www.fiverr.com/hourapp/grow-your-instagram-followers-for-7-days)
---

Instagram scraper which scrapes peoples images use machine learning to recognise a face, if face
is detected it will repost, Like and Comment that photo.

## Face detection at work on a live webcam 

![image](https://res.cloudinary.com/practicaldev/image/fetch/s--qdvR8Vl8--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://cloud.githubusercontent.com/assets/896692/24430398/36f0e3f0-13cb-11e7-8258-4d0c9ce1e419.gif)

Script now saves user session and and have CLI session. 
I also integrated it with instabot api.
90% of it are junk code I will fix it later.

This script scrapes images from users and then repost them under your Instagram accounts with your own tags.

Demo:
https://www.instagram.com/siliconeheaven/
## Requirements
* Python 3.6+

The script does not work with new accounts. If you know how to fix, send me a message. 

## To install script with Docker:
```
git clone https://github.com/reliefs/Instagram-scraper-with-autopost.git

cd Instagram-scraper-with-autopost

Docker build .

Docker run [imageid] -u username -p password -l therock,kimkardashian
```

## To install script on Windows:

### Install Cmake 
download link : https://github.com/Kitware/CMake/releases/download/v3.14.1/cmake-3.14.1.zip

### Install Dblib
Download dlib ‘.wheel’ file as ur system requirnment (use link bellow)
download link : https://pypi.python.org/simple/dlib/

```
Open cmd navigate to dlib wheel file path and hit command
pip install dlib_file_name.wheel
```

### Then run

``` bash
git clone https://github.com/instagrambot/Instagram-scraper-with-autopost --recursive
```

```
cd Instagram-scraper-with-autopost
```

```
pip install -r requirements.txt
```

```
Run: python example.py -u yourusername -p password -l therock,kimkardashian
```

And press Enter.


## To install script on Linux:
```
Ubuntu:
apt-get install python-dev python3-dev
sudo apt install g++
sudo apt install cmake
sudo apt install python3-pip

Arch Linux:
sudo pacman -S python3-dev
sudo pacman -S cmake
sudo pacman -S python3-pip
```

First, make sure you have dlib already installed with Python bindings:

  * [How to install dlib from source on macOS or Ubuntu](https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf)
  

### Then do

```
git clone https://github.com/reliefs/Instagram-scraper-with-autopost.git

cd Instagram-scraper-with-autopost

sudo pip install -r requirements.txt

Run: python example.py -u yourusername -p password -l therock,kimkardashian
```

## Troubleshoot
If you are getting Illegal Instruction with face_recognition follow this guide:
https://github.com/ageitgey/face_recognition/issues/11#issuecomment-475482716

AttributeError: 'module' object has no attribute 'face_recognition_model_v1'

Solution: The version of dlib you have installed is too old. You need version 19.7 or newer. Upgrade dlib.

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE TERMS AND CONDITIONS FOR COPYING, DISTRIBIUTION AND MODIFICATION.

0. You just do WHAT THE FUCK YOU WANT TO.
