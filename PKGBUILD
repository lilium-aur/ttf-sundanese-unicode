# Maintainer: alcztn <alcztn@pm.me>

pkgname=ttf-sundanese-unicode
pkgver=2.0
pkgrel=1
pkgdesc='Sundanese Unicode Font'
arch=('any')
url='https://www.kairaga.com/download/sundanese-unicode-2-0-ttf'
license=('custom')
source=("SundaneseUnicode-${pkgver}.ttf")
sha256sums=('SKIP')

package() {
  install -dm 755 "${pkgdir}/usr/share/fonts/TTF"
  install -m 644 SundaneseUnicode-${pkgver}.ttf "${pkgdir}/usr/share/fonts/TTF/SundaneseUnicode.ttf"
}
