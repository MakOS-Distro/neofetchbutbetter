pkgname=neofetch
pkgver=1
pkgrel=1
pkgdesc=""
arch=('any')
url="https://repo.makan.cat"
license=('MIT')
depends=('bash')
source=('neofetch')
noextract=('neofetch')
sha256sums=('39f0aeba325257cd01e4b0ac25ec17f6a5e373e204e3cb09813353d276cac01d')

package() {
  install -Dm755 "$srcdir/neofetch" "$pkgdir/usr/bin/neofetch"
}
