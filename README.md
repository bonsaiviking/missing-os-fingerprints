WANTED: OS Fingerprints!
========================

These IP addresses were scanned by the [Carna
botnet](http://internetcensus2012.bitbucket.org/paper.html) using
[Nmap](http://nmap.org/).  Nmap's OS detection scanner was able to grab
good-quality fingerprints for them, but the fingerprints didn't match anything
in our database.

How you can help
----------------

Please help the Nmap team! If you own or administer any of these IP addresses,
please install the [latest version](http://nmap.org/download/) of Nmap and run
the following Nmap command and [submit the
results](http://insecure.org/cgi-bin/submit.cgi?new-os):

    sudo nmap -O -sSU -T4 -d $IP_ADDRESS

Finding your IP addresses
-------------------------

The CSV files in this repository are sorted and split according to IP. If you
know which IP ranges you can help with, view the appropriate CSV file and use
Github's CSV filtering interface to find them. The files also have reverse-DNS
names where available, so you can search by domain name, too.

I don't own any of these IPs. Can I still help?
-----------------------------------------------

You bet! In order to stay on top of the hordes of new operating systems and
application versions that are released every day, Nmap needs the community to
scan and submit [OS
fingerprints](http://nmap.org/book/osdetect-unidentified.html) and [service
fingerprints](http://nmap.org/book/vscan-community.html).  Before you do, be
sure to [update to the latest version of Nmap](http://nmap.org/download/); this
will ensure that you don't submit something Nmap already knows about. Plus, you
will improve your view of your own network, and take advantage of new features,
fingerprints, and optimizations.
