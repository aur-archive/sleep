pkgname=sleep
pkgver=0.4
pkgrel=1
url=('http://check_the_pkgbuild')
pkgdesc="A daemon that sleeps for a number of seconds"
license=('GPL')
arch=('any')
depends=()
makedepends=()
source=('sleep')
md5sums=('430da1243a9b3da1f1e6d75b60cf528e')

build() {
    install -Dm 755 $startdir/sleep $pkgdir/etc/rc.d/sleep
}
