# Maintainer: shad0w73 <shad0w73@maills.de>
pkgname=xchat-xdccq
pkgver=0.6
pkgrel=3
pkgdesc="Keeps a local queue of xdcc requests, and dishes them out as files finish. Ideal for grabbing many consecutive packs from a single bot."
arch=(any)
url="http://dev.jmoiron.net/xchat/"
license=('GPL2')
depends=('xchat' 'python2')
source=("xdccq.py")
md5sums=('df7d3cedc987647b2698512b76007c63')

package() {
  install -d "$pkgdir/usr/lib/xchat/plugins/"
  install -Dm 755 "$srcdir/xdccq.py" "$pkgdir/usr/lib/xchat/plugins/"
}
