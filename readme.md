PowerShell Script to calculate CCITT CRC16 checksum for hex-encoded strings
===========================================================================

Herwig Habenbacher 2017

License: Public Domain, MIT, Apache or whatever you prefer

***This file is not guaranteed by me to be error free. Every effort  
has been made to ensure proper data-types and declarations, but this program  
is distributed WITHOUT ANY WARRANTY; without even the implied  
warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  
Use it at your own risk!***  

The reason to create this small script was to generate a CCITT CRC16 (0xFFFF) Checksum for hex-encoded strings for testing.  

You can verify your results with:  
https://www.lammertbies.nl/comm/info/crc-calculation.html

> **Please Note:**
> If you try for example hex _"313233343536373839"_ you will get _"0x29B1"_  
> The PowerShell Script will return _"B129"_  on Intel Architectures.  
> This is due to Low-Endian Encoding...
