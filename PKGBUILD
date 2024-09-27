# Maintainer: Aryan Singh <insaiyan@cocaine.ninja>
pkgname=showratings
pkgver=1.0.1
pkgrel=1
pkgdesc="A script to fetch and display Codeforces, CodeChef, and LeetCode ratings"
license=('MIT')
arch=('any')
depends=('bash' 'curl' 'jq')
source=("showratings")
sha256sums=('SKIP') 

package() {
    install -Dm755 "$srcdir/showratings" "$pkgdir/usr/bin/showratings"
    install -d "$pkgdir/etc/showratings"
}
