# ST-M24SR64-NFC
This folder contains a library I wrote in MicroPython for ST's dynamic NFC tag M24SR64 ---> datasheet: https://www.st.com/resource/en/datasheet/m24sr64-y.pdf



**lib_nfc.py** is the library it contains low and high level methods (writeNDEFFile, eraseNDEFFile, readNDEFFile). Reading and erasing tags have been tested and are working properly. The writing functionality is not yet operational. 

**test_nfc.py** is an example script (it contains the library, standalone and raises no dependency errors). It reads the content of the tag, displays it and then erases its content and shows the empty tag.
