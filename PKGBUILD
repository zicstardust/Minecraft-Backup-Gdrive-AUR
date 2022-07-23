# Maintainer: zicstardust <zicstardust@outlook.com>
pkgname=minebkgdrive
pkgver=1.0
pkgrel=1
pkgdesc="Backup Minecraft Maps to Google Drive"
arch=(any)
url="https://github.com/zicstardust/Minecraft-Backup-Gdrive"
license=('none')
depends=('tar' 'bash' 'awk' 'grep' 'xargs')
source=("minebkgdrive::https://github.com/zicstardust/Minecraft-Backup-Gdrive/releases/download/${pkgver}/minebkgdrive")
sha256sums=('e60a54f188c699b45f62cb97d18d566b5dbf39e56b220341ed815f3808e2b8fe')
options=(!strip)

package() {
	install -Dm755 "${srcdir}/minebkgdrive" "${pkgdir}/usr/bin/minebkgdrive"
}
