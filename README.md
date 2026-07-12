# Qotom_Q20342G9_S20_C3808
Qotom Q20300S9 is a fanless Mini PC with an Intel Atom Denverton processor. It features 4 x 10G SFP+ and 5 x 2.5 Gigabit LAN ports, supports up to 64GB DDR4 RAM, and offers storage options with 2 x M.2, 2 x SATA 3.0, and 1 x Mini SAS. <br>
https://www.qotom.com/products/show/Mini-PC-Q20300S9-S20-Series
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/5cb03f32-b49c-4925-8c39-ee37a1644eae" />
<img width="869" height="545" alt="image" src="https://github.com/user-attachments/assets/2c2dcbdf-6a54-46c5-abec-f31c5fdec325" />

### RAM Compatibility Test Records of Q203xxG9 Series

* **Test Content:** Time taken to power up the Q203xxG9 series
* **Test Platform:** C3758R

| Vendor | Module | Chip | Size | Speed (MHz) | Socket | First Time | Secondary Time |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Micron** | MTA8ATF51264HZ-2G1A1 <br> 4GB 1RX8 PC4-2133P-SA0-10 | Micron | 4G | 2133 | sodimm1 | 45s | 15s |
| **Micron** | MTA8ATF51264HZ-2G1A1 <br> 4GB 1RX8 PC4-2133P-SA0-10 | Micron | 4G | 2133 | sodimm2 | 47s | 15s |
| **Micron** | MTA8ATF51264HZ-2G1A1 <br> 4GB 1RX8 PC4-2133P-SA0-10 | Micron | 8G (dual 4G) | 2133 | dual | 1m 19s | 19s |
| | | | | | | | |
| **Crucial/Micron** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840) | ECC 16G MTA18ASF2G72HZ-2G6E1 <br> PC4-21300 | Micron | 16G | 2666 | sodimm1 & 2| TBC | TBC |
| **Crucial/Micron** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840) | MTA8ATF1G64HZ-3G2J1 <br> 8GB PC4-3200 | Micron | 8G | 3200 | sodimm1 & 2 | TBC | TBC |
| | | | | | | | |
| **Crucial/Micron** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840) | CT8G4SFS6266.M4FE <br> 8GB 1RX8 PC4-21300 | Micron | 8G | 2666 | sodimm1 | <b>No signal No Beep No Post</b> | <b>No signal No Beep No Post</b> |
| **Crucial/Micron** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840) | CT8G4SFS6266.M4FE <br> 8GB 1RX8 PC4-21300 | Micron | 8G | 2666 | sodimm2 | <b>No signal No Beep No Post</b> | <b>No signal No Beep No Post</b> |
| **Crucial/Micron** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840) | CT8G4SFS6266.M4FE <br> 8GB 1RX8 PC4-21300 | Micron | 16G (dual 8G) | 2666 | dual | <b>No signal No Beep No Post</b> | <b>No signal No Beep No Post</b> |
| | | | | | | | |
| **Kingston** | KVR32S22S8/16-SP | Micron | 16G | 3200 | sodimm1 | 55s | 25s |
| **Kingston** | KVR32S22S8/16-SP | Micron | 16G | 3200 | sodimm2 | 55s | 25s |
| **Kingston** | KVR32S22S8/16-SP | Micron | 32G (dual 16G) | 3200 | dual | 1m 35s | 38s |
| **Kingston** <br> [reference](https://https://forum.opnsense.org/index.php?topic=41589.0) | KF432S20IBK2/64 | Micron | 32G (dual 16G) | 3200 | dual | TBC | TBC | 
| | | | | | | | |
| **TEAMGROUP**| *N/A* | Micron | 32G | 3200 | sodimm1 | 1m 35s | 35s |
| **TEAMGROUP**| *N/A* | Micron | 32G | 3200 | sodimm2 | 1m 35s | 35s |
| **TEAMGROUP**| *N/A* | TEAMGROUP | 64G (dual 32G) | 3200 | dual | <b>No signal</b> | <b>No signal</b> |
| | | | | | | | |
| **Gowe** | 32G 2Rx8 <br> PC4-3200AA-22-22-52 | Samsung | 32G | 3200 | sodimm1 | 1m 35s | 35s |
| **Gowe** | 32G 2Rx8 <br> PC4-3200AA-22-22-52 | Samsung | 32G | 3200 | sodimm2 | 1m 35s | 35s |
| **Gowe** | 32G 2Rx8 <br> PC4-3200AA-22-22-52 | Samsung | 64G (dual 32G) | 3200 | dual | 3m | 1m |
| | | | | | | | |
| **Lexar** | 32G 2Rx8 PC4-3200AA-SF4 <br> LD4S32G32C22ST-HGN | Sk hynix | 32G | 3200 | sodimm1 | 1m 40s | 35s |
| **Lexar** | 32G 2Rx8 PC4-3200AA-SF4 <br> LD4S32G32C22ST-HGN | Sk hynix | 32G | 3200 | sodimm2 | 1m 40s | 35s |
| **Lexar** | 32G 2Rx8 PC4-3200AA-SF4 <br> LD4S32G32C22ST-HGN | Sk hynix | 64G (dual 32G) | 3200 | dual | 3m 10s | 1m |
| | | | | | | | |
| **Samsung** | 32G 2Rx8 PC4-3200AA-SE1-11 <br> M471A4G43AB1-CWE | Samsung | 32G | 3200 | sodimm1 | 1m 35s | 35s |
| **Samsung** | 32G 2Rx8 PC4-3200AA-SE1-11 <br> M471A4G43AB1-CWE | Samsung | 32G | 3200 | sodimm2 | 1m 35s | 35s |
| **Samsung** | 32G 2Rx8 PC4-3200AA-SE1-11 <br> M471A4G43AB1-CWE | Samsung | 64G (dual 32G) | 3200 | dual | 3m | 1m |
| | | | | | | | |
| **Sk hynix** | ECC 32G 2Rx8 PC4-2666V-TG1-11 <br> HMAA4GS7AJR8N-VK TO AC | Sk hynix | 32G | 2666 | sodimm1 | 1m 38s | 35s |
| **Sk hynix** | ECC 32G 2Rx8 PC4-2666V-TG1-11 <br> HMAA4GS7AJR8N-VK TO AC | Sk hynix | 32G | 2666 | sodimm2 | 1m 40s | 35s |
| **Sk hynix** | ECC 32G 2Rx8 PC4-2666V-TG1-11 <br> HMAA4GS7AJR8N-VK TO AC | Sk hynix | 64G (dual 32G) | 2666 | dual | 3m 09s | 1m |
| | | | | | | | |
| **Sk hynix** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840)| ECC 16G 2Rx8 PC4-21300 <br> HMA82GS7DJR8N-VK | Sk hynix | 16G | 2666 | sodimm1 | TBC | TBC | 
| **Sk hynix** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840)| ECC 16G 2Rx8 PC4-21300 <br> HMA82GS7DJR8N-VK | Sk hynix | 16G | 2666 | sodimm2 | TBC | TBC | 
| **Sk hynix** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840)| ECC 16G 2Rx8 PC4-21300 <br> HMA82GS7DJR8N-VK | Sk hynix | 32G (dual 16G) | 2666 | dual | TBC | TBC | 
| | | | | | | | |
| **Synology/Sk hynix** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840)| 4G PC4-19200 <br> D4SS12081SH24A-B | Sk hynix | 32G | 2400 | sodimm1 | TBC | TBC |
| **G.Skill/Ripjaws** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840)| 8G PC4-17000 <br> F4-2133C15D-16GRS | Sk hynix | 32G | 2133 | 16G (dual 8G) | TBC | TBC |
| **Timetec/Sk hynix** <br> [reference](https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840)| ECC 16G PC4-21300 Sodimm <br> D4ECSO-2666-16G | Sk hynix | 32G (dual 16G) | 2666 | dual | 3m 09s | 1m |



<img width="2542" height="272" alt="1736451587861" src="https://github.com/user-attachments/assets/93e9a0ff-95ff-4a21-b450-031e5ba39e20" />
https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840
<img width="1506" height="653" alt="image" src="https://github.com/user-attachments/assets/d8d825bf-7342-458f-b5ca-9671dafc8432" />

