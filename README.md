UbuntuPersonalizer for Natty
============================

* importing SSH keys

		sudo apt-get install git-core
		mkdir Projekte && cd Projekte
		git clone git@github.com:kabum/UbuntuPersonalizer.git
		git clone git@github.com:kabum/MailNotify.git
		git clone git@github.com:kabum/Skripte.git
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
* Pidgin embeddedvideo http://linuxundich.de/de/ubuntu/videos-direkt-im-chat-fenster-von-pidgin-betrachten/
* Google calendar http://linuxundich.de/de/ubuntu/google-kalender-in-gnome-integrieren/

Bruno
-----

	./bruno
	
* autostart apps
	* synergys
	
Helmut
------

	./helmut
	
* autostart apps
	* synergy (`~/Projekte/Skripte/SynergyClient.sh`)
	* autorotate (`~/Projekte/Skripte/RotateScreen.sh`)
* crontab (root)

		@reboot ~/Projekte/Skripte/UpDown.sh

* VPN http://www.tu-chemnitz.de/urz/netz/vpn/vpnc.html
* energy managment
