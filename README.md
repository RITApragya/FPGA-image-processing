# FPGA-image-processing

Using 2D convolution to apply a 3x3 kernel over an image to perform basic image processing operations like Sobel Kernel Edge Detector, grayscale and box blurring. Line Buffers are used to load 3 rows of pixels at a time to perform the convolution operation over a 3x3 area of pixels. The output is stored in a FIFO and later sent out to the CPU via DMA when the interrupt is triggered.
