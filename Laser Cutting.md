
## 1. Using Onshape

 - Make sure you register on [Onshape](https://www.onshape.com/en/) using your student account.
 - After registration, search for `Buildathon template` and right click to copy.
	 - ![[Pasted image 20241008182056.png]]
- Basic control: Right click to rotate around, press down scroll to move around, left click to select
- Create a new sketch here ![[Pasted image 20241008182606.png]]
- Aim: try to create a part that is the same as above, which can fit the servo motor inside (see `Assembly1` tab at the bottom)
- **3mm** is the minimum width if you want to make a strong 3d printing material.
- **0.2mm** is a good tolerance to make.
- [Some materials](https://www.youtube.com/watch?v=pMWnsHpDlQE&list=PLxmrkna-ixrIQmsPR3MITi4Ru1bnMH4-l) that might be helpful

## 2. Laser Cutting

 - MakerSpace has good videos on that.
 - Basically: cutting on flat material using 2-D shapes

### Process

1. Creating the .DXF file
2. Laser cut settings
3. Laset cut using trotec

### Creating DXF File

1. Export the Onshape model as .dxf file
	 - Right click a plane and select export as .dxf ![[Pasted image 20241008192459.png]]
1. Convert an image to dxf using online resources, the image should contain lines only

There are various templates based on the setting of the laser cutting, generally please ask the staff for which template to use.

Kirby uses 400.

You can choose to either cut or engrave on your material.

### Tips

1. When you have a donut-like shape to cut, always cut the inside shape first, or else the 
2. Checkout the laser cutting badge
3. Video is given in the slide (available on Wednesday).

### Why use laser cutting?

1. Faster than 3D printing. (if you can use laser cutting, no need to do 3d printing)
2. Does not cost points.

## 3. About the Breadboard Power Supply Module

### Why use it

1. Built-in voltage regulator
2. Secure power connection
3. Built in switch and usb port

If we use anything over 6.5V:
 - Plug it into the Power Port which will bring it down to 3.3/5V. DO NOT CONNECT DIRECTLY TO THE HEADER PINS
If we use anyting between 3.3V-6V:
 - Connect the power supply to either 5V & GND or 3.3V & GND depending on the required voltage.
IF YOU SMELL SOMETHING AND/OR SEE SMOKE, IMMEDIATELY ASK FOR HELP