COMMENT =	sound distributed version control system
CATEGORIES =	devel
V =		1.0.0-beta.9

PKGNAME =	pijul-${V:S/-beta./beta/}
DISTNAME =	pijul-${V}
SITES =		${SITES.cargo}
DISTFILES =	pijul-${V}.${EXTRACT_SUFX}{pijul/${V}/download}

HOMEPAGE =	https://pijul.org

# GPLv2
PERMIT_PACKAGE =	Yes

WANTLIB += ${MODCARGO_WANTLIB} m

MODULES =	devel/cargo

SEPARATE_BUILD =	Yes

CONFIGURE_STYLE =	cargo

.include "crates.inc"
.include <bsd.port.mk>
