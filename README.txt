This is the Mandelbrot image generator project utilising the PYNQ-Z2 board.

To run this project a 'PYNQ-Z2' board is required. Below are detailed the files required to run each variation.
System Generator files are also provided which have to be ran using the 2020.2 version of Matlab and Simulink. 
To generate a brand new bitstream and handware handoff (.hwh) files the Vivado 2020.2 version is required.

Unfortunately, the Axi Stream implementation of this project was not completed. 
The hardware should function as required, but the code sends an incorrectly formatted data-stream into the hardware.
These files can still be viewed, but should not be expected to work.

The files required in the same directory as the Jupyter notebook 'Mandelbrot_Axi4_lite.ipynb' to run the AXI4-Lite variation are:
    'mandel_wrapper.bit'
    'mandel_wrapper.hwh'

The files required in the same directory as the Jupyter notebook 'Mandelbrot_Axi_stream.ipynb' to run the Axi-Stream variation are:
    'Mandel_stream_wrapper.bit'
    'mandel_stream_wrapper.hwh'

Also included, are a selection of images produced by both the hardware itself, and by an implementation of the system on Visual Studio Code.
Due to the manner of the hardware implementation, the software implementation operates at much greater speeds, allowing for more detailed
images and greater 'zooming' capabilities.
