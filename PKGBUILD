pkgname=kdeplasma-applets-window-title
_pkgname=applet-window-title
pkgver=0.5.2
pkgrel=1
pkgdesc="Plasma 5 applet that shows the application title and icon for active window "
arch=(x86_64)
url="https://github.com/psifidotos/applet-window-title"
license=('GPL2')
depends=(kdeclarative)
source=("https://github.com/psifidotos/${_pkgname}/archive/v${pkgver}.tar.gz")
md5sums=('2c8d5143dc6f31989d2e380dc7f5483f')

package() {
  install -dm755 "${pkgdir}/usr/share/plasma/plasmoids/"
  cp --preserve=mode -r "${_pkgname}-${pkgver}" "${pkgdir}/usr/share/plasma/plasmoids/org.kde.windowtitle"
}
