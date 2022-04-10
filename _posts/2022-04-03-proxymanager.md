---
layout: post
title: 'NginxProxyManager: A better Nginx'
date: 2022-04-03 04:00:00 +01:00
tags: web sysadmin networking proxy
comments: true
---

## What is NginxProxyManager?
NginxProxyManager, or NPM (not to be confused with the Node package manager), in essence is Nginx packaged together with a web interface and certbot in a Docker container.

## What does it have to offer?
With NPM, managing your reverse proxy could not be any easier. You can set up and edit all your hosts on a simple, well designed web interface. Pretty much anything you could need is at most a few clicks away, and even in case you need some very specific config, you can still just enter traditional Nginx config entries. Also, NPM handles setting up and refreshing your SSL certs via Let's Encrypt automatically! No need to fiddle around with certbot yourself!

## That sounds incredibly bloated!
My motto: "work smarter, not harder"
Sure, you can set up everything it does manually, but what do you gain from that? Is the overhead of an additional, small webserver really too much for you? In my opinion, the ease of use it provides outweighs the tiny amount of additional resource use. Instead of hacking away at a bunch of convoluted config files just to proxy some website (while also risking making a mistake and having to deal with an unreachable server), i can click a few buttons and go on to more important things. 

## Where do I sign up?
You can find NPM at [nginxproxymanager.com](https://nginxproxymanager.com), and a quick setup tutorial is [here](https://nginxproxymanager.com/guide/#quick-setup). Try it out, i bet you won't regret it!

## Disclaimer
Just to be clear, this is not an ad, i just like to show off cool stuff.