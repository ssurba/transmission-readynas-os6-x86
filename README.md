# transmission-readynas-os6-x86

Latest version is: 2.92-0.01

This is a special build of Transmission client for current line of NETGEAR ReadyNAS OS6 systems on x86 architecture - ReadyNAS 300, 500, 700 series, 3220/4220 and others.  

You can download the add-on in the Releases section: https://github.com/ssurba/transmission-readynas-os6-x86/releases

##General notes:

* You may find release notes for Transmission on Transmission developers site: https://trac.transmissionbt.com/wiki/Changes.

* This package requires at least version 6.1.0 of the ReadyNAS OS. 

* Only transmission-daemon, client tools and Web interface are included in this package.

* Your NAS should be connected to the Internet while installing this package because several additional components will be downloaded.

* After starting the installation of the add-on there will be no indication of the process and Transmission will appear in the list of installed applications after a delay. So relax and wait for 2-3 minutes (depending on your Internet connection speed). You will get notification and message in the log after the add-on is completely installed.

* Once the add-on gets fully installed you should be able to access web interface from your browser by the following URL: http://[ip_address_of_your_NAS]:9091.

* Transmission network share will be created after installation. It provides access to downloaded files, Transmission configuration file (settings.json) and some other special files.

* Watch directory by default is located in Transmission share - \transmission\watch-dir. Put your .torrent files in it to start downloading.

* By default downloaded files are saved to /data/Transmission/downloads. You may later change download path in Transmission configuration.

**WARNING!** Before installing this version please **uninstall any other builds** of Transmission (versions not made by me) and **delete Transmission share** created by the other build. But you can keep previous version of my build and Transmission share created by it, newer version should use and upgrade them.

# Version changes:

## Version 0.01

* Release for GitHub.
