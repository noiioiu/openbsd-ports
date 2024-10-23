COMMENT =	kakoune language server protocol client
CATEGORIES =	devel
V =	18.0.2

GH_ACCOUNT =	kakoune-lsp
GH_PROJECT =	kakoune-lsp
GH_TAGNAME =	v${V}

DISTNAME =	${GH_PROJECT}-${V}

HOMEPAGE =	https://github.com/${GH_ACCOUNT}/${GH_PROJECT}

# Unlicense OR MIT
PERMIT_PACKAGE =	Yes

WANTLIB += ${MODCARGO_WANTLIB} m

MODULES =	devel/cargo

SEPARATE_BUILD =	Yes

CONFIGURE_STYLE =	cargo

.include "crates.inc"
.include <bsd.port.mk>
