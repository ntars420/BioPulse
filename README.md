# BioPulse     
## A compact plant health monitor enclosure made with 3D printing and laser-cutting technologies

## 1. Product Concept
In the future, humanity has invented technology to derive energy from plants. Professionals plant vegetation for each household to meet all of the home's energy needs. The product "BioPulse" is designed to monitor the status of these plants, using simple interactions to help non-expert users stay informed about the plant's condition in a timely manner. One end of the product connects to a sensor inserted into the plant's soil. It uses different colored lights to indicate the plant's various states. Users can also check an electronic screen for further details about the plant's specific situation.

## 2. Product Composition
### (1) Product Components:
Base:
![03669f2396f398dc133ca8a3d053ab36](https://github.com/user-attachments/assets/4b8a7aac-eb66-4c3f-a018-fde55e44be1c)
Lid:
![9dba8dc08a5cd4c1a4d3503a1715fb8d](https://github.com/user-attachments/assets/0e06b131-80a8-414e-92b4-41d561f55b63)
Acrylic Panel:
![26147dde889d7a02f18cc404adb849f8](https://github.com/user-attachments/assets/aa95a1c3-5685-49d2-ac73-8e065f21dfda)
### (2) Required Tools & Materials:
① Any modeling software (e.g., Rhino, SketchUp, Blender);
② Any software capable of drawing vector graphics (e.g., Adobe Illustrator, Autodesk CAD, etc.);
③ UltiMaker Cura software (for processing 3D print files);
④ 3D Printer;
⑤ Laser Cutter;
⑥ 2mm thick acrylic sheet.

## 3. Production Steps
### (1) Making the Base and Lid (Using 3D Printing Technology)
① Use any modeling software (e.g., Rhino, SketchUp, Blender) to model the base and lid, and export them in STL format. (Corresponding files: BOX.stl, LID.stl)
<img width="2553" height="1528" alt="image" src="https://github.com/user-attachments/assets/28c6f8cf-2789-4869-880a-99f83cd2ff16" />
![ce91f700abe1198497ed0e90d7727cb0](https://github.com/user-attachments/assets/88c4d33a-4093-4b79-8530-1d3290299d42)

② Import the obtained STL files into UltiMaker Cura software, click 'Slice', and after generation, export to get G-code files. (Corresponding files: CFFFP_BOX.gcode, CFFFP_LID.gcode)
![d95fe91da326dfa96015e1a433136766](https://github.com/user-attachments/assets/4ec60d67-09b6-4004-868f-2ef1113a5e9f)

③ Remove the SD card from the 3D printer, connect it to a computer using a card reader, copy the G-code files onto the SD card, and reinsert the SD card into the 3D printer.
![247cae49c5b04920f25c7770d7693d65](https://github.com/user-attachments/assets/3bb8c933-f856-4233-986a-2cbcaa592df1)

④ Start the 3D printer, select the file(s) to print, and begin printing.
![237ed0f5ce420d4bbb134a667f366c0b](https://github.com/user-attachments/assets/034b9fd7-8e05-47d8-bb98-3162e05e8c22)


### (2) Making the Acrylic Light Component (Using Laser Cutting Technology)
① Use any software capable of drawing vector graphics (e.g., Adobe Illustrator, Autodesk CAD, etc.) to draw a leaf shape (you can trace an imported image or draw one yourself); export the file in a suitable format (e.g., .ai, .dxf, .pdf). (Corresponding file: LEAF.dxf).
<img width="1957" height="1415" alt="image" src="https://github.com/user-attachments/assets/e669c70c-4ce3-4364-bf71-bc1485615dae" />

② Import the image file into the laser cutter control software (e.g., RDWorks). Select the appropriate printing speed and power for laser cutting the material, and proceed with printing. This project uses a 2mm thick acrylic sheet. Note: The thickness of the acrylic sheet must correspond to the width of the slot on the lid.
（Sorry,I forgot to take a photo here.)

### (3) Product Assembly
① Fit the lid onto the base.
![847fee9e2934312b613cdc9939fe9939](https://github.com/user-attachments/assets/1a7a8764-be1f-495f-956f-99d5a4eb1abb)
② Insert the acrylic panel into the slot on the lid.
![4372642e6bfd03ef5626e8f298d39495](https://github.com/user-attachments/assets/7fcf5cd4-dccf-4ac8-bd12-f39565081453)
### Some tips: 
1. It might be necessary to make the slot of the box looser; otherwise, it will be very difficult for the lid and the box to fit together.
2.  2 The groove of the lid needs to be slightly narrower than the thickness of the acrylic sheet; otherwise, the acrylic sheet is prone to fall off
