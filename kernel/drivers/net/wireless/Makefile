#
# Makefile for the Linux Wireless network device drivers.
#

obj-$(CONFIG_IPW2100) += ipw2x00/
obj-$(CONFIG_IPW2200) += ipw2x00/

obj-$(CONFIG_HERMES)		+= orinoco/

obj-$(CONFIG_AIRO)		+= airo.o
obj-$(CONFIG_AIRO_CS)		+= airo_cs.o airo.o

obj-$(CONFIG_ATMEL)             += atmel.o
obj-$(CONFIG_PCI_ATMEL)         += atmel_pci.o 
obj-$(CONFIG_PCMCIA_ATMEL)      += atmel_cs.o

obj-$(CONFIG_AT76C50X_USB)      += at76c50x-usb.o

obj-$(CONFIG_PRISM54)		+= prism54/

obj-$(CONFIG_HOSTAP)		+= hostap/
obj-$(CONFIG_B43)		+= b43/
obj-$(CONFIG_B43LEGACY)		+= b43legacy/
obj-$(CONFIG_ZD1211RW)		+= zd1211rw/
obj-$(CONFIG_RTL8180)		+= rtl818x/
obj-$(CONFIG_RTL8187)		+= rtl818x/
obj-$(CONFIG_RTLWIFI)		+= rtlwifi/

# 16-bit wireless PCMCIA client drivers
obj-$(CONFIG_PCMCIA_RAYCS)	+= ray_cs.o
obj-$(CONFIG_PCMCIA_WL3501)	+= wl3501_cs.o

obj-$(CONFIG_USB_NET_RNDIS_WLAN)	+= rndis_wlan.o

obj-$(CONFIG_USB_ZD1201)	+= zd1201.o
obj-$(CONFIG_LIBERTAS)		+= libertas/

obj-$(CONFIG_LIBERTAS_THINFIRM)	+= libertas_tf/

obj-$(CONFIG_ADM8211)	+= adm8211.o

obj-$(CONFIG_MWL8K)	+= mwl8k.o

obj-$(CONFIG_IWLWIFI)	+= iwlwifi/
obj-$(CONFIG_IWLEGACY)	+= iwlegacy/
obj-$(CONFIG_RT2X00)	+= rt2x00/

obj-$(CONFIG_P54_COMMON)	+= p54/

obj-$(CONFIG_ATH_COMMON)	+= ath/

obj-$(CONFIG_MAC80211_HWSIM)	+= mac80211_hwsim.o

obj-$(CONFIG_WL1251)	+= wl1251/
obj-$(CONFIG_WL12XX)	+= wl12xx/
obj-$(CONFIG_WL12XX_PLATFORM_DATA)	+= wl12xx/

obj-$(CONFIG_IWM)	+= iwmc3200wifi/

obj-$(CONFIG_MWIFIEX)	+= mwifiex/

#obj-$(CONFIG_BCMDHD)	+= bcmdhd/

obj-$(CONFIG_BRCMFMAC)	+= brcm80211/
obj-$(CONFIG_BRCMSMAC)	+= brcm80211/
#obj-m	+= rtl8188C_8192C/
#obj-m	+= rtl8188EUS_rtl8189ES_linux_v4.1.7_9024.20130916/
#obj-m	+= rtl8723A_WiFi_linux_v4.1.7_7700.20130531_BTCOEX20130528_ver3.3_beta/
#obj-m	+= rtl8723BS_WiFi_linux_v4.2.5_9732.20131128_BTCOEX20131113-473F_beta_for_porting/
#obj-m	+= bcmdhd.1.28.23.x.cn_ap6330/
#obj-m	+= rtl8189ES_linux_v4.1.8/
#obj-$(CONFIG_BCMDHD)	+= bcmdhd.1.28.23.x.cn/
#obj-m	+= nmc1000/
#############################################
# NMI NMC1XXX
#############################################
#obj-$(CONFIG_NMC1XXX_WIFI_MODULE) += nmi/
