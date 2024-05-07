COMMENT=	flash ROM programmer for BIOS etc

V=		1.0.1
DISTNAME=	flashprog-v${V}
PKGNAME=	flashprog-${V}
EXTRACT_SUFX=	.tar.bz2

CATEGORIES=	sysutils

HOMEPAGE=	https://www.flashprog.org/

# GPLv2
PERMIT_PACKAGE=	Yes

WANTLIB=	c ftdi1 usb-1.0 z

SITES=		https://flashprog.org/releases/

BUILD_DEPENDS=	sysutils/pciutils \
		devel/gmake
LIB_DEPENDS=	devel/libftdi1 \
		devel/libusb1
MAKE_FLAGS+=	WARNERROR=no
FAKE_FLAGS=	PREFIX="${TRUEPREFIX}" MANDIR="${TRUEPREFIX}/man"

USE_GMAKE=	Yes
NO_TEST=	Yes

MAKE_FLAGS+=	CONFIG_JLINK_SPI=no

.include <bsd.port.mk>
