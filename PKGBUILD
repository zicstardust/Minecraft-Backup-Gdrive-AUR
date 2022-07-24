# Maintainer: zicstardust <zicstardust@outlook.com>
pkgname=minebkgdrive
pkgver=1.0.1
pkgrel=1
pkgdesc="Backup Minecraft Maps to Google Drive"
arch=(any)
url="https://github.com/zicstardust/Minecraft-Backup-Gdrive"
license=('none')
depends=('tar' 'bash' 'awk')
source=("minebkgdrive::https://github.com/zicstardust/Minecraft-Backup-Gdrive/releases/download/${pkgver}/minebkgdrive")
sha256sums=('7dbaba05f8a25e438e07ccb13e64f7ed9b648cbc907039e8e59cd79ab650e284')
options=(!strip)

package() {
	install -Dm755 "${srcdir}/minebkgdrive" "${pkgdir}/usr/bin/minebkgdrive"
}
