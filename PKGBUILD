# Maintainer: SkyyySi

pkgname=ztheme
pkgver=1.0
pkgrel=1
pkgdesc='Instantly change your zsh theme.'
arch=('any')
#url=''
license=('Unlicense')
depends=('zsh')
source=("$pkgname-$pkgver.tar.gz")

package() {
	sudo make DESTDIR="$pkgdir/" install
}
md5sums=('7870bb95708edf0207cd7344b0adae8d')
