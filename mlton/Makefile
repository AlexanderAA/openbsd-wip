# $OpenBSD: Makefile,v 1.7 2013/03/11 10:50:31 espie Exp $

COMMENT=        MLton compiler
DISTNAME=       mlton-20130715
REVISION=       1
CATEGORIES=     devel

MAINTAINER=     Alexander Abushkevich <alex@abushkevi.ch>

HOMEPAGE=       http://mlton.org

GH_ACCOUNT=     AlexanderAA
GH_PROJECT=     mlton
# GH_TAGNAME=     on-20130715-release
# GH_COMMIT=      e2a8395e4a1c02ab22970215eabf91db59acedf8
GH_COMMIT=      afc68e3d881ca04a33db3efd072874acf677ded5

WRKDIST =       ${WRKDIR}/mlton-${GH_COMMIT}

# BSD
PERMIT_PACKAGE_CDROM=   Yes
PERMIT_PACKAGE_FTP=     Yes
PERMIT_DISTFILES_FTP=   Yes

USE_GMAKE=              Yes
NO_CHECKSUM=            No

BUILD_DEPENDS=          ${RUN_DEPENDS}
RUN_DEPENDS=


.include <bsd.port.mk>
