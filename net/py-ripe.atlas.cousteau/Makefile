PORTNAME=	ripe.atlas.cousteau
DISTVERSIONPREFIX=	v
DISTVERSION=	2.0.0
CATEGORIES=	net python
PKGNAMEPREFIX=${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	mstucchi@ripe.net
COMMENT=	Python wrapper around the RIPE Atlas API
WWW=		https://github.com/RIPE-NCC/ripe-atlas-cousteau

LICENSE=	GPLv3
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}dateutil>0:devel/py-dateutil@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}socketio-client>=0.6.5:net/py-socketio-client@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}requests>=2.7.0:www/py-requests@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}websocket-client>0:www/py-websocket-client@${PY_FLAVOR}

NO_ARCH=	yes
USES=		python
USE_GITHUB=	yes
GH_ACCOUNT=	RIPE-NCC
GH_PROJECT=	ripe-atlas-cousteau

USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
