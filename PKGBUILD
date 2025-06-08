# Maintainer: @zstg <zestig@duck.com>
pkgname=stratmacs-config
pkgver=1.0
pkgrel=1
pkgdesc="Emacs configuration for StratOS"
arch=('any')
license=('GPL3')
depends=('emacs')
source=('.config')
md5sums=('SKIP')

package() {
    install -d "$pkgdir/etc/skel/.config"
    cp -r "$srcdir/.config/emacs" "$pkgdir/etc/skel/.config/"
    echo "Configuration files have been copied to /etc/skel."
    echo "You may copy these files to ~/.config/ and make any changes you wish."
}
