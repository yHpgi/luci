#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI Diagnostics Tools (Device Info)
LUCI_DEPENDS:=+luci-app-diag-core +smap +netdiscover +mac-to-devinfo +httping +smap-to-devinfo +netdiscover-to-devinfo @BROKEN

define Package/luci-app-diag-devinfo/conffiles
/etc/config/luci_devinfo
endef

include ../../luci.mk

# call BuildPackage - BoluWrt buildroot signature
