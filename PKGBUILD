# Maintainer: @zstg <zestig@duck.com>
pkgname=stratmacs-config
pkgver=1.0
pkgrel=1
pkgdesc="Emacs configuration for StratOS"
arch=('any')
license=('GPL3')
depends=('emacs')
source=()
install=stratmacs-config.install

prepare() {
    cp -r "$startdir/.config/" "$srcdir/"
}

package() {
    install -d "$pkgdir/etc/skel/.config"
    cp -r "$srcdir/.config/emacs/" "$pkgdir/etc/skel/.config/"
}
