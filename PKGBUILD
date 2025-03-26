pkgname=otf-nimbus-mono
pkgdesc="Nimbus Mono typeface - A serif, typewriter typeface"
pkgver=1.0
pkgrel=1
arch=('any')
source=("https://www.fontsquirrel.com/fonts/download/nimbus-mono")
#source=("https://web.archive.org/web/20240306115725/https://www.fontsquirrel.com/fonts/download/nimbus-mono"
sha256sums=("5ff0173b126ea714ab636e4417427cc13cba7cf84ea62568d59f461a9fbe7e56")

package() {
	cd $srcdir
	for f in *.otf; do
  		install -Dm644 -t "$pkgdir/usr/share/fonts/OTF/nimbus-mono" "$f"
	done
  		install -Dm644 -t "$pkgdir/usr/share/licenses/$pkgname/license.txt" GNU\ General\ Public\ License.txt
}
