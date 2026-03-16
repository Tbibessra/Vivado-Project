
# Sobel Edge Detection on Zynq

## Description
This project implements Sobel edge detection using hardware acceleration on a Xilinx Zynq platform.

The Sobel filter is implemented as a custom IP core using Vivado HLS and connected to the Processing System through AXI DMA.

## Technologies Used
- Xilinx Zynq
- Vivado
- Vivado HLS
- AXI DMA
- C programming

## Project Architecture
The system is composed of:

- Processing System (PS)
- AXI DMA
- Sobel HLS IP Core
- DDR Memory

The PS sends image data to the Sobel IP via AXI DMA and receives the processed image.

## Input
Grayscale image

## Output
Edge-detected image using Sobel filter

## Author
Tbib Essra
