# Tools and Materials
1. A small drill.
2. Soldering iron.
3. Solder.
4. Flux.
5. An iron.
6. Thermal paper.
7. and all the previous tools from the last week.

# Components
1. 3x Screw terminal 01x02.
2. 2x 1k Resistors.
3. 2x 2n2222 transistors.
4. 2x Diodes.
5. 2x 5V Relays.

# Steps

## 1. Schematic
Design the schematic using any suitable software, for example KiCAD.
<img width="1018" height="563" alt="Screenshot 2026-10-15 180448" src="https://github.com/user-attachments/assets/58d665be-2af3-4a0e-9a9b-362d29d9fc34" />

## 2. PCB layout
Switch to PCB editor, place the components and draw the routs.

A plugin called Freerouting can be used to automatically route the PCB.

Optionally, use a plugin called Round tracks which lowers the resistance of the tracks, and makes it look better in my opinion.
<img width="1276" height="897" alt="Screenshot 2026-10-15 180610" src="https://github.com/user-attachments/assets/81797869-f013-4c0e-b33d-5b7d29cbf078" />
<img width="737" height="463" alt="Screenshot 2026-10-16 110210" src="https://github.com/user-attachments/assets/b0eac5b1-3cde-489d-bbe6-da84c5020e04" />


## 3. Save and print the PCB layout
In KiCAD open file > plot, in plot format select PDF, select the place you want to save the layout in from output directory, in a tab called include layers select B.Cu and Edge.Cuts.

Befor pressing plot make sure the scale is 1:1 and that any text is mirrored, **but not the layout**.
<img width="985" height="787" alt="Screenshot 2026-10-16 102320" src="https://github.com/user-attachments/assets/2aad8ccc-5805-47df-b329-8c33139822bb" />

Print the layout on thermal paper.
<img width="1152" height="864" alt="WhatsApp Image 2026-10-16 at 10 37 10" src="https://github.com/user-attachments/assets/d6bb8aed-848c-4d82-a26b-0aa808421467" />


## 4. Ironing
Put the layout side of the thermal paper on the copper side of the Fr4, then iron the thermal paper for 3-8 minutes depending on how hot your iron is, make sure to keep moving the iron on the thermal paper.

Let it cool down and take off the thermal paper slowly and carefully.
<img width="1152" height="864" alt="WhatsApp Image 2026-10-15 at 17 59 00" src="https://github.com/user-attachments/assets/ab9bebe8-d010-4742-8ba2-3914adbe402d" />


## 5. Acidification
Put the copper plate in ferric chloride acid until all the copper is gone (follow the steps from week01).
<img width="1152" height="864" alt="WhatsApp Image 2026-10-15 at 17 59 00" src="https://github.com/user-attachments/assets/28f28a6d-bf76-473b-b030-057b79d429b9" />

## 6. Sand the metallic marker
Sand off the metallic marker with the fine steel wool.
<img width="1152" height="864" alt="WhatsApp Image 2026-10-15 at 17 59 01" src="https://github.com/user-attachments/assets/37ae184f-d002-4497-ab7d-b85e72e2e2e4" />

## 7. Drill
Drill the holes, 0.8 mm for the small ones and 1 mm for the large holes.

## 8. Soldering
Solder the components on the PCB
<img width="1152" height="864" alt="WhatsApp Image 2026-10-16 at 11 05 02" src="https://github.com/user-attachments/assets/8599430c-9256-4603-91e8-e6288ce096ca" />
<img width="1152" height="864" alt="WhatsApp Image 2026-10-16 at 11 05 03" src="https://github.com/user-attachments/assets/eac58f98-f49a-420e-a4b9-0aaa5d0e433e" />
