# bashcast
Simple bash based podcast downloader

* Features:
	* Download only newest podcast
	* Option: delete old podcasts, so only the latest remains
	* Option: set id3tag Title and Artists
	* Option: Add id3 image to podcast
	* Option: create playlist with items in chronological order (new first)

* dependencies:
	* eyed3 (apt-get install eyed3)
	* id3tag (apt-get install libid3-tools)


* Install:
	* git clone -b 'master' --single-branch --depth 1 https://github.com/MiguSchweiz/bcaster.git
	* cd bashcast
	* chmod 755 bashcast
	* ./bashcast
	* edit ~/.bcast according your needs
	* ./bashacst
	* add cronjob with crontab -e

* Config example:
	* see file: config-example
