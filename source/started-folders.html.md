---
title: Create the Folder Structure
---

We will be compiling and installing all the packages into `/usr/local`. You may want to verify if this folder already exists and its contents before proceeding. The folder `/usr/local` does not exist on a fresh installation of OS X.

Create the necessary folders.

	sudo mkdir -p /usr/local/src
	sudo mkdir -p /usr/local/var/log
	mkdir -p ~/Library/LaunchAgents

Modify the ownership of `/usr/local` and its children to make yourself the owner.

	sudo chown -R $LOGNAME:staff /usr/local
