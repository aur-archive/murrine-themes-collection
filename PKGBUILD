# Maintainer: Edoardo Maria Elidoro <edoardo.elidoro@gmail.com>
# Contributor: Alireza Savand <alireza.savand@gmail.com
# Contributor: Martin Lee <hellnest.fuah@gmail.com>

pkgname=murrine-themes-collection
pkgver=0.98.3
pkgrel=1
pkgdesc="A collection of Murrine GTK2 themes"
license=('GPL')
arch=('any')
url="https://launchpad.net/murrine-themes"
depends=('gtk-engine-murrine')
source=(https://launchpad.net/ubuntu/saucy/+source/murrine-themes/0.98.3ubuntu1/+files/murrine-themes_0.98.3ubuntu1.tar.gz)
sha1sums=('12c176406adccb2d4faba1adbf21f71e7aacd578')

package() {
  mkdir -p "$pkgdir/usr/share/themes"
  cd $srcdir/murrine-themes-0.98.3ubuntu1/
  mv usr/share/themes/* "$pkgdir/usr/share/themes/"
}
