obj-$(CONFIG_MTK_SMART_BATTERY) += battery_meter.o battery_common.o
ifeq ($(X2_CHARGING_STANDARD_SUPPORT),yes)
    obj-$(CONFIG_MTK_SMART_BATTERY) += x2_charging.o
endif

ifeq ($(MTK_FAN5402_SUPPORT),yes)
    obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
else ifeq ($(MTK_FAN5405_SUPPORT),yes)
        obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o 
else
    ifeq ($(MTK_SWCHR_SUPPORT),yes)
        obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
    else
        ifeq ($(MTK_BQ24158_SUPPORT),yes)
            obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o 
        else
            ifeq ($(MTK_BQ24196_SUPPORT),yes)
                obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
            else
                ifeq ($(MTK_BQ24296_SUPPORT),yes)
                    obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
                else
                    ifeq ($(MTK_NCP1851_SUPPORT),yes)
                        obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
                    else
                        ifeq ($(MTK_NCP1854_SUPPORT),yes)
                            obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
                        else
                            ifeq ($(MTK_BQ24160_SUPPORT),yes)
                                obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
                            else
                                ifeq ($(MTK_BQ24157_SUPPORT),yes)
                                    obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
                                else
                                    ifeq ($(MTK_BQ24250_SUPPORT),yes)
                                       obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o 
                                    else
                                       ifeq ($(MTK_BQ24261_SUPPORT),yes)
                                          obj-$(CONFIG_MTK_SMART_BATTERY) += switch_charging.o
                                       else
                                          obj-$(CONFIG_MTK_SMART_BATTERY) += linear_charging.o
                                       endif
                                    endif
                                endif        
                            endif        
                        endif
                   endif
                endif
            endif
        endif  
    endif    
endif
