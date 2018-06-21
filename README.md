# bcaster
Simple bash based podcast downloader

* Features:
	* Download only newest podcast
	* Option: delete old podcasts, so only the latest remains
	* Option: set id3tag Title and Artists
	* Option: Add id3 image to podcast
	* Option: create playlist with items in chronological order (new first)

* dependencies:
	* eyed3 (`sudo apt-get install eyed3`)
	* id3tag (`sudo apt-get install libid3-tools`)


* Install:
	* `git clone -b 'master' --single-branch --depth 1 https://github.com/MiguSchweiz/bcaster.git`
	* `cd bcaster`
	* `chmod 755 bcaster`
	* `./bashcast`
	* edit ~/.bcast according your needs
	* `./bcaster`
	* add cronjob with crontab -e

* Config example:
	* see file: [config-example](config-example)
