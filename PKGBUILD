# Maintainer: Edoardo Maria Elidoro <edoardo.elidoro@gmail.com>
# Contributor: grimi <grimi at poczta dot fm>

pkgname=gtk-theme-clearbird
pkgver=1.3
pkgrel=1
pkgdesc="A gtk2, gtk3, metacity, xfwm4, openbox and unity theme..."
arch=('any')
url="http://gnome-look.org/content/show.php/Clearbird?content=154148"
license=('GPL')
depends=('gtk-engines' 'gtk-engine-murrine' 'gtk-engine-unico')
source=("${pkgname}-${pkgver}.tar.gz::http://gnome-look.org/CONTENT/content-files/154148-Clearbird36.tar.gz")
md5sums=('d6dd8d309f6e81b049d6f3d17adc8159')


package() {

  # install theme
  find Clearbird/ -type f \
      -exec install -Dm644 "{}" "$pkgdir/usr/share/themes/{}" \;
}
