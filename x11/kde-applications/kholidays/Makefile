# $OpenBSD$

COMMENT =	KDE library for regional holiday information
DISTNAME =	kholidays-${VERSION}
CATEGORIES =	devel

SHARED_LIBS +=  KF5Holidays               0.0 # 5.5

WANTLIB += ${COMPILER_LIBCXX} Qt5Core Qt5Network Qt5Qml m

RUN_DEPENDS =	x11/qt5/qtdeclarative

KDE5 =		Yes

.include <bsd.port.mk>
