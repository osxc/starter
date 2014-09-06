starter
=======

An osxc playbook, ready to be forked !


> **Warning:** This version of osxc is not compatible with the old one (called now legacy), you'll have to copy some old roles locally in order to make a smooth transition. On the other side, you can still use legacy and we will continue to accept your pull requests on legacy.
> **Warning:** The Makefile is temporary and will soon be deprecated. But for now, it will play nice while waiting for the CLI.

## Introduction

Welcome to osxc !

osxc is a simple configuration tool for OS X (in fact, it just makes it easier for you to use ansible on OS X).

You can reach our (temporarily not updated and old) [website](http://osxc.github.io) if you want to know more. But don't follow the instructions there to get started, just stay here for that !

## Get started

> **Warning:**: All of this is subject to change, just be sure you're able to reach this page to see the latest instructions when it'll be updated. Don't worry though, we will not change brutally the structure of your current repo (not like we did with legacy).

1. Be sure to have the XCode Command-Line tools installed: `xcode-select --install`
2. [Fork this repo](https://github.com/osxc/starter/fork)
3. Clone your forked repo anywhere you want on your machine: `git@github.com:<myname>/starter.git`; mv starter osxc; cd osxc`
4. Setup your system with `make setup`
5. Start osxc with `make osxc`

At the end, you'll only need to repeat step 5.

Now you're ready to tweak the configuration we gave you. Have fun !
