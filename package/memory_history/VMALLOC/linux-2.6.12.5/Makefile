################################################
#
# VMALLOC linux 2.6.12.5
#
################################################
PK_VMALLOC_2_6_12_5_NAME        := BiscuitOS_VMALLOC
PK_VMALLOC_2_6_12_5_VERSION     := $(CONFIG_PK_VMALLOC_2_6_12_5_VERSION)
PK_VMALLOC_2_6_12_5_SITE        := $(CONFIG_PK_VMALLOC_2_6_12_5_URL)
PK_VMALLOC_2_6_12_5_GITHUB      := $(CONFIG_PK_VMALLOC_2_6_12_5_GITHUB)
PK_VMALLOC_2_6_12_5_SUBNAME     :=
PK_VMALLOC_2_6_12_5_BUILDARCH   := $(CONFIG_PK_VMALLOC_2_6_12_5_BUILDARCH)
PK_VMALLOC_2_6_12_5_DIR         := $(srctree)/package/memory_history/VMALLOC/linux-2.6.12.5
PK_VMALLOC_2_6_12_5_PATCH       := $(PK_VMALLOC_2_6_12_5_DIR)/patch
PK_VMALLOC_2_6_12_5_BSBIT       := BiscuitOS_VMALLOC-$(PK_VMALLOC_2_6_12_5_VERSION).bsbit
PK_VMALLOC_2_6_12_5_OUT         :=
PK_VMALLOC_2_6_12_5_SCRIPTS     := $(srctree)/scripts/package/package-memory.sh
PK_VMALLOC_2_6_12_5_TAR         := $(CONFIG_PK_VMALLOC_2_6_12_5_TAR)
PK_VMALLOC_2_6_12_5_PACKAGE     :=
PK_VMALLOC_2_6_12_5_CONFIG      := $(CONFIG_PK_VMALLOC_2_6_12_5_CONFIG)
SUB_TARGET                  += $(PK_VMALLOC_2_6_12_5_DIR)/build

PK_VMALLOC_2_6_12_5_sh = $(CONFIG_SHELL) $(PK_VMALLOC_2_6_12_5_SCRIPTS) \
                 $1X \
                 $(PK_VMALLOC_2_6_12_5_NAME)X \
                 $(PK_VMALLOC_2_6_12_5_VERSION)X \
                 $(PK_VMALLOC_2_6_12_5_SITE)X \
                 $(PK_VMALLOC_2_6_12_5_GITHUB)X \
                 $(PK_VMALLOC_2_6_12_5_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_VMALLOC_2_6_12_5_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_VMALLOC_2_6_12_5_SUBNAME)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_CONFIG)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_LIBPATH)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_CPPFLAGS)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_DPKCONFIG)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_CFLAGS)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_LDFLAGS)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_CXXFLAGS)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_ASFLAGS)X \
                 $(PK_VMALLOC_2_6_12_5_BSBIT)X \
                 $(PK_VMALLOC_2_6_12_5_BUILDARCH)X \
		 $(PK_VMALLOC_2_6_12_5_CSRCFILE)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_SRCFILE)X \
                 $(CONFIG_PK_VMALLOC_2_6_12_5_CSRCFILE)

$(PK_VMALLOC_2_6_12_5_DIR)/build: FORCE
	$(Q)$(call PK_VMALLOC_2_6_12_5_sh,$(srctree))
