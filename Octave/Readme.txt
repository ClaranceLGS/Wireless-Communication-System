### Image Transmission with GNU Radio
1. Binary Conversion for Transmission
  - Images must be converted to binary formats before transmission through GNU Radio.
  - Use the following Octave scripts for conversion:
      - Image_Binary_Mono.m: Converts monochrome images into a single binary file.
      - Image_Binary_RGB.m: Converts colour images into three separate binary files (one for each channel: R, G, and B).

2. Reconstruction of Received Images
  - The received binary files can be reconstructed into images using the following Octave scripts:
      - Image_Reconstruct_Mono.m: Reconstructs monochrome images.
      - Image_Reconstruct_RGB.m: Reconstructs color images.

3. Additional Functions for Error Handling
  - padding.m: Adds redundant bits to the binary files to compensate for potential bit losses during transmission.
  - rep_find.m: Aids in identifying and managing redundant bits for accurate reconstruction.
