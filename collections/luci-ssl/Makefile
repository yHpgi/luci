#
# Copyright (C) 2008-2016 The LuCI Team
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TYPE:=col
LUCI_BASENAME:=ssl

LUCI_TITLE:=LuCI with HTTPS support (mbedTLS as SSL backend)
LUCI_DEPENDS:=+luci +libustream-mbedtls +px5g

include ../../luci.mk

# call BuildPackage - BoluWrt buildroot signature
