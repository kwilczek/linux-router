# How to make a router out of a Linux machine

*What sort of a machine would be adequate?* Basically, any machine that has at least two wired network interfaces.
My home router is an old Thinkpad X230 with a single built-in Ethernet port; the second
one is a USB Ethernet adapter.

*Is it expensive to have such a router powered on all the time?* It might be, but it shouldn't
be. I tweaked my X230 to use about 10 W when idle (more about that later). If you are using
an RPi, it should be much less, depending on the version of the board.

*Why do I need a second router?* Routing will be only one of many things you will be able to
do with such a contraption. One of the most important things is that you will learn
while doing all those things mentioned below! :open_book: I assume that a person reading this likes to tinker
and has some basic knowledge on Linux :penguin: operating system. Debian is the system of my choice.

* ISP's routers have limited set of funcionalities.
* Some of those functions often do not work properly (like a DDNS client).
* The ISP's router might ocasionally pass some strange traffic to
  your network (by accident or not).
* Security or firmware updates for such routers are oftentimes non-existent.
* Usually, ISPs routers firmware is a closed source software.
* You may want to have a monitoring of your home devices or network.
* You may want a VPN server available to securely connect to your network.
* For this, it would be nice to have a working DDNS client.
* You may want to set up a secure backup solution.
* Do you have an old external drive? It would be great for a NAS and storing those
  secure backups (remmber that RAID is not a backup and to have a backup of your backup).
