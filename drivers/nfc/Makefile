#
# Makefile for nfc devices
#

obj-$(CONFIG_NFC_PN544)		+= pn544/
obj-$(CONFIG_NFC_MICROREAD)	+= microread/
obj-$(CONFIG_NFC_PN533)		+= pn533.o
obj-$(CONFIG_NFC_WILINK)	+= nfcwilink.o
obj-$(CONFIG_NFC_MEI_PHY)	+= mei_phy.o
obj-$(CONFIG_NFC_QNCI)		+= nfc-nci.o
#/* < DTS2014120800808 songxiaoming 20141208 begin */
obj-y      += pn547.o
obj-y      += nfc_adaptive.o
#/* DTS2014120800808 songxiaoming 20141208 end > */

ccflags-$(CONFIG_NFC_DEBUG) := -DDEBUG
