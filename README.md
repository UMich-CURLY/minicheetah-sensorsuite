# Minicheetah Sensor Suite Mk V
![Image](https://github.com/UMich-CURLY/minicheetah-sensorsuite/tree/master/img/P1.png)
<br>3D-Printed sensor suite designed to augment Minicheetah autonomous capabilities. <br>
#### High Level Design Goals
* Secure/rigid/robust design
* Scalable platform
* Low Center of Mass
* Reduced part count
* Replicable assembly for other groups (parts should be easily manufacturable/sourceable)

#### Lower Level Design Goals
* Camera mount accepts either D435i or L515 camera
* Suite accommodates two straps for Minicheetah underbelly battery mounting solution

***(Extra points)***
Not an eyesore (hopefully).

## Printed Components
STL files found under /stl <br>
Support material is unnecessary for any part besides MkV-002u3<br>
3-4 perimeter layers minimum, 30-40% infill, 0.2mm layer height


| Name                        | Description                 |
|-----------------------------|-----------------------------|
| MkV-001                     | Base Platform Mount         |
| MkV-002u3                   | Camera Mount                |
| MkV-004                     | Outer Shell                 |
| MkV-005 &<br>Mirrored-MkV-005 | Camera Protection for L515  |
| MkV-006 &<br>Mirrored-MkV-006 | Camera Protection for D435i |

## Fasteners

| Fastener Name | McMaster-Carr PID | Qty |
|---------------|-------------------|-----|
| M3x8mm        | 91290A113         | 2   |
| M3x40mm       | 91290A136         | 4   |
| M4x16mm       | 91274A119         | 10  |
| M4x10mm       | 91290A144         | 2   |
| M4x18mm       | 91290A164         | 2   |
| M4 Nylock Nut | 90576A103         | 10  |


![Image](https://github.com/UMich-CURLY/minicheetah-sensorsuite/tree/master/img/P3.png)
<br>*Underside Fasteners View with transparent MkV-001*
<br>
<br>![Image](https://github.com/UMich-CURLY/minicheetah-sensorsuite/tree/master/img/P2.png)
<br>*Isometric Fasteners View with all electronics removed and all printed components transparent*
<br><br>
All 10 M4 nuts (red) are fastened with the 10 M4x16mm bolts (blue).<br>
The 2 M4x18mm (yellow) belong in the front fastening MkV-002u3 and MkV-001 to the Minicheetah<br>
The 2 M4x10mm (green) belong in the back fastening MkV-001 to the Minicheetah<br>
The 4 M3x40mm (purple) fasten the NVIDIA Jetson Xavier to MkV-001<br>
The 2 M3x8mm (orange) fasten either of the camera options to MkV-002u3
<br><br>
Camera Protection pieces may be glued to the MkV-004 shell, or alternatively, M4 bolts and nuts may be used for temporary fastening.


##### For any issues with printing, assembling, or part sourcing, contact yujustin@umich.edu or tzuyuan@umich.edu
