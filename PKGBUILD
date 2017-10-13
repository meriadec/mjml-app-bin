# Maintainer: Meriadec Pillet <meriadec.pillet@gmail.com>
pkgname=mjml-app
pkgver=2.7.0
pkgrel=1
pkgdesc='The desktop app for MJML'
arch=('any')
url="https://github.com/mjmlio/${pkgname}"
license=('MIT')
depends=('yarn')
source=(
  "https://github.com/mjmlio/${pkgname}/archive/${pkgver}.tar.gz"
  "mjml-app.desktop"
)
md5sums=('7144c577dbac7bed68cc8383c344e8cc')

package() {
  cd "${srcdir}/${pkgname}-${pkgver}/"
  yarn
  yarn package
}
