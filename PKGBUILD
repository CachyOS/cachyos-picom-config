# Maintainer: Vladislav Nepogodin <nepogodin.vlad@gmail.com>

pkgname=cachyos-picom-config
pkgdesc='CachyOS picom config'
pkgver=1.0.1
pkgrel=1
arch=('any')
url="https://github.com/cachyos/$pkgname"
license=('GPL')
makedepends=('coreutils')
source=("$pkgname-$pkgver.tar.gz::$url/archive/$pkgver.tar.gz")
sha512sums=('b0e925fe6311a4d5e059028ed3ce5c3da67f35c2152df1633369d457558571ae15c14fe816fbc5e6866588cf726437cc9192f5f8699fd22e8ef9af45bed495bd')
depends=('picom')
install=$pkgname.install
provides=('cachyos-picom-config')
conflicts=('cachyos-picom-config')

package() {
    install -d $pkgdir/etc
    cp -rf $srcdir/$pkgname-$pkgver/etc $pkgdir
}
