+++
title = 'Moving to Linux full time'
draft = true
date = 2024-07-07T10:13:47+01:00
categories = [
    "Computing"
]
tags = [
    "linux",
    "gaming",
    "programming"
]
+++

## I've always been a fan of Linux, but...

I have been a user of Linux for over a decade now. Ever since my first laptop, an ancient Dell Latitude with a Pentium M, was rendered a paperweight by applications dropping support for Windows XP, the newest version of windows that the computer could reliably run. A quick install of Ubuntu 12.04 managed to buy the computer well over 2 years of extended life until the backlight gave out and it was well and truly dead.

Ever Since then, every computer I've had has had a version of Linux installed alongside Windows. But I've never managed to move exclusively away from Windows as there has always been software that I've needed that didn't run on Linux, usually tools made by Microsoft themselves be it the Microsoft Office Suite at school or Visual Studio at university. 

And for the most part it wasn't an issue. Sure Windows 8 was a usability nightmare without 3rd party applications that re-added basic desktop functionality, and Windows 10 slowly but surely chocked to death on half baked features and adverts, it was all manageable with the right registry edits and workarounds. But it sure didn't feel good

## But everything changed when the AI attacked 

Windows 11 was already not amazing, it had all of the awful nonsense of Windows 10, combined with an ugly UI refresh, even more ads than Windows 10 and a requirement to have a microsoft account that was only getting stricter. At the start of this year however, Microsoft committed in my opinion possibly their biggest sin yet, with the announcement of their ~~spyware~~ AI companion tool Recall. A program that would constantly take screenshots of a users desktop, confidentiality be damned unless you use Microsoft's own tools exclusively. Now thankfully they walked back on this disaster waiting to happen and now its off by default, but with their previous track record, it could be very quietly turned on as part of a feature update at any second. 

## Do I even really need Windows? 

Day to day I use my PC for gaming, browsing the web, writing code and occasionally recording / editing music (I usually use a Mac for music work as any realtime audio work on Windows is an exercise in futility at the best of times). 

In my previous experience I had zero problems doing all bar one of these tasks on Linux, even less so since I switched to a IDE that isn't platform specific for the C++ work I do. The one thorn in my side was gaming. The last time I had tried to do any serious gaming on Linux I was confined to a handful of native ports, most of them Valves games or old boomer shooter source ports. But it had been years since I had tried playing anything in earnest and I knew there had been enormous amounts of development made with tools like Proton and DXVK (a conversion layer to translate Microsoft's proprietary Rendering API to the open standard of Vulkan),


## Making the switch 

After making full backups of the multiple drives in my PC I filled a Ventoy drive with about 5 different live CD ISO files. I had a pretty bad habit of distrohopping over the years and I wanted to make sure I was fully on board with a given distros setup before installing and not regret it a few weeks later. Just in case I still needed to switch, I set up my `/home`directory on a different partition so I could retain my user profile and directories, This is something I think should be the standard on Linux and wish that installers gave users an easier way of setting it up. 

I ended up trying Mint, Fedora, Manjaro PopOS and Debian before settling on Kubuntu, because it had good driver support, up to date packages and used the KDE desktop, which is currently my preferred desktop environment thanks to its looks and customizability. I may switch to KDE Neon once KDE 6 is more stable, but at the moment stability is the most important thing to me.

## Gaming on Linux, a pleasant surprise

The first thing I did once I installed Linux was reformat one of my other drives and set it up to be a drive for my games and then installed Steam from flatpak and grab a couple of games I play regularly to see how it performed.  One thing to keep in mind is that every other operating system that isn't windows uses case sensitive file paths, so its for the best to enable casefolding to mimic the windows environment on whatever drive you are gonna be installing Windows games onto, this is doubly important if you plan to do any game modding. 

The first game I tried was Sid Miers Civilization V (not exactly a taxing game I know) which was interesting because it has a native Linux port that works well enough, but when I downloaded the Windows version to run through proton I was amazed at just how well it ran. 


Emboldened by just how well Steam games went I looked to my physical game collection, specifically, Neverwinter Nights. After some research I found a program called Lutris, which acts as a frontend and install manager for games, and like Steam it worked absolutely amazingly. the game installed with less trouble than I had getting the game working on Windows 11.

Overall, I have installed about a third of my steam library and all of my physical games. out of all of those that I've tried I have only had two games give me issues, and both of them have easy workarounds.