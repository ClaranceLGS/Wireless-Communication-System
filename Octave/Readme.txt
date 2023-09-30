** Images must be converted to binary formats before transmitting through GNURadio.
** 'Image_Binary_Mono.m', and 'Image_Binary_RGB.m' octave codes are used to convert images into binary files. Mono images reasult in a single binary file, and color imaged results in three binary files.
** The recieved files through GNURadio can be reconstructed into images by 'Image_Reconstruct_Mono.m' and 'Image_Reconstruct_RGB.m' codes.
** 'padding.m' and 'rep_find.m' are additional functions used for adding redundant bits to compensate bit losses.
