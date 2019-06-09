# Maintainer: Jan Boelsche <jan@lagomorph.de>
pkgname=hide-cursor
pkgver=1.0
pkgrel=1
pkgdesc="Set icon-theme with invisible default cursor for auto-login user"
arch=('x86_64')
license=('GPL')
groups=()
depends=(
  'lightdm-autologin'
  'adwaita-invisible-default-cursor'
)

source=(
  'index.theme'
)

sha256sums=('7284c5e022eeac8a81b7d0bbc8ee7c168e5392960b0b0c1b9d50914ab0bf3451')

package () {
  install -Dm 644 -t "${pkgdir}/home/auto-login/.icons/default" "index.theme"
}
