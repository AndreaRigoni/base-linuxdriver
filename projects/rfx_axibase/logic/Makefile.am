include $(top_srcdir)/Common.am
include $(top_srcdir)/fpga/FpgaCommon.am

SOC_BOARD       ?= red_pitaya
VIVADO_VERSION  ?= 2015.4
VIVADO_SOC_PART ?= xc7z010clg400-1


SOURCES = red_pitaya.xdc

BD_SOURCES =
#red_pitaya_2015.4.tcl

## NOTE: the ip name must be formatted as: [ip_path]/[ipname]_[major.minor]
IP_SOURCES = 

all: $(FPGA_BIT) $(DTB) ##@all Write bitstream and devicetree

clean:
	-rm -rf out .Xil .srcs sdk webtalk_*

