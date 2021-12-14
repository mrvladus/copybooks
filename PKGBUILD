pkgname="copybooks"
pkgver="1.0.0"
pkgrel="3"
pkgdesc="Copy audiobooks to USB drive in right order"
arch=("x86_64")
depends=("zenity" "cpio")
license=("custom")
source=("copybooks.sh")
sha512sums=("SKIP")
package() {
  mkdir -p "${pkgdir}/usr/bin"
  cp "${srcdir}/copybooks.sh" "${pkgdir}/usr/bin/copybooks"
  chmod +x "${pkgdir}/usr/bin/copybooks"
}