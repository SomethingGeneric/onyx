# Maintainer: Matt C <mdc028[at]bucknell[dot]edu>

pkgname=old_onyx_themes
pkgver=2
pkgrel=1
pkgdesc="Crystal Linux (old) default desktop setup"
arch=('any')
url="https://github.com/SomethingGeneric/onyx"
license=('GPL')
source=('inst::git+https://github.com/SomethingGeneric/onyx')
depends=()
conflicts=()
md5sums=('SKIP')
options=(!strip)

package() {

    mkdir -p "${pkgdir}"
    cp -rv inst/usr ${pkgdir}/.
    
}
