# adhost_blocker

blocks known advertisement hosters using the user's hosts file.

the script reads latest adserver hosts from mvps.org, yoyo.org and malwaredomainlist.com.

i am using this script instead of browser-based adblockers like adblock plus etc. since those services started to team up with advertisers. 

i gotta admit, it's not as effective as the browserplugins, which allow wildcard url blocking etc. but it's ok to get rid of the most ads.

# Installation

Make a backup before you run this ;)

There is no installation. Just run the script with the appropriate user rights (/etc/hosts must be writable).
As your /etc/hosts file is overwritten by running this script, you should put permanent host definitions in /etc/hosts.orig .
Run the script in a cronjob to get latest updates of known hosts that are used
