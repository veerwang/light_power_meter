## installed library
pip install pyvisa
pip install pyvisa-py
pip install pyUSB

sudo apt-get install python3-usb
sudo move 99-com.rules /etc/udev/rules.d/

## initialize API explaination
rm.open_resource('USB0::0x1313::0x8078::P0015699::INSTR')
0x1313: VendorID
0x8078: ProductID (PM100D)
P0015699: SerialNumber

## demo
https://github.com/Thorlabs/Light_Analysis_Examples.git
