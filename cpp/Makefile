# -*-Makefile-*-
#----------------------------------------------------------------------------
#       Make Workspace
#
# $Id$
#
# This file was generated by MPC.  Any changes made directly to
# this file will be lost the next time it is generated.
#
# MPC Command:
# /home/dds/OvernightTests/overnight/ospli/tags/OSPL_V6_8_3-RC5/ubuntu1604-64a/x86_64.linux-release-inner/build/bin/mwc.pl -features ospl_os_host_linux=1 -features ospl_os_linux=1 -features ospl_64_bit=1 -value_template lib_modifier= -include /bin/MakeProjectCreator/config -include /bin/MakeProjectCreator/config/TAO -features x86_64_linux=1 -features ospl_arch_x86_64=1 -type make -features no_c99=0 -features isocpp2_cxx11=1 HDE/x86_64.linux/examples/examples_simple.mwc
#
#----------------------------------------------------------------------------


all: sacpp_datariverchannel_types sacpp_datariverchannel_pub sacpp_datariverchannel_sub

clean depend generated realclean check-syntax $(CUSTOM_TARGETS):
	@cd standalone && $(MAKE) -f Makefile.sacpp_datariverchannel_types $(@)
	@cd standalone && $(MAKE) -f Makefile.sacpp_datariverchannel_pub $(@)
	@cd standalone && $(MAKE) -f Makefile.sacpp_datariverchannel_sub $(@)

.PHONY: sacpp_datariverchannel_types
sacpp_datariverchannel_types:
	@cd standalone && $(MAKE) -f Makefile.sacpp_datariverchannel_types all

.PHONY: sacpp_datariverchannel_pub
sacpp_datariverchannel_pub: sacpp_datariverchannel_types
	@cd standalone && $(MAKE) -f Makefile.sacpp_datariverchannel_pub all

.PHONY: sacpp_datariverchannel_sub
sacpp_datariverchannel_sub: sacpp_datariverchannel_types
	@cd standalone && $(MAKE) -f Makefile.sacpp_datariverchannel_sub all

project_name_list:
	@echo sacpp_datariverchannel_pub
	@echo sacpp_datariverchannel_sub
	@echo sacpp_datariverchannel_types
