# Maintainer: Emam Damon <grn.aryan666@gmail.com>

pkgname=arko-fetch
pkgver=1.0
pkgrel=2
pkgdesc="fetch for Arkolinux"
url="https://github.com/archcraft-os/archcraft-packages"
arch=('any')
license=('GPL3')
makedepends=()
depends=()
conflicts=()
provides=("${pkgname}")
options=(!strip !emptydirs)

source=('fetch')

#sha256sums=('f7e70e6f7ea0f6326f8c8705e98db82bb09e4615f1c5defe5cb365ad56646895'
            'e076edd4a4e571eb431b8efc5ba5da513c8c354c700e6aecdae7a5142382defc')

package() {
	install -Dm 755 fetch   		${pkgdir}/usr/local/bin/fetch
	install -Dm 755 sfetch   		${pkgdir}/usr/local/bin/sfetch
	install -Dm 755 sysinfo   		${pkgdir}/usr/local/bin/sysinfo
	install -Dm 755 sysinfo-retro   		${pkgdir}/usr/local/bin/sysinfo-retro
}
