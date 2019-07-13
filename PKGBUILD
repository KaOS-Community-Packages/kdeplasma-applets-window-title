pkgname=kdeplasma-applets-window-title
_pkgname=applet-window-title
pkgver=0.5.0
pkgrel=1
pkgdesc="Plasma 5 applet that shows the application title and icon for active window "
arch=(x86_64)
url="https://github.com/psifidotos/applet-window-title"
license=('GPL2')
depends=(kdeclarative)
source=("https://github.com/psifidotos/${_pkgname}/archive/v${pkgver}.tar.gz")
md5sums=('5d182ff3de699f9d0ad894a551bc804a')

package() {
  install -dm755 "${pkgdir}/usr/share/plasma/plasmoids/"
  cp --preserve=mode -r "${_pkgname}-${pkgver}" "${pkgdir}/usr/share/plasma/plasmoids/org.kde.windowtitle"
}
