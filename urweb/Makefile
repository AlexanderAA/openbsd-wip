COMMENT=	programming language plus a standard library

DISTNAME=	urweb-20141206.src
REVISION=	
CATEGORIES=	devel

MAINTAINER=     Alexander Abushkevich <ml@extensibl.com>

HOMEPAGE=	http://ray/public/

WRKDIST =	${WRKDIR}/urweb-20141206

# BSD
PERMIT_PACKAGE_CDROM=	Yes

MASTER_SITES=		http://ray/public/

WANTLIB= crypto m pthread ssl

USE_GMAKE=		Yes
NO_CHECKSUM=            No

RUN_DEPENDS=		
BUILD_DEPENDS=		${RUN_DEPENDS}

CONFIGURE_STYLE=        simple


.include <bsd.port.mk>
