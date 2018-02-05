The Mayo Clinic Analyze 7.5 format is used for the storage of images created during brain-related research. It consists of a 348 byte header '.hdr' that describes image data stored in a corresponding '.img' file.

The first four bytes of the '.hdr' file define the length of the header. In practice this is 348 bytes, although at the outset it could be any 4-byte length. Headers can be encoded as little- or big-endian, and the encoding of '348' is used to test endianness.  

This signature is written with an end-of-file offset to test both the 348 byte size and the magic number.

Sample '.hdr' files are from the The Virtual Brain.