SPK_NAME = mercurial
SPK_VERS = 6.5
SPK_REV = 9
SPK_ICON = src/mercurial.png

PYTHON_PACKAGE = python311

WHEELS = src/requirements-crossenv.txt src/requirements-pure.txt
SPK_DEPENDS = "$(PYTHON_PACKAGE)>=3.11.4-7"

MAINTAINER = SynoCommunity
DESCRIPTION = Mercurial is a free, distributed source control management tool
STARTABLE = no
DISPLAY_NAME = Mercurial
CHANGELOG = "1. Update mercurial to 6.5<br/>2. Update to Python 3.11"

HOMEPAGE = https://www.mercurial-scm.org/
LICENSE  = MPL1.1

SERVICE_SETUP = src/service-setup.sh

SPK_USR_LOCAL_LINKS = bin:env/bin/hg

include ../../mk/spksrc.python.mk
