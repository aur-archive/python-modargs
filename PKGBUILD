# Maintainer: Hilton Medeiros <medeiros.hilton@gmail.com>

pkgname=python-modargs
pkgver=1.7
pkgrel=1
pkgdesc="A simple command line argument parsing library that infers arguments from functions."
arch=('any')
url="http://pypi.python.org/pypi/python-modargs"
license=('MIT')
depends=('python2')
source=("http://pypi.python.org/packages/source/p/$pkgname/$pkgname-$pkgver.tar.gz")
md5sums=('701bf62449c303238bb27ec59cdca8ab')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python2 setup.py install --prefix=/usr --root="$pkgdir" -O1
}
md5sums=('b4893fdd657e2f1bb8e750a747239a9a')
