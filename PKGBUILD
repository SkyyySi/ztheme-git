# Maintainer: SkyyySi

pkgname=ztheme-git
_pkgname=ztheme
pkgver=2.0
pkgrel=1
pkgdesc='Instantly change your zsh theme.'
arch=('any')
url='https://github.com/skyyysi/ztheme'
license=('Unlicense')
depends=('zsh')
source=("ztheme::git+https://github.com/SkyyySi/ztheme.git#branch=master")
md5sums=('SKIP')

package() {
	cd "$_pkgname"
	sudo make DESTDIR="$pkgdir/" install
}
