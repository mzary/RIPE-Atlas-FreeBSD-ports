PORTNAME=		ripe-goat
DISTVERSIONPREFIX=	v
DISTVERSION=	0.7.2
CATEGORIES=		net
DIST_SUBDIR=	goat

MAINTAINER=	zarychtam@plan-b.pwste.edu.pl
COMMENT=	Go (RIPE) Atlas Tools - CLI & API Wrapper
WWW=		https://github.com/robert-kisteleki/goat

LICENSE=	BSD
LICENSE_FILE=	${WRKSRC}/LICENSE

USES=		go:modules
GO_MODULE=	github.com/robert-kisteleki/goat
GO_TARGET=	./cmd/goat

PLIST_FILES=	bin/goat

.include <bsd.port.mk>
