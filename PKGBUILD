pkgname=kdeplasma-applets-window-title
_pkgname=applet-window-title
pkgver=0.7.0
pkgrel=1
pkgdesc="Plasma 5 applet that shows the application title and icon for active window "
arch=(x86_64)
url="https://github.com/psifidotos/applet-window-title"
license=('GPL2')
depends=(kdeclarative)
source=("https://github.com/psifidotos/${_pkgname}/archive/${pkgver}.tar.gz")
md5sums=('04c240b862211aae851858fafc00b8b4')

package() {
  install -dm755 "${pkgdir}/usr/share/plasma/plasmoids/"
  cp --preserve=mode -r "${_pkgname}-${pkgver}" "${pkgdir}/usr/share/plasma/plasmoids/org.kde.windowtitle"
}
