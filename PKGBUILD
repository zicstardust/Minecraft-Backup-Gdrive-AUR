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
sha256sums=('27ad4f94c12c810f4121cc9b8991bd63ec2bead14cbc3c0089762383c5ba890c')
options=(!strip)

package() {
	install -Dm755 "${srcdir}/minebkgdrive" "${pkgdir}/usr/bin/minebkgdrive"
}
