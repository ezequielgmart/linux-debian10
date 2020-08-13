# De esta manera debe verse el archivo /etc/apt/Sources.list
# ------------------------- Copiar a partir de acá -----------------------

# deb cdrom:[Debian GNU/Linux 10.5.0 _Buster_ - Official amd64 DVD Binary-1 20200801-11:35]/ buster contrib main

# deb cdrom:[Debian GNU/Linux 10.5.0 _Buster_ - Official amd64 DVD Binary-1 20200801-11:35]/ buster contrib main

deb http://security.debian.org/debian-security buster/updates main contrib non-free
deb-src http://security.debian.org/debian-security buster/updates main contrib non-free

# buster-updates, previously known as 'volatile'
# A network mirror was not selected during install.  The following entries
# are provided as examples, but you should amend them as appropriate
# for your mirror of choice.
#
# deb http://deb.debian.org/debian/ buster-updates main contrib
# deb-src http://deb.debian.org/debian/ buster-updates main contrib
deb http://deb.debian.org/debian/ buster contrib non-free main
