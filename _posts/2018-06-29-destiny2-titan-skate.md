---
layout: post
title:  "How to Titan Skate in Destiny 2 Using AutoHotKey"
subtitle: "A simple way to have some fun in PVE"
date:   2018-06-29 6:03:00 -0400
background: ''
---

`DISCLAIMER: DO NOT USE THIS SCRIPT OR ANY OTHER SCRIPT IN PVP`

---

Hello Guardians! Today I will be showing you how to make an AutoHotKey script so that you can Titan Skate and pretend you are playing Destiny 1 again.

## Installing AutoHotKey

You can read the documentation [here](https://autohotkey.com/docs/Tutorial.htm#s11).

Or you can download the AutoHotKey installer below:

<a class="btn btn-secondary nounderline" href="https://autohotkey.com/download/ahk-install.exe">ahk-install.exe</a>

---

## Gear

While you do not NEED to use the Lion Rampant Titan boots, it does make skating a bit easier and you go a little faster.

Here is what I am running on my Titan when I am skating:

<img class="img-fluid rounded" src="https://puu.sh/AOfCm/d54bfb9026.jpg" alt="Titan Gear">

Also, make sure you are using "Catapult Lift" as shown below:

<img class="img-fluid rounded" src="https://puu.sh/AOfEU/38f230c3b0.png" alt="Catapult Lift">

Once you get that all sorted out in-game we can create the script.

## Creating an AutoHotKey Script

Right click on an empty part of your desktop and hover over **New** and then click **AutoHotKey Script**

A new file should appear on your desktop. Right click that `.ahk` file and open it using NotePad or NotePad++.

Delete all the text in the newly created file and then paste in this code:

```
z::
  While GetKeyState("z","P") { ;while "z" is held
  send, {Space}
  sleep 20 ;lower this if you need it faster
}
return
```

I use the <kbd>z</kbd> key, but you can change what key you would like the use simply by editing the script to any standard keyboard key. Just change every <kbd>z</kbd> in the script the key you prefer.

Also, the <code>sleep 20</code> means that the script will add a <code>20ms</code> delay between keystrokes. I have found that anywhere between <code>20ms</code> and <code>30ms</code> works. So you can edit that number as well if <code>20ms</code> is not working for you.

Once you have the script edited to your liking you can save it and name the file whatever you'd like. Then just double click the file when you want to use it.

When you are done and want the script to end find the small AutoHotKey icon in the icon tray and right click it and then close the script. It should be somewhere in here:

![Closing the script][exit]

Congrats! You can now Titan Skate in Destiny 2! Have fun and thanks for reading!

[exit]: https://puu.sh/AOfZk/a46eb758a5.png "Closing the script"
