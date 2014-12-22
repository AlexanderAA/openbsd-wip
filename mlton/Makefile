# $OpenBSD: Makefile,v 1.7 2013/03/11 10:50:31 espie Exp $

COMMENT=	MLton compiler

#DISTNAME=	mlton-20141220-1.amd64-openbsd
DISTNAME=	mlton-20130715.src
REVISION=	
CATEGORIES=	devel

HOMEPAGE=	http://ray/public/

WRKDIST =	${WRKDIR}/mlton-20130715

# BSD
PERMIT_PACKAGE_CDROM=	Yes
PERMIT_PACKAGE_FTP=     Yes
PERMIT_DISTFILES_FTP=   Yes

MASTER_SITES=		http://ray/public/

WANTLIB=		gmp

USE_GMAKE=		Yes
NO_CHECKSUM=            No

BUILD_DEPENDS=		${RUN_DEPENDS}
RUN_DEPENDS=		



.include <bsd.port.mk>
