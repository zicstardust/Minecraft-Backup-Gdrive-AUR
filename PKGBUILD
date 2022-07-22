# Maintainer: zicstardust <zicstardust@outlook.com>
pkgname=minebkgdrive
pkgver=0.2
pkgrel=1
pkgdesc="Backup Minecraft Maps to Google Drive"
arch=(any)
url="https://github.com/zicstardust/Minecraft-Backup-Gdrive"
license=('none')
depends=('tar' 'bash' 'awk')
source=("minebkgdrive::https://github.com/zicstardust/Minecraft-Backup-Gdrive/releases/download/${pkgver}/minebkgdrive")
sha256sums=('b0f3db71ecf353bc65306a1b592a8b42fb1f17ffc78e338af229d160215ff24a')
options=(!strip)

package() {
	install -Dm755 "${srcdir}/minebkgdrive" "${pkgdir}/usr/bin/minebkgdrive"
}
