pkgname=ttf-merriweather-sans
pkgver=1
pkgrel=1
pkgdesc='A sans-serif typeface that is pleasant to read on screens by Sorkin Type Co'
arch=('any')
url=
license=('custom:SIL Open Font License v1.1')
depends=('fontconfig' 'xorg-fonts-encodings' 'xorg-font-utils')
conflicts=()
source=(

package() {
  install -dm 755 "${pkgdir}/usr/share/fonts/TTF"
  install -Dm644 ${pkgname}-${pkgver}-OFL.txt "${pkgdir}/usr/share/licenses/$pkgname/LICENSE"
}
