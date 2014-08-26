pkgname=ttf-inconsolata-dz-powerline
pkgver=1.0
pkgrel=2
depends=('fontconfig' 'xorg-font-utils')
pkgdesc="Inconsolata-dz-Powerline"
arch=('any')
url=('https://github.com/Ema0/ttf-inconsolata-dz-powerline')
license=('GPL')
source=(https://github.com/Ema0/arch/raw/master/Inconsolata-dz-Powerline.otf)
md5sums=('4319abb6691c480d23cec11252c86a56')
install=$pkgname.install

package()
{
    mkdir -p $pkgdir/usr/share/fonts/TTF
    cp $srcdir/Inconsolata-dz-Powerline.otf $pkgdir/usr/share/fonts/TTF
}
