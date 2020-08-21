# Maintainer: SkyyySi

pkgname=ztheme-git
_pkgname=ztheme
pkgrel=1
pkgdesc='Instantly change your zsh theme.'
arch=('any')
url='https://github.com/skyyysi/ztheme'
license=('Unlicense')
depends=('zsh')
source=("ztheme::git+https://github.com/SkyyySi/ztheme.git#branch=master")
md5sums=('SKIP')

pkgver() {
  cd "$srcdir/$_pkgname"
  git describe --long --tags | sed 's/^v//;s/\([^-]*-g\)/r\1/;s/-/./g'
}

package() {
	cd "$_pkgname"
	sudo make DESTDIR="$pkgdir/" install
}
