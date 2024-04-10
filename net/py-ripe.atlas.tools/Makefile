PORTNAME=	ripe.atlas.tools
DISTVERSIONPREFIX=	v
DISTVERSION=	3.1.0
CATEGORIES=	net python
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	mstucchi@ripe.net
COMMENT=	Official command-line client for RIPE Atlas
WWW=		https://github.com/RIPE-NCC/ripe-atlas-tools

LICENSE=	GPLv3
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}dateutil>0:devel/py-dateutil@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}requests>=2.7.0:www/py-requests@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}ripe.atlas.cousteau>=2.0.0:net/py-ripe.atlas.cousteau@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}ripe.atlas.sagan>=1.3.1:net/py-ripe.atlas.sagan@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}tzlocal>0:devel/py-tzlocal@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}yaml>0:devel/py-yaml@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}typing-extensions>=4.10.0:devel/py-typing-extensions@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}openssl>=0.13:security/py-openssl@${PY_FLAVOR}

USES=		python
USE_GITHUB=	yes
GH_ACCOUNT=	RIPE-NCC
GH_PROJECT= ripe-atlas-tools

USE_PYTHON=	autoplist distutils
NO_ARCH=	yes

CONFLICTS_INSTALL=	c-ares # bin/adig

.include <bsd.port.mk>
