# Thicc Plate Guide

1. Navigate to [KLE](https://www.keyboard-layout-editor.com/)
2. Make your layout (For this example we will use the minivan layout [Minisub](https://trashman.wiki/community/pcbs/minisub)) [KLE link here](https://www.keyboard-layout-editor.com/#/gists/1fa1f216f42ccb54e6a5849ecc492d73)
	2.1. For any bars 2u and over that you would like to have flipped stabilizers, you will need to select they key and the homing option
		![KLE Homing Image](Show the option being selected)
	2.2. If your layout has multiple layouts for an area you will need to stack/compress all layout options into one line
		![Compressed layout](Show before and after)
3. Navigate to [Keebio Plate Generator](https://plate.keeb.io/)
3. Take your KLE raw data and paste into the 'KLE Raw Data' field
4. Select the 'Combine overlapping layouts'
5. Download the DXF and save to a location you can find later
6. Open [Fusion360](https://www.autodesk.com/products/fusion-360/personal)
7. Start a new project
8. Save the new project
9. Create a new component and name it 'Plate'
10. Create a sketch on the plane of your choice
11. Choose insert and DXF
12. Choose your DXF and it will populate
13. Drag to select all and choose fix so you don't accidently move anything
14. Create a rectangle around the perimiter of the layout
15. Hit the 'D' key and select the top of a switch cutout on the top row and then the top line on the rectangle you created
16. Make this 2.525mm
17. Repeat this step on all 3 other sides
18. 