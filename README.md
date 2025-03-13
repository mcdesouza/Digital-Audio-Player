#🚀 STM32 Digital Audio Player

This project is a portable WAV audio player built using the STM32F407G-DISC1 microcontroller. The player reads WAV files from a connected USB drive, decodes the audio, and outputs it through a Digital-to-Analog Converter (DAC) to a headphone jack.
##🎯 Project Overview

    Developed a real-time audio playback system on the STM32 platform using CubeIDE.
    Configured USB Host for FAT32 file access and I2S for audio streaming to the DAC.
    Designed for efficient real-time processing with minimal latency.
    Supports adjustable output amplitude using a potentiometer.

##🛠️ Features

✅ Supports 16-bit PCM WAV files.
✅ FAT32 file system compatibility via USB drive.
✅ Real-time audio playback using DMA.
✅ Adjustable volume with a potentiometer.
✅ Output through 3.5mm audio jack (compatible with headphones and speakers).
🧰 Hardware Components

    STM32F407G-DISC1 microcontroller
    USB Drive (for file storage)
    DAC for audio output
    Potentiometer for volume control
    Headphone jack for audio output
