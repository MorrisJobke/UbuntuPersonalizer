UbuntuPersonalizer for Natty
============================

Todo
----
* shortcuts on Helmut
* Picard

Main
----

* importing SSH keys

		sudo apt-get install git-core
		mkdir Projekte && cd Projekte
		git clone git@github.com:kabum/UbuntuPersonalizer.git
		git clone git@github.com:kabum/MailNotify.git
		git clone git@github.com:kabum/Skripte.git
		cd UbuntuPersonalizer
		./main

* settings
	* Chromium
	* Desktop Webmail
	* Shotwell
	* clock
	* disable sounds
* autostart apps
	* shortcuts (`xbindkeys`)
	* MailNotify (`/home/kabum/Projekte/MailNotify/main.py`)
* copy
	* music
	* Pidgin logs
* UbuntuOne
* [Pidgin icon override][1]
* [Google calendar][2]




Bruno
-----

	./bruno
	
* autostart apps
	* synergys

* adding `mod_fastcgi` to `server.modules` in `/etc/lighttpd/lighttpd.conf`
	
Helmut
------

	./helmut
	
* autostart apps
	* synergy (`~/Projekte/Skripte/SynergyClient.sh`)
	* autorotate (`~/Projekte/Skripte/RotateScreen.sh`)
* crontab (root)

		@reboot ~/Projekte/Skripte/UpDown.sh

* [VPN][3]
* energy managment

[1]: http://code.google.com/p/pidgin-icon-override/
[2]: http://linuxundich.de/de/ubuntu/google-kalender-in-gnome-integrieren/
[3]: http://www.tu-chemnitz.de/urz/netz/vpn/vpnc.html
