#Automatically generated by pip2arch on 2015-09-02

pkgname=python-css-html-prettify
pkgver=1.0.0
pkgrel=1
pkgdesc="StandAlone Async single-file cross-platform Unicode-ready Python3 Prettifier Beautifier for the Web."
url="https://github.com/juancarlospaco/css-html-prettify"
depends=('python' 'pip')
makedepends=('python3' )
license=('CUSTOM')
arch=('any')
source=('https://pypi.python.org/packages/source/c/css-html-prettify/css-html-prettify-1.0.0.zip')
md5sums=('7035dc4f84e0528d13cc46781afc5dc3')

build() {
    cd $srcdir/css-html-prettify-1.0.0
    python setup.py build
}

package() {
    cd $srcdir/css-html-prettify-1.0.0
    python setup.py install --root="$pkgdir" --optimize=1 
}