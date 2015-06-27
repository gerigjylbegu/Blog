---
layout: post
title:  "Elementary OS like mac"
date:   2015-06-27 10:33:58
categories: software
tags: Linux Elementary
---

To make elementary os like macc you need a couple of things.First you need to now that elementary os freya doesn't support wingpannel yet so if you want to ,install an older version like Luna or Isis.
First write these on terminal:

---
sudo add-apt-repository ppa:gnome3-team/gnome3 && sudo add-apt-repository ppa:gnome3-team/gnome3-staging && sudo add-apt-repository ppa:ricotz/testing && sudo add-apt-repository ppa:elementary-os/daily && sudo apt-get update && sudo apt-get dist-upgrade -y
---

Now we need to get XGtk theme for elementary.Download the zip file [here](http://kxmylo.deviantart.com/art/Xgtk-theme-gtk-3-14-3-12-465195148),after this extract it to Downloads.
Than write in terminal:
---
sudo mv Downloads/XGTK /usr/share/themes/
---

If you're using Freya install elementary tweaks.

---
sudo add-apt-repository ppa:mpstark/elementary-tweaks-daily
sudo apt-get update
sudo apt-get install elementary-tweaks
---

<img src="http://1.bp.blogspot.com/-Rylts2gpKH4/VSz3nFNsFbI/AAAAAAAAWG8/t1dD-YXBbNU/s1600/elementary-tweaks-system-settings.png">

Open Elementary tweaks then choose the theme you want at Appereance changing Metacity Theme and GTK+ Theme to XGTK.
Now you need plank theme ,which you can download it [here](https://github.com/fsvh/plank-themes).Extract only Capeos file to Downloads then open terminal and write:

---
sudo mv Downloads/Capeos /usr/share/plank/themes/
---
Go to elementary tweaks,then plank and to Theme chose capeos.
The third thing you need to do is to install super wingpanel,but there is no version for freya yet.
This is how to make Elementary os like mac.
