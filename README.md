# CPLDCOMTrigger



## Description

A Python script depends on Impacket scripts to trigger the loading of a .cpl file into memory using a DCOM object. The CPL file path must already be added to the registry.
The script uses the Open function in the IOpenControlPanel interface to load the CPL (Control Panel Item) DLL into memory.

## Usage

`python3 CPLTrig.py [[domain/]username[:password]@]<targetName or address> -cpl 'mycpl'`

The script will return error but the dll will be loaded successfully

Note: Any random name can be provided for the -cpl argument.

## Authors and acknowledgment

Haidar kabibo. Kaspersky Security Services. X: https://x.com/haider_kabibo

## License

This software is provided under MIT Software License.
