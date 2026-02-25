RC Preset

The CRC shall support a configurable preset value.

CRC Initial XOR

The CRC shall support configurable inital XOR for the first raw data.

CRC Output XOR

The CRC shall support configurable output XOR for the last raw data.

CRC Raw data region 

The raw data address map shall consist of 32 KiB continuous addresses to enhance DMA transfer performance.

CRC Polynomials

The CRC shall support fixed polynomials: crc_8_sae(0x1d), crc_8_autosar(0x2f), crc_16_ccitt(0x1021), crc_32(0x04C11DB7), crc_32c93(0xD419CC15). Additionally, the CRC shall support configurable polynomials for CRC8, CRC16, CRC32, and CRC64.

CRC interface

The CRC shall support AHB Lite slave interface for register configuration, data input, and data output. The AHB Lite slave shall support byte/halfword/word access, and support burst 4/8/16 for raw data region.
