# Maintainer: Nathan Kolpa <nathan@kolpa.me>
pkgname=xmonad-recompile-hook-git
pkgver=1.0
pkgrel=1
pkgdesc="This hook recompiles xmonad when necessary to prevent errors after restarting"
arch=('any')
url="https://github.com/NathanKolpa/xmonad-recompile-hook.git"
license=('GPL')
depends=(xmonad)
makedepends=(git make)
options=()
source=("git+$url")
md5sums=('SKIP')

package() {
	cd "xmonad-recompile-hook"
	make DESTDIR="$pkgdir/" install
}
