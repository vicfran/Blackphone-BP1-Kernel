# generic pinmux support
GCOV_PROFILE := y

ccflags-$(CONFIG_DEBUG_PINCTRL)	+= -DDEBUG

obj-$(CONFIG_PINCTRL)		+= core.o
obj-$(CONFIG_PINMUX)		+= pinmux.o
obj-$(CONFIG_PINCONF)		+= pinconf.o
ifeq ($(CONFIG_OF),y)
obj-$(CONFIG_PINCTRL)		+= devicetree.o
endif
obj-$(CONFIG_GENERIC_PINCONF)	+= pinconf-generic.o
obj-$(CONFIG_PINCTRL_PXA3xx)	+= pinctrl-pxa3xx.o
obj-$(CONFIG_PINCTRL_MMP2)	+= pinctrl-mmp2.o
obj-$(CONFIG_PINCTRL_PXA168)	+= pinctrl-pxa168.o
obj-$(CONFIG_PINCTRL_PXA910)	+= pinctrl-pxa910.o
obj-$(CONFIG_PINCTRL_SIRF)	+= pinctrl-sirf.o
obj-$(CONFIG_PINCTRL_TEGRA)	+= pinctrl-tegra.o
obj-$(CONFIG_PINCTRL_TEGRA20)	+= pinctrl-tegra20.o
obj-$(CONFIG_PINCTRL_TEGRA30)	+= pinctrl-tegra30.o
obj-$(CONFIG_PINCTRL_TEGRA114)	+= pinctrl-tegra114.o
obj-$(CONFIG_PINCTRL_U300)	+= pinctrl-u300.o
obj-$(CONFIG_PINCTRL_COH901)	+= pinctrl-coh901.o
obj-$(CONFIG_PINCTRL_MAX77660)  += pinctrl-max77660.o
obj-$(CONFIG_PINCTRL_PALMAS)	+= pinctrl-palmas.o
