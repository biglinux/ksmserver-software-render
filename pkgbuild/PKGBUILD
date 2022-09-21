# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=ksmserver-software-render
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/ksmserver-software-render"
pkgdesc="Force ksmserver to use software render"
depends=('sddm')
source=("git+https://github.com/biglinux/ksmserver-software-render.git")
md5sums=(SKIP)

package() {
    cp -r "${srcdir}/ksmserver-software-render/ksmserver-software-render/usr/" "${pkgdir}/"
} 
