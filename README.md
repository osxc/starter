starter
=======

An osxc playbook, ready to be forked !


> **Warning:** This version of osxc is not compatible with the old one (called now legacy), you'll have to copy some old roles locally in order to make a smooth transition. On the other side, you can still use legacy and we will continue to accept your pull requests on legacy.

## Introduction

Welcome to osxc !

osxc is a simple configuration tool for OS X (in fact, it just makes it easier for you to use ansible on OS X).

You can reach our (temporarily not updated and old) [website](http://osxc.github.io) if you want to know more. But don't follow the instructions there to get started, just stay here for that !

## Get started

> **Warning:**: All of this is subject to change, just be sure you're able to reach this page to see the latest instructions when it'll be updated. Don't worry though, we will not change brutally the structure of your current repo (not like we did with legacy). All we are going to do is add a CLI tool.

> **Additional Note:** If you're installing system-wide `sudo ansible-galaxy install -r requirements.yml` otherwise edit `ansible.cfg` and comment out `roles_path:./roles` to install the roles in your osxc.starter fork before running **Step 5**.

1. Be sure to have the XCode Command-Line tools installed: `xcode-select --install`
2. Pip install Ansible: `sudo pip install ansible` (or `sudo pip install --upgrade ansible` if Ansible has already been installed via pip and needs upgrading to 1.8+)
3. While that's happening [Fork this repo](https://github.com/osxc/starter/fork) and then clone your fork anywhere you want on your machine: `git clone https://github.com:<yourname>/starter.git ~/src/osxc; cd ~/src/osxc`
4. Take a quick look at `configuration.yml` and `installation.yml` customizing to your liking.
5. Start osxc with `ansible-galaxy install -r requirements.yml && ansible-playbook desktop.yml`

At the end, you'll only need to repeat step 5.

Now you're ready to further tweak the configuration we gave you. Have fun ! (You may want to read the [Ansible documentation](http://docs.ansible.com/index.html) in this case ...)

## Learn More

If you want to get more documentation or just want to see what osxc can do for you, here's a [repository list on ansible galaxy](https://galaxy.ansible.com/list#/users/6499) where you can find all the publicly available roles for osxc.
