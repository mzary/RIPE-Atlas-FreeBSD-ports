PORTNAME=	ripe.atlas.sagan
DISTVERSIONPREFIX=	v
DISTVERSION=	1.3.1
CATEGORIES=	net python
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	mstucchi@ripe.net
COMMENT=	Parsing library for RIPE Atlas measurement results
WWW=		https://github.com/RIPE-NCC/ripe.atlas.sagan

LICENSE=	GPLv3
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}dateutil>0:devel/py-dateutil@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}pytz>=0:devel/py-pytz@${PY_FLAVOR}

USES=		python
USE_GITHUB=	yes
GH_ACCOUNT=	RIPE-NCC
GH_PROJECT= ripe-atlas-sagan

USE_PYTHON=	autoplist concurrent cryptography distutils
NO_ARCH=	yes

.include <bsd.port.mk>
