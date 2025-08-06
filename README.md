# FPGA Image Pipeline Project

This project is a 12-week side project to implement a real-time image edge detection pipeline using FPGA (Spartan-7) and Python cocotb verification.

## Features
- FPGA implementation of a 3x3 Sobel edge detector
- Line-buffered image processing
- Python OpenCV interface for image conversion
- UART streaming from FPGA to host
- Cocotb-based simulation and verification framework
- Tkinter GUI for easy input/output testing

## Folder Structure
- `rtl/` - Verilog modules
- `sim/` - cocotb testbenches and utilities
- `scripts/` - image conversion and visualization scripts
- `gui/` - user interface for demo
- `data/` - input and output images
- `reports/` - documentation and notes
