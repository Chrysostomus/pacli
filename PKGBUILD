# Maintainer: Chrysostomus @forum.manjaro.org

pkgname=pacli
pkgver=0.1
pkgrel=1
pkgdesc="An interactive pacman interface using fzf"
arch=(any)
url="https://github.com/Manjaro-Pek/$pkgname"
license=GPL2
depends=('fzf'
	'pacman'
	'yaourt'
	'pacman-mirrors'
	'sudo'
	'gzip'
	'downgrade'
	'bash')
makedepends=('git')
optdepends=('update-notifier: Automatically get notified when updates are available')
source=("git://github.com/Manjaro-Pek/$pkgname")
md5sums=('SKIP')

package () {
    install -Dm755 "$srcdir/$pkgname/pacli" "$pkgdir/usr/bin/pacli"
    install -Dm544 "$srcdir/$pkgname/pacli.help" "$pkgdir/usr/share/doc/pacli/help"
}
