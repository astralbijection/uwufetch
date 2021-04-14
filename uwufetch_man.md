% UWUFETCH(1) uwufetch 1.2
% TheDarkBug
% April 2021
<!---
I am using markdown instead of troff because i don't know how to use it, and the same could be for some people.
I also don't know if this is a good practice, but it works, so I am keeping it.
To "compile" this file you need pandoc (https://pandoc.org).
--->
# NAME
uwufetch - A meme system info tool for Linux, based on nyan/uwu trend on r/linuxmasterrace.

# SYNOPSIS
**uwufetch** [*OPTIONS*] [*ARGUMENTS*]\

## OPTIONS
-a	--ascii\
prints the logo as ascii text (default)

-c	--custom\
you can choose a custom image path

-d	--distro\
you can choose the logo to print by the distro name

-h	--help\
prints a help page

-i	--image\
prints image instead of ascii logo

-l	--list\
prints a list of all supported distributions

# SUPPORTED DISTRIBUTIONS
Distribution name\	\	\	\	\ -d option

Nyalpine\	\	\	\	\	\	\	\	\	alpine\
Nyarch Linuwu\	\	\	\	\	\	\ arch\
Nyartix Linuwu\	\	\	\	\	\	\ artix\
Debinyan\	\	\	\	\	\	\	\	\	debian\
Fedowa\	\	\	\	\	\	\	\	\	\	\ fedora\
GentOwO\	\	\	\	\	\	\	\	\	\ gentoo\
GnUwU gUwUix\	\	\	\	\	\	\	guix\
Miwint\	\	\	\	\	\	\	\	\	\	\ linuxmint\
Myanjawo\	\	\	\	\	\	\	\	\	manjaro\
Myanjawo AWM\	\	\	\	\	\	\	\\"manjaro-arm\\"\
OwOpenSUSE\	\	\	\	\	\	\	\	\ \\"opensuse-leap\\"\
Pop OwOs\	\	\	\	\	\	\	\	\	pop\
RaspNyan\	\	\	\	\	\	\	\	\	raspbian\
UwUntu\	\	\	\	\	\	\	\	\	\	\ ubuntu\
OwOid\	\	\	\	\	\	\	\	\	\	\ \\"void\\"\
Nyandroid\	\	\	\	\	\	\	\	\ android\
Unknown (tux logo)\	\	\	\	\ unknown

--image/ascii only distributions--\
endeavOwO\	\	\	\	\	\	\	\	\ endeavour\
KDE NeOwOn\	\	\	\	\	\	\	\	\ neon\
nixOwOs\	\	\	\	\	\	\	\	\	\ nixos\
Swackwawe\	\	\	\	\	\	\	\	\ slackware\
sOwOlus\	\	\	\	\	\	\	\	\	\ solus\
FweeBSD\	\	\	\	\	\	\	\	\	\ freebsd\
OwOpenBSD\	\	\	\	\	\	\	\	\ openbsd

# DESCRIPTION
Uwufetch is a program inspired by neofetch and ufetch, that takes system informations\
and prints them in the terminal in an UwU way, with and UwU ascii logo or image.

# EXAMPLES
uwufetch -d arch\	\	\	\	\	\	\	\	\	\ # prints arch logo\
uwufetch -\-custom some_image.png\ \	# prints custom image (does not need full path)\
ueufetch -i -d artix\	\	\	\	\	\	\	\ # prints artix image

# DEPENDANCES
lshw\	\	better gpu info\
viu\	\	\ print images instead of ascii logo\
kitty\	\ better image viewing

All of this are optional, there is no necessary dependancy.

# LICENSE AND COPYRIGTH
uwufetch is provided under the GPL3 license, for copyright info read https://github.com/TheDarkBug/uwufetch/tree/main/res/COPYRIGHT.md.