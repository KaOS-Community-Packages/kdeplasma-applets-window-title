pkgname=kdeplasma-applets-window-title
_pkgname=applet-window-title
pkgver=0.6.0
pkgrel=1
pkgdesc="Plasma 5 applet that shows the application title and icon for active window "
arch=(x86_64)
url="https://github.com/psifidotos/applet-window-title"
license=('GPL2')
depends=(kdeclarative)
source=("https://github.com/psifidotos/${_pkgname}/archive/${pkgver}.tar.gz")
md5sums=('609370dd8a58e8c0cb0df16fcc8cee65')

package() {
  install -dm755 "${pkgdir}/usr/share/plasma/plasmoids/"
  cp --preserve=mode -r "${_pkgname}-${pkgver}" "${pkgdir}/usr/share/plasma/plasmoids/org.kde.windowtitle"
}
