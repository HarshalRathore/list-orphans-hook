# Maintainer: Harshal Rathore <harshalrathore2014@gmail.com>
pkgname=list-orphans-hook
pkgver=1.0
pkgrel=1
pkgdesc="A pacman hook that lists orphaned packages in prettier format."
arch=('any')
url="https://aur.archlinux.org/packages/list-orphans-hook"
license=('MIT')
depends=('bash' 'pacman')
source=(
    "list-orphans.sh"
    "list-orphans.hook"
)
sha256sums=(
    'SKIP'
    'SKIP'
)

package() {
    install -Dm755 "${srcdir}/list-orphans.sh" "${pkgdir}/usr/bin/list-orphans"
    install -Dm644 "${srcdir}/list-orphans.hook" "${pkgdir}/usr/share/libalpm/hooks/list-orphans.hook"
}
