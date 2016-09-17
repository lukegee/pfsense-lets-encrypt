This script facilitates the automatic download and installation of a Lets Encrypt certificate on pfSense (tested on 2.3.2).
Uses a separate NGINX process to allow for challenges.

Script must be placed in /root

le-server/conf/acme_mydomain contains the name of the domain on a single line with no newlines.
