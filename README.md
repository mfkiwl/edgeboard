<img src="./board_files/fz3a/A.0/fz3a_board.jpeg" alt="logo" height="160" align="right" />

# Awesome EdgeBoard Lite

**Use EdgeBoard Lite as a general Zynq development board**

[![en](https://img.shields.io/badge/lang-zh--cn-red.svg)](./README.zh-cn.md)

EdgeBoard Lite (a.k.a. FZ3) is an FPGA-accelerated embedded AI computing board, launched by Baidu Brain in 2019. As part of the Baidu AI solution, it can quickly depoly the neural network models.

The board is based on Xilinx Zynq Ultrascale+ ZCU3EG MPSoC, which can achieve 1\~2 TOP/s with an average power of 5\~10 W. It also has the following peripherals:

- 2GB DDR4 RAM
- 8GB eMMC Flash
- 256Mb QSPI Flash
- PCIe x1 connector
- MIPI camera connector
- BT1120 HDTV connector
- 1000Mbps Ethernet
- TF-card slot
- USB Hub (1 x USB 3.0, 1 x USB 2.0)
- Mini DisplayPort (miniDP)
- USB UART

In addition to the rich peripherals, what matters more is that it only costs \~1000 CNY (about 140 USD)! It is almost the cheapest Xilinx Zynq Ultrascale+ development board. Another Zynq ZCU3EG board [Ultra96](https://www.96boards.org/product/ultra96), much loved by developers, is priced at 249 USD. In the Chinese market, Ultra96 even costs more than 2200 CNY, more than double of EdgeBoard Lite.

Unfortunately, Baidu sells the EdgeBoard as its AI solution instead of a general-purpose development board. Therefore, it is a bit difficult for us to obtain full official support (You can send emails to Baidu to request limited documents).

This repository contains materials that help us use EdgeBoard as a general Ultrascale+ Zynq development board.

## Documents

Here are some documents you may need, and you can find them in the `./docs` folder. It should be noted that most of them are in Chinese, and currently do not have an English translation.

- [Hardware handbook](./docs/FZ3A-Hardware-Handbook.pdf) provided by ALINX. Its [online version](https://ai.baidu.com/ai-doc/HWCE/8kq9b2121) can be also found on Baidu.
- [PCB-level circuit schematic](./docs/FZ3A-Schematic.pdf) provided by ALINX
- [IO Definition](./docs/FZ3A-io-definition.xls) provided by ALINX

Most of above documents are from ALINX, the manufacturer of this board.

Documents about how to run EasyDL/PaddlePaddle models on the EdgeBoard Lite will not be listed here. You can visit [its product website](https://ai.baidu.com/ai-doc/HWCE/Yk3b86gvp) to access them.

## Hardware Support Files

I plan to port the PYNQ framework to EdgeBoard Lite, and provide the image file as well as necessary support files, such as BSP files and Vivado board files.

Work is still in progress, so far only the Vivado board files can be provided.

- [Vivado board files](./board_files) by myself
- BSP file
- PYNQ image file

## License

Except for those already noted in the text, other documents written by myself are released under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) and the code is released under the [MIT](./LICENSE) license.
