# poc
A repository recording the poc file of the crashes I found.

## Index

| CVE | Package | Version | Program | Summary | PoC |
| --- | --- | --- | --- | --- | --- |
| CVE-2018-20189 | graphicsmagick | gm | 89e43 | Assertion Failure in WriteOnePNGImage | [file](graphicsmagick/assertion-failure_png.c-7503)|
| CVE-2019-7581 | libming | 50098 | listswf | Memory Allocation Failure in parseSWF_ACTIONRECORD | [file](libming/memory-allocate-failure_parser.c-1142) |
| CVE-2019-7582 | libming | 50098 | listswf | Memory Allocation Failure in readBytes | [file](libming/memory-allocate-failure_read.c-252) |
| CVE-2019-7663 | libtiff | 56a19 | tiffcp | Segment Fault in cpSeparateBufToContigBuf | [file](libtiff/segment-fault_tiffcp.c-1245) | 
| CVE-2022-22844 | libtiff | cd57b | tiffset | Global Buffer Overflow in _TIFFmemcpy | [file](libtiff/global-buffer-overflow_tif_unix.c-346) |


