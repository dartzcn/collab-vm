# CollabVM
This page contains details about CollabVM, what it is, the links to the source code, how to host it, the requirements for hosting it, and other things.

# Where is the source code?
The "CollabVM source code" is ambiguous as there are multiple components to the site that are open source. CollabVM is fully open source; all components you see on the website are open source. 

* [collab-vm-server](https://github.com/computernewb/collab-vm-server) - This is basically the "heart" of CollabVM: It handles pretty much everything. This will allow you to host your own collab-vm mirror or host a VM for another person if you want to. You can either compile it yourself or use the pre-made binaries.

* [collab-vm-web-app](https://github.com/computernewb/collab-vm-web-app) - This contains the source to the web backend, which includes the Javascript and HTML. This will allow you to either compile the default web backend, or you can customize the theme or the Javascript if you want to.

* [collab-vm-admin-web-app](https://github.com/computernewb/collab-vm-admin-web-app) - This contains the source to the admin panel web backend, which includes the Javascript and HTML. This will allow you to customize the administrator panel to your liking. You can customize the theme, Javascript, etc (very similar to the collab-vm-web-app and compiled in the same way.)

* [collab-vm-agent](https://github.com/computernewb/collab-vm-agent) - This contains the source to the CollabVM Agent and the CollabVM Agent Loader, which powers the Virus Farm. 

# Requirements for hosting
* You need a Linux machine, preferrably one running Ubuntu 14.04 or higher (although not necessarily required). You can also compile and run this on Windows (requiring Windows Vista SP2 and up), although the Windows version is unstable and not very functional at this time (although in the future much better Windows support is planned). There is currently no Mac OS version (mainly because I don't have a Mac) but you can at least compile and run it on a Mac (tested on OS X Yosemite 10.10).

* You should probably have at least 1 GB of RAM. collab-vm-server itself requires about 64 MB of RAM in total, but of course this would not be optimal unless you were hosting a VERY low-end VM. So to have a mid-end VM, we recommend having at least 1 GB of RAM (for 512 MB RAM VMs) or 2 GB of RAM (for 1 GB of RAM).  If you're hosting multiple virtual machines, we recommend having a minimum of 2 GB of RAM.

* CollabVM requires about 40 MB of space in total. I'm going to assume you have that.

# FAQs

## If I make a fork of CollabVM Server/Webapp/etc, can it be closed source?
You do not need to redistribute the source code to your CollabVM fork: However, in accordance with the Apache license; you must list all modifications that you have made to the software somewhere. Also, if it contains bug fixes, really cool new features, or something else, I always appreciate the help!

## Do I need to give attribution for my fork?
You don't need to give attribution to the CollabVM dev team for the software, but it is always appreciated.

## Can my CollabVM mirror be private?
Your CollabVM mirror may be private or public; it's up to you.

## Is there any risk to hosting this?
If you have a net nic enabled on your virtual machine, anyone can do anything on your internet connection. Also, if you're hosting this from home, you may want to isolate your VM from your host, since users may be able to access your router configuration if you configure it improperly.

## Are chat bots allowed?
Some users have created chat bots and until now there has not been very much of an official statement. On the official CollabVM website, chat bots are allowed, but there are a few rules they must follow. 

* Chat bots may not spam the chat. This will result in the bot being banned.
* Chat bots may not start vote resets or participate in any vote resets. This includes commands which allow it to vote yes/no or start a vote reset. 
* Chat bots may take turns, but they may not rack up turns or perform destructive actions constantly.
* Chat bots are allowed to respond to users, but they must have a direct way of doing so (e.g., "Chatbot, how are you?"). Chat bots that respond to EVERY message are considered to be spammers.
* Chat bots must follow all the rules seen in the Rules page.
* Chat bots may have any command so long as it follows the above rules.

## There is a page called "Collab VM Default Page" when I go to the root page, what is the purpose of this?
This page is here so users on your website can check which version of Collab VM you are running, and is also there to ensure web admins that they have properly configured the site, as well as a little guide on how to access the admin panel. You don't have to keep this page if you don't want to, it's completely optional. You can also modify it in any way that you want to.

## Is it possible to host Collab VM for my family / on my LAN?
Yes, although there is no official "LAN" mode for Collab VM, just keep the port closed to the internet and it will effectively achieve the same thing.

## Does Collab VM have any other themes I can use?
Collab VM does have other themes, although they are not included with the regular Web App, which just uses the default Light theme. However, there are several different themes on the official website that you can use on either Collab VM or your own website if you so desire.

* [Dark Metro](http://computernewb.com/collab-vm/themes/dark-metro/) (Dark metro-styled theme by LoveEevee.)
* [Embedded](http://computernewb.com/collab-vm/themes/embedded/) (Based on Windows XP Embedded theme)
* [Experimental](http://computernewb.com/collab-vm/themes/experimental/) (Dark theme similar to Light theme, named after Experimental VM.)
* [Material](http://computernewb.com/collab-vm/themes/material/) (Custom theme by CtrlAltDelete.)
* [Metro](http://computernewb.com/collab-vm/themes/metro/) (Metro-styled theme by LoveEevee.)
* [Royale](http://computernewb.com/collab-vm/themes/royale/) (Based on Windows XP Royale theme, although it's unrecommended to use, and actually serves mostly as a base to create custom themes.)
