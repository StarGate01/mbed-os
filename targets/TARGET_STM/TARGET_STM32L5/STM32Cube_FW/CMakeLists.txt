# Copyright (c) 2020 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

add_library(mbed-stm32l5cube-fw INTERFACE)

target_sources(mbed-stm32l5cube-fw
    INTERFACE
        STM32L5xx_HAL_Driver/stm32l5xx_hal.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_adc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_adc_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_comp.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_cortex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_crc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_crc_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_cryp.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_cryp_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_dac.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_dac_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_dfsdm.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_dfsdm_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_dma.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_dma_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_exti.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_fdcan.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_flash.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_flash_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_flash_ramfunc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_gpio.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_gtzc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_hash.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_hash_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_i2c.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_i2c_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_icache.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_irda.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_iwdg.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_lptim.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_mmc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_mmc_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_nand.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_nor.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_opamp.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_opamp_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_ospi.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_otfdec.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_pcd.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_pcd_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_pka.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_pwr.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_pwr_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_rcc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_rcc_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_rng.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_rng_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_rtc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_rtc_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_sai.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_sai_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_sd.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_sd_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_smartcard.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_smartcard_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_smbus.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_smbus_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_spi.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_spi_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_sram.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_tim.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_tim_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_tsc.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_uart.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_uart_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_usart.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_usart_ex.c
        STM32L5xx_HAL_Driver/stm32l5xx_hal_wwdg.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_adc.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_comp.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_crc.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_crs.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_dac.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_dma.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_exti.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_fmc.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_gpio.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_i2c.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_icache.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_lptim.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_lpuart.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_opamp.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_pka.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_pwr.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_rcc.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_rng.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_rtc.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_sdmmc.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_spi.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_tim.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_ucpd.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_usart.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_usb.c
        STM32L5xx_HAL_Driver/stm32l5xx_ll_utils.c
        system_stm32l5xx.c
)

target_include_directories(mbed-stm32l5cube-fw
    INTERFACE
        .
        CMSIS
        STM32L5xx_HAL_Driver
        STM32L5xx_HAL_Driver/Legacy
)
