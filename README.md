# OpenPLC_MegaInd_Interface_PSM
This is the PSM interface codes between OpenPLC and MegaInd Board
The open PLC version used is 2.01.
PSM (Python Sub Module) a tool used together Open PLC software becomes a gateway reading variables from a Industrial board (MegaIoInd from sequent mycrosystems company).
This board is assembled in a I2C busbar on raspberry PI platform.
These variables like digital or analog, in a bi-directional way are read and send to PLC user software in this case developed in ladder language (from open PLC).
This is the way variables from OpenPLC can be exchanged to external devices (MegaIoInd) and once these variables are present in a Python Language, using the resources of this language, we are allowed to exchange them to any other system provided by this language.
