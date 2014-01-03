NicoletReader
=============

The NicoletFile class can be used to access data from Nicolet (.e) files using Matlab. 

1. This method can read the raw data from the .e files
2. Supports multiple sections within the .e file 
3. Cannot read events/annotation layers
4. Cannot read specific montages that are saved within the .e file

Please read the help section in the NicoletFile class definition for additional information.

**Install**

- Copy the @NicoletFile folder to a place on the Matlab path. 
- Create a Nicolet Object using: OBJ = NicoletFile('Filename').
