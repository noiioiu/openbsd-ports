COMMENT =	language server for haskell

PKGNAME =	${MODCABAL_STEM}-${MODCABAL_VERSION}
CATEGORIES =	devel

# Apache 2.0
PERMIT_PACKAGE=		Yes

MAINTAINER =		noiioiu <noiioiu@cocaine.ninja>

WANTLIB =		c charset ffi gmp iconv m pthread util

LIB_DEPENDS =		converters/libiconv \
			devel/gmp \
			devel/libffi

MODULES =		devel/cabal
MODCABAL_EXECUTABLES =	haskell-language-server haskell-language-server-wrapper

.include "modcabal.inc"

.include <bsd.port.mk>
