# Maintainer: Trizen <echo dHJpemVueEBnbWFpbC5jb20K | base64 -d>

pkgname=chm-to-pdf-fr
pkgver=0.01
pkgrel=1

arch=('any')
license=('GPLv3')

pkgdesc="A simple Perl script that converts CHM files into PDF files (based on wkhtmltopdf and file-roller)"
url="http://code.google.com/p/trizen/downloads/detail?name=$pkgname-$pkgver.tar.gz"

depends=('perl>=5.10.0' 'file-roller' 'perl-uri' 'wkhtmltopdf-static')

source="http://trizen.googlecode.com/files/$pkgname-$pkgver.tar.gz"
md5sums=('4da306eca811132431eee3be7df6bcb7')

package() {
  install -m 755 -D $pkgname "$pkgdir/usr/bin/$pkgname"
}
