## StarWind V2V Converter Portabl
- Portable Version
- Also patched binary to disable annoying webpage popup when exiting V2V Converter.
- Thats about it.

Patch info:

------------------------------
What was modified:
------------------------------
Original instruction:
[7FF717C95700]     | 00007FF717C95700:L"https://www.starwindsoftware.com/download-free-tools?intype=%d&inlocation=%d&outtype=%d&outlocation=%d&page=%d&res=%d&insize=%I64u&version=%s&id=%08x"

Hex:
[Original]
48 8D 15 08 A8 11 00  

[Modified]
90 90 90 90 90 90 90

Just changed to NOPs to skip.
