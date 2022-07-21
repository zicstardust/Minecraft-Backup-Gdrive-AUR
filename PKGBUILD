# Maintainer: zicstardust <zicstardust@outlook.com>
pkgname=minecraftbackupgdrive
pkgver=0.1
pkgrel=1
pkgdesc="Backup Minecraft Maps to Google Drive"
arch=(any)
url="https://github.com/zicstardust/Minecraft-Backup-Gdrive"
license=('none')
depends=('gdrive' 'tar' 'bash')
source=("minecraftbackupgdrive::https://github.com/zicstardust/Minecraft-Backup-Gdrive/releases/download/0.1/minecraftbackupgdrive")
sha256sums=('4f5ad77e0a6b61f1331c37c94860c907efd8052d4993f3cef6417257844f5a6c')
options=(!strip)

package() {
	install -Dm755 "${srcdir}/minecraftbackupgdrive" "${pkgdir}/usr/bin/minecraftbackupgdrive"
}
