# MULTITHREADED-FILES-COMPRESSION-TOOL
 Project Goals
Compress and decompress files using a standard algorithm (e.g., gzip/zlib or custom RLE).

Multithreading to optimize performance—process file chunks in parallel.

Performance demonstration—compare single-threaded vs multithreaded times.
Multithreading Strategy
Read file into memory and divide it into chunks.

Each chunk is handled by a thread for compression/decompression.

Merge output in correct order.

#OUTPUT
![Image](https://github.com/user-attachments/assets/e7b2c210-a546-4d40-96b6-dfbcc6e9b42f)
