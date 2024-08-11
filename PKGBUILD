# Maintainer: eldiaboloz <iliyan87.ivanov@gmail.com>
pkgname=totp-cli-rofi
pkgver=1.0.0
pkgrel=1
pkgdesc="Simple CLI TOTP tool with rofi integration"
arch=('any')
depends=('fzf' 'rofi' 'jq' 'gnupg' 'oath-toolkit' 'xdotool' 'bash')
license=('MIT')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/eldiaboloz/${pkgname}/archive/v${pkgver}.tar.gz")
sha256sums=('0178ece448f3360b62d858b5c60757cd412e6fa79789567f0d90a250383c7be7')

package() {
  cd "$pkgname-$pkgver"
  install -m 755 -D $pkgname "$pkgdir/usr/bin/$pkgname"
  install -m 444 -D LICENCE "$pkgdir/usr/share/doc/LICENCE"
}
