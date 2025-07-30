# Maintainer: Aryan Singh <insaiyan@cocaine.ninja>
pkgname=showratings
pkgver=1.1.0
pkgrel=1
pkgdesc="A script to fetch and display ratings from Codeforces, CodeChef, LeetCode, and GitHub stats"
license=('MIT')
arch=('any')
depends=('bash' 'curl' 'jq')
source=("showratings")
sha256sums=('SKIP') 

package() {
    install -Dm755 "$srcdir/showratings" "$pkgdir/usr/bin/showratings"
    install -d "$pkgdir/etc/showratings"
}
