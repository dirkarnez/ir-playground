ir-playground
=============
### IR Loader Hardwares [SONIC IR Speaker Cabinet Simulator Impulse Response Loader - SONICAKE](https://www.sonicake.com/products/sonic-ir)
- [client](https://ir-converter.sonicake.net/#/)
  - `w.FS("writeFile","input.wav",r),t.next=11,w.run("-i","input.wav","-acodec","pcm_s24le","-ac","1","-ar","44100","-bitexact","-t","0.023219955","output.wav"`

### MCU
- HC32F460
  - https://www.zlgmcu.com/data/upload/file/Utilitymcu/HC32F460.pdf
  - https://github.com/SoCXin/HC32F460
  - [jinsc123654/hc32f460_cherryusb_gcc: cherryusb在hc32f460上启动](https://github.com/jinsc123654/hc32f460_cherryusb_gcc)
  - [记：华大HC32F460系列搭建FreeRTOS记录 » GreenDream](https://www.abcde.engineer/jihuadahc32f460xiliedajianfreertosjilu/)
  - [国产(华大)单片机 hc32f460入门-CSDN博客](https://blog.csdn.net/u011624093/article/details/119530135)
    
### Tutorials
- [(Sponsored) Real-Time Impulse Response Simulation in Software (STM32 DSP) - Phil's Lab #126 - YouTube](https://www.youtube.com/watch?v=xjQBpsu9Tzc)
- [[#5] IIR Filters - Audio DSP On STM32 with I2S (24 Bit / 96 kHz) - YouTube](https://www.youtube.com/watch?v=lNBrGOk0XzE&pp=ugUEEgJlbg%3D%3D)
- https://www.st.com/resource/en/application_note/an4841-digital-signal-processing-for-stm32-microcontrollers-using-cmsis-stmicroelectronics.pdf
- https://www.arterytek.com/download/APNOTE/AN0036_DSP_Instruction_and_Library_on_AT32_ZH_V2.0.1.pdf;jsessionid=cFeMAMN1RDD9NdD7EyjMRhfOwHgH0JtV19FwDlvnU8JyXPHsmO_K!287432582
- [DSP Instruction and CMSIS-DSP Library Guide for AT32 Cortex-M4F MCUs | by ARTERY Technology | Medium](https://medium.com/@arterychip/dsp-instruction-and-cmsis-dsp-library-guide-for-at32-cortex-m4f-mcus-c75ae14fc962)
- https://developer.arm.com/cfs-file/__key/communityserver-blogs-components-weblogfiles/00-00-00-21-42/7563.ARM-white-paper-_2D00_-DSP-capabilities-of-Cortex_2D00_M4-and-Cortex_2D00_M7.pdf
- [[Donald_S._Reay]_Digital_Signal_Processing_Using_t(BookZZ.org).pdf](https://kolegite.com/EE_library/books_and_lectures/%D0%9C%D0%B8%D0%BA%D1%80%D0%BE%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D0%BE%D1%80%D0%BD%D0%B0%20%D1%81%D1%85%D0%B5%D0%BC%D0%BE%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D0%BA%D0%B0/%D0%9C%D0%B8%D0%BA%D1%80%D0%BE%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D0%B5%D1%80%D0%B8/%5BDonald_S._Reay%5D_Digital_Signal_Processing_Using_t%28BookZZ.org%29.pdf)
