---
layout: post
title: "Protect My Browsers"
subtitle: A native linux program to block advertisements, trackers and pixels across all your browsers!
author: Pranav Gaikwad
permalink: /protect-my-browsers
tags: [Internet Privacy, Ad Blocker]
---

When you use an online service for free, it's very likely that you're not the customer, you're the product. Most of such services use your personal information to show you relevant advertisements. There are endless ways through which websites collect your information. Most of them are beyond the comprehension of a general internet user. Believe it or not, your private information is more valuable than you think. It's not worth to give it away so easily only to get some relevant ads in return. If you think the same way as I do, take a step towards protecting your privacy. Install **Protect My Browsers**! It's a program for Linux which blocks annoying ads in all of your apps. Under the hood, it also blocks third-party trackers and pixels to prevent user profiling. User profiling is a technique that allows websites to control the content on your screen based on who you are.

### Why shouldn't I install a browser extension ?

When you install a browser extension, you essentially put trust in an unknown third party.

> Imagine asking a random stranger to deliver your private letters to your friend and requesting him not to read them. Would you do it?

Moreover, extensions help websites to identify users uniquely. I am no expert, but you can read more about [Browser Fingerprinting](https://www.eff.org/deeplinks/2018/06/gdpr-and-browser-fingerprinting-how-it-changes-game-sneakiest-web-trackers).

Apart from these 'not so obvious' reasons, one reason you should care about 'Protect My Browsers' is that it blocks ads in every app which connects to the internet, unlike browser extensions which only work in a browser.

### Installation

Protect My Browsers is available as an Ubuntu package. You can install it using following commands. 

```bash
sudo add-apt-repository ppa:gaikwad.pranav/gaikwadpranav

sudo apt-get update 

sudo apt-get install protectmybrowsers
```

For other Debian based linux distros, it is available as a standard .deb package. Download it at this link. 

For all other Linux users, I'll be happy to provide you with a source package along with installation instructions. Drop an email with subject 'Request PMB' to **contact [dot] apps [dot] pg [at] gmail [dot] com** to get a source package. The subject line is important in order to ensure a timely reply since my bot reads these messages and he is very dumb.

### Usage

Once the package is installed, you can start blocking ads by running following command in the terminal.

```bash
sudo protect-my-browsers --start
```

To stop blocking, run following command. 

```bash
sudo protect-my-browsers --stop
```

### Submit Bugs and Issues

Report bugs and issues to this email - **contact [dot] apps [dot] pg [at] gmail [dot] com**



