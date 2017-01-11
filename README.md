# Fedora-FreeBSD-dual-boot

Fedora 25 and FreeBSD 11

in Fedora 

cd cd /etc/grub.d/

emacs (or your favorite editor) 40_custom
add my 40_custom configuration

grub2-mkconfig >/boot/efi/EFI/fedora/grub.cfg

