include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-mmfd
PKG_VERSION:=1

include ../gluon.mk

define Package/gluon-mmfd
  TITLE:=mesh multicast forwarding daemon - gluon integration
  DEPENDS:=+mmfd +uc +gluon-core
endef

$(eval $(call BuildPackageGluon,gluon-mmfd))
