# CURLY's Minicheetah Sensor Suite Mk V
<img src="https://raw.githubusercontent.com/UMich-CURLY/minicheetah-sensorsuite/master/img/P1.png?token=ADDGZNIAN63E5D3ORJ236RC747ZTW" height="80%" width="80%">
<img src="https://raw.githubusercontent.com/UMich-CURLY/minicheetah-sensorsuite/master/img/P4.JPG?token=ADDGZNMVGQCLZ2JP5VHVDY27475RI" height="35%" width="35%"><img src="https://raw.githubusercontent.com/UMich-CURLY/minicheetah-sensorsuite/master/img/P5.JPG?token=ADDGZNPSPGTFZSEW6BPNZSS7475SK" height="35%" width="35%">

<br>3D-Printed sensor suite designed to augment Minicheetah autonomous capabilities. 
<br>

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
<br><br>

## Overview
This sensor suite was designed to house and protect an NVIDIA Jetson Xavier as well as a vision system. Our suite will accept either the Intel D435i depth camera or L515 LiDAR. Additional components such as network switches may be mounted at the rear via tape. 2 cargo straps are run through the sensor suite frame to secure a [Krisdonia portable battery](https://www.amazon.com/Krisdonia-Portable-TSA-Approved-25000mAh-Smartphone/dp/B074PQBRJV/ref=pd_bxgy_3/145-9030221-8924019?_encoding=UTF8&pd_rd_i=B074PQBRJV&pd_rd_r=2784de7f-2ee9-4e7e-a4bc-77ea9417cde1&pd_rd_w=JQHPX&pd_rd_wg=A5wtw&pf_rd_p=ce6c479b-ef53-49a6-845b-bbbf35c28dd3&pf_rd_r=4B2XVXJKFZKAB6JSTR0R&psc=1&refRID=4B2XVXJKFZKAB6JSTR0R) to the underside of the Minicheetah.
<br><br>
## Printed Components
STL files found under /stl <br>
Support material is unnecessary for any part besides MkV-002u3<br>
3-4 perimeter layers minimum, 30-40% infill, 0.2mm layer height<br>
Any 3D printer filament such as PLA, PETG, ABS will work


| Name                        | Description                 |
|-----------------------------|-----------------------------|
| MkV-001                     | Base Platform Mount         |
| MkV-002u3                   | Camera Mount                |
| MkV-004                     | Outer Shell                 |
| MkV-005 &<br>Mirrored-MkV-005 | Camera Protection for L515  |
| MkV-006 &<br>Mirrored-MkV-006 | Camera Protection for D435i |
| MkV-007 | Underbelly Battery Mount (Lower) |
| MkV-008 | Underbelly Battery Mount (Upper) |

## Fasteners

| Fastener Name | McMaster-Carr PID | Qty |
|---------------|-------------------|-----|
| M3x8mm        | 91290A113         | 2   |
| M3x40mm       | 91290A136         | 4   |
| M4x16mm       | 91274A119         | 10  |
| M4x10mm       | 91290A144         | 2   |
| M4x18mm       | 91290A164         | 2   |
| M4 Nylock Nut | 90576A103         | 10  |


<img src="https://raw.githubusercontent.com/UMich-CURLY/minicheetah-sensorsuite/master/img/P3.png?token=ADDGZNI2TYRFAAY3C4Y7UZC747ZWS" height="50%" width="50%">
<br>*Underside Fasteners View with transparent MkV-001*
<br>
<br><img src="https://raw.githubusercontent.com/UMich-CURLY/minicheetah-sensorsuite/master/img/P2.png?token=ADDGZNLWH62R7IDJ5R6B27C747ZVI" height="50%" width="50%">
<br>*Isometric Fasteners View with all electronics removed and all printed components transparent*
<br><br>
All 10 M4 nuts (red) are fastened with the 10 M4x16mm bolts (blue).<br>
The 2 M4x18mm (yellow) belong in the front fastening MkV-002u3 and MkV-001 to the Minicheetah<br>
The 2 M4x10mm (green) belong in the back fastening MkV-001 to the Minicheetah<br>
The 4 M3x40mm (purple) fasten the NVIDIA Jetson Xavier to MkV-001<br>
The 2 M3x8mm (orange) fasten either of the camera options to MkV-002u3
<br><br>
Camera Protection pieces may be glued to the MkV-004 shell, or alternatively, M4 bolts and nuts may be used for temporary fastening.
<br><br>
Battery mount is fastened to the Minicheetah with 2 cargo straps. MkV-007 & 008 battery case is fastened together with an additional 6 M4x12mm bolts and M4 nuts. 


##### For any issues with printing, assembling, or part sourcing, contact yujustin@umich.edu or tzuyuan@umich.edu
