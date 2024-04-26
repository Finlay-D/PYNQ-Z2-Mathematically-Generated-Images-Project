This is the Mandelbrot image generator project utilising the PYNQ-Z2 board.
To run this project a 'PYNQ-Z2' board is required. Below are detailed the files required to run each variation.
System Generator files are also provided which have to be ran using the 2020.2 version of Matlab and Simulink. 
To generate a brand new bitstream and handware handoff (.hwh) files the Vivado 2020.2 version is required.

The files required in the same directory as the Jupyter notebook 'Mandelbrot_Axi4_lite.ipynb' to run the AXI4-Lite variation are:
'mandel_wrapper.bit'
'mandel_wrapper.hwh'

The files required in the same directory as the Jupyter notebook 'Mandelbrot_Axi_stream.ipynb' to run the Axi-Stream variation are:
'Mandel_stream_wrapper.bit'
'mandel_stream_wrapper.hwh'