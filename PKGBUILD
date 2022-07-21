# Maintainer: zicstardust <zicstardust@outlook.com>
pkgname=minebkgdrive
pkgver=0.1
pkgrel=1
pkgdesc="Backup Minecraft Maps to Google Drive"
arch=(any)
url="https://github.com/zicstardust/Minecraft-Backup-Gdrive"
license=('none')
depends=('gdrive' 'tar' 'bash')
source=("minebkgdrive::https://github.com/zicstardust/Minecraft-Backup-Gdrive/releases/download/${pkgver}/minebkgdrive")
sha256sums=('940e1dfd4c01f6545ab1d873f6d9c6ab95ae62348d7dd68cfba7d5735ee03ea6')
options=(!strip)

package() {
	install -Dm755 "${srcdir}/minebkgdrive" "${pkgdir}/usr/bin/minebkgdrive"
}
