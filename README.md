# TXb - 2HP i2c Bus Board w/ 3.5mm Connectors

The TELEXb (TXb) is a 2HP powered bus board for the i2c ecosystem that also enables the connection of external devices using the two 3.5mm stereo jacks at the top and the bottom of the module. These jacks can be used for connection to the 16n FaderBank, TXb that are in disconnected rack rows, or to fiendishly wonderful Frankenstein machines of your own creation.

<img src="https://cdn.shopify.com/s/files/1/1856/2693/products/TXb_front-top_1024x1024@2x.jpg?v=1549508398" alt="TXn" width="600"/>

## High-Level i2c Tips

There are some key things to keep in mind with the TXb (and i2c busses in general):

- Powered bus boards are required when you connect three or more devices to your Teletype via i2c.
- You should only have one bus board connected to power at a time.
- Connections should be kept as short as possible using high-quality cabling (less than 3.5mm).
- There still are practical limits to having a stable i2c bus that are highly dependent on the topology of your deployment. Plan for some trial and error.

Want more help understanding what i2c can and can't do and how to use it in your setup? Check out this awesome [User's Guide to i2c](https://llllllll.co/t/a-users-guide-to-i2c/19219) that was put together by some awesome people.

## Module Specifications

- +12V: 1 mA 
- -12V: 0 mA
- +5V: 0 mA
- 2HP
- 20.5mm Depth

## Folders & Files Explained

* **assistive**: 
	* ```TXb Frame``` - a 3D printed frame to hold multiple TXb at a time
	* ```TXb Stencil Frame``` - a 3D printed stencil frame to hold the TXb in place while applying solder paste
	* ```TXb Stencil.svg``` - the solder paste stencil for laser cutting
	
* **board**
	* ```gerbers``` - the gerbers files (and Eagle files) for the PCB
	* ```images``` - image rederings of the PCB
	* ```TELEXb_v1.2.brd/sch``` - the master Eagle file for the TXb
	
* **extras**
	* ```instructions.docx``` - the instructions delivered with the pre-built module
	
* **panel**
	* ```metalphoto``` - the individual files used for the creation of the metalphoto panel in the retail version
	* ```TXb.ai/svg``` - the panel files
	* ```TXb_lasercut.svg``` - the file used for cutting prototype panels out of acrylic
	* ```TXb_lg.png``` - a big version of the panel
	* ```TXb_mp.zip``` - the archive sent for fabrication
	* ```TXb_sm.png``` - a small photo of the panel

* ```TXb BOM.csv``` - the BOM for this version of the TXb.

## Links

Visit the TXb on Modular Grid:

* [Modular Grid](https://www.modulargrid.net/e/other-unknown-telexb)

Pre-built TXb are occasionally made availalbe for purchase here:

* [store.bpcmusic.com](https://store.bpcmusic.com/products/telexb)

## License

[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

