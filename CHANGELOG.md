# Changelog

## 3.8-0.9.7-0.13.7-RC2 (2018/06/26)

* Include path error for custom plugins and themes

## 3.8-0.9.7-0.13.7-RC1 (2018/06/25)

* Add ruTorrent 3.8 web client
* Add option to remove core plugins of ruTorrent (default `erasedata,httprpc`)
* Add a boostrap (default) config for rTorrent in `/etc/.rtlocal.rc`
* Move `/var/rtorrent` to `/data/rtorrent`
* Use Nginx WebDAV module instead of Apache
* Compile Nginx from source for better performance
* Remove Apache2 and implement Nginx WebDAV
* Do not process entrypoint on `htpasswd` command
* Add reverse proxy example with Traefik
* Remove old docker tags `0.9.6-0.13.6` and `0.9.7-0.13.7`
* Do not persist runtime data
* Rename repository `rtorrent-rutorrent` (github and docker hub)

## 0.9.7-0.13.7-RC3 (2018/06/18)

* Force rTorrent process as a daemon through command flag
* Add .rtorrent.rc if not exist

## 0.9.7-0.13.7-RC2 (2018/06/17)

* Move runtime data in `/var/rtorrent/run`
* Enable WebDAV protocol on `downloads/complete` with basic auth

## 0.9.7-0.13.7-RC1 (2018/06/16)

* Upgrade to rTorrent 0.9.7 and libTorrent 0.13.7
* Base image updated to Alpine Linux 3.7
* Update c-ares to 1.14.0
* Update curl to 7.60.0
* Move `RTORRENT_HOME` to `/var/rtorrent`
* XMLRPC through nginx over SCGI socket with basic auth
* Do not expose SCGI port (use a local socket instead)
* Run the rTorrent process as a daemon
* Replace deprecated commands in `.rtorrent.rc`
* Review supervisor config

## 0.9.6-0.13.6-RC1 (2018/01/10)

* Initial version
