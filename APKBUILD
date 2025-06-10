# Reference: <https://postmarketos.org/devicepkg>
pkgname=device-samsung-greatlte
pkgdesc="Samsung Galaxy Note 8 Exynos"
pkgver=1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="
	linux-samsung-greatlte
	mkbootimg
	postmarketos-base
"
makedepends="devicepkg-dev"
source="
	deviceinfo
	modules-initfs
"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="
66197abf977206399668e4253c912f8d008327bc618e2809e6772f52dfb932c093850c17f902697d68df07539e241dfef531b776608076133c1013611247aa82  deviceinfo
e70bae17df23dcaaaea0e2d3616556f04baa23f8ee1357785c0f539bf97282d8ddff53953e155b72689bb73beb38c2da3d08de2a61e866684edfa10a6593885d  modules-initfs
"
