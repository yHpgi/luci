#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=Support for VPNC VPN
LUCI_DEPENDS:=+vpnc
LUCI_PKGARCH:=all

PKG_NAME:=luci-proto-vpnc
PKG_RELEASE=1
PKG_VERSION:=1.0.0
PKG_MAINTAINER:=Daniel Dickinson <openwrt@daniel.thecshore.com>
PKG_LICENSE:=Apache-2.0

LUA_TARGET:=source

include ../../luci.mk

# call BuildPackage - BoluWrt buildroot signature