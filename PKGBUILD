# This builds the package for hxc usb emulator tools
# 
# Maintainer: Michael Hauspie <mickeymtp@gmail.com>
pkgname=hxcfloppy
pkgrel=1
epoch=
pkgdesc="Software that drives the HxC Floppy USB emulator"
arch=()
url="http://hxc2001.com"
license=('GPL')
depends=('fltk>=1.3')
makedepends=('base-devel', 'awk')
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("svn://svn.code.sf.net/p/hxcfloppyemu/code/hxcfloppyemu-code")
md5sums=() #generate with 'makepkg -g'

prepare() {
	cd "$srcdir/"
}

build() {
	cd "$srcdir/"
}

check() {
	cd "$srcdir/"
}

package() {
	cd "$srcdir/"
}

pkgver()
{
    grep '#define STR_FILE_VERSION2' "$srcdir/hxcfloppyemu-code/HxCFloppyEmulator/HxCFloppyEmulator_software/trunk/sources/version.h" | awk '{print $3;}' | tr -d \"
}
