# EX-No.6.1. DESIGN THE VARIOUS PARTS OF A MECHANICAL COMPONENT AND ASSEMBLE

## DATE:19/11/2026

## AIM: 
To Design the various parts of a mechanical component and assemble it using a bottom-up approach then convert it into the orthographic view

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 4 GB of RAM (integrated graphics recommend 6 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## COMMANDS USED:
### Align: 
The Align tool allows you to align, distribute or organize selected elements, annotations, tags and text along the axis you specify. Furthermore, the Arrange feature will automatically neatly place your tags around the current view.
The Align plug-in for Autodesk® Revit® can help to save time while producing complex drawings with large sets of annotation.
Just select a few elements and the Align tool will sort them for you.

### Derive:
Insert design elements such as Components, Bodies, Sketches, Work geometry, Flat patterns or parameters from another design.
The inserted elements update with changes to the original design

### Move: Moves the selected face, body, sketch, or construction geometry a specified distance or angle.
Select the objects to modify then specify the distance or angle. Use set pivot to reposition the manipulator

## PROCEDURE:
1. Open Autodesk Fusion, start a new design file, and set the document units to millimetres (mm).
2. Create a sketch on the XY plane for the base mounting plate, dimensioning the outer profile and pivot pin holes.

<img width="475" height="482" alt="WhatsApp Image 2026-11-25 at 9 22 20 PM" src="https://github.com/user-attachments/assets/c52ad22f-c66e-440b-8c84-1e4a1e206941" />

4. Extrude the base plate profile to the required thickness and save it as a separate component.
5. Use the built-in Spur Gear generator (under Utilities > Add-Ins) to create two identical spur gears with matching module and tooth counts.

<img width="471" height="200" alt="WhatsApp Image 2026-11-25 at 9 22 53 PM" src="https://github.com/user-attachments/assets/489c3932-bb6c-4d4f-9dbf-fd076d8a1bdb" />

7. Sketch and extrude the inner white parallel connecting links with accurate center-to-center hole distances.
8. Sketch and extrude the outer gripper arms and angled jaws to match the linkage geometry.
   
<img width="862" height="317" alt="WhatsApp Image 2026-11-25 at 9 24 00 PM" src="https://github.com/user-attachments/assets/9659b4fc-8566-466b-a165-9d1a52adf3be" />

10. Apply small Fillets and Chamfers to all sharp outer edges and pin holes for smooth mechanical clearance.
11. Insert all individual components (base plate, two gears, two inner links, and two gripper jaws) into a main assembly file.
12. Apply a Rigid joint or Ground the base plate so it stays fixed in the workspace.
13. Use Revolute joints to attach the two spur gears to their respective pivot pins on the base plate.

<img width="776" height="547" alt="WhatsApp Image 2026-11-25 at 9 25 01 PM" src="https://github.com/user-attachments/assets/1571e948-26c4-4398-a551-b51cbe6ea082" />

15. Adjust the rotation angle of one gear slightly so its teeth mesh cleanly into the valleys of the second gear without interference.
16. Create a Motion Link between the two gear revolute joints with a -1 ratio so they rotate in opposite directions at equal speeds.
17. Connect the inner white links and outer gripper jaws to the base and gears using Revolute joints to complete the four-bar parallel linkage.

 

19. Enable Contact Sets or test the range of motion by dragging one gear to verify that the jaws open and close smoothly without colliding.
20. Save the completed assembly and generate a 2D engineering drawing with exploded and assembled views if required for documentation.

## OUTPUT:

<img width="962" height="631" alt="{A8D6ADC6-71BC-4825-A43A-BB030051AFE8}" src="https://github.com/user-attachments/assets/67ec52c0-cdfe-4983-bbba-3b3cbad2dbab" />

<img width="1112" height="777" alt="{E0673654-ACE0-4468-BF5C-582EDD0D4DE7}" src="https://github.com/user-attachments/assets/03580287-c080-4458-b59e-cb010fae4cbd" />

## RESULT:
Thus, a design of various parts of a mechanical component and assemble it using a bottom-up approach in orthographic view has been done
