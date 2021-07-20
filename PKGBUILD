# Maintainer: Baran Karaaslan <barankaraaslan_06@hotmail.com>
pkgname=baran-sudo
pkgver=0.1.0
pkgrel=1
pkgdesc="my sudo configuration"
arch=(any)
url=""
license=('GPL')
depends=('sudo')
install=
changelog=
source=("${pkgname}-${pkgver}::git+https://github.com/barankaraaslan/baran-sudo.git")

package() {
	cd "$pkgname-$pkgver"
	make DESTDIR="$pkgdir/" install
}
