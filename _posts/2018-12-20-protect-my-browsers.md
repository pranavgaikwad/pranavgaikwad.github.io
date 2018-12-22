---
layout: post
title: "Protect My Browsers"
subtitle: A native linux program to block advertisements, trackers and pixels across all your browsers!
author: Pranav Gaikwad
permalink: /protect-my-browsers
tags: [Internet Privacy, Ad Blocker]
---

When you use an online service for free, it's very likely that you're being the product. You trade your private information to get relevant advertisements in return. I believe that your private information is more valuable than you think. It's not worth to give it away so easily merely to see some relevant content on your screen. If you think the same way as I do, take a step towards protecting your privacy. Install **Protect My Browsers**! It's a program for Linux which blocks third party advertisement providers, trackers and pixels without having to install extensions in your browsers.

### Why shouldn't I install a browser extension ?

When you install a third party browser extension, you essentially put trust in an unknown third party.

> Imagine asking a random stranger to deliver your secret letters to somebody and asking them not to tell anyone.

Moreover, extensions help websites to identify users uniquely. I am no expert, but you can read more about [Browser Fingerprinting](https://www.eff.org/deeplinks/2018/06/gdpr-and-browser-fingerprinting-how-it-changes-game-sneakiest-web-trackers).

### Installation

Protect My Browsers is available as an Ubuntu package. Run following commands in terminal to install. 

```bash
sudo add-apt-repository ppa:gaikwad.pranav/ppa

sudo apt-get update 

sudo apt-get install protect-my-browsers
```

For other Debian based linux distros, it is available as a standard .deb package. Download it at this link 

For all other Linux users, I'll be happy to provide you with a source package along with installation instructions. Drop an email to **contact [dot] apps [dot] pg [at] gmail [dot] com** to get a source package.

### Usage

Once the package is installed, you can start blocking ads by running following command in the terminal.

```bash
sudo protect-my-browsers --start
```

To stop blocking, run following command. 

```bash
sudo protect-my-browsers --stop
```

### See the difference