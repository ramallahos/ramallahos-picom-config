# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-picom-config
pkgver=1
pkgrel=1
pkgdesc="Picom config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('picom-jonaburg-git')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/picom/"
    install -Dm 644 ".bashrc" "${pkgdir}/etc/skel/.config/picom/picom.conf"
}
