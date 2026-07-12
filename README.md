# Qotom_Q20342G9_S20_C3808
Qotom Q20300S9 is a fanless Mini PC with an Intel Atom Denverton processor. It features 4 x 10G SFP+ and 5 x 2.5 Gigabit LAN ports, supports up to 64GB DDR4 RAM, and offers storage options with 2 x M.2, 2 x SATA 3.0, and 1 x Mini SAS. <br>
https://www.qotom.com/products/show/Mini-PC-Q20300S9-S20-Series
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/5cb03f32-b49c-4925-8c39-ee37a1644eae" />
<img width="869" height="545" alt="image" src="https://github.com/user-attachments/assets/2c2dcbdf-6a54-46c5-abec-f31c5fdec325" />


<title>RAM Compatibility Test Records</title>
<style>
    table {
        width: 100%;
        border-collapse: collapse;
        font-family: Arial, sans-serif;
        margin: 20px 0;
        font-size: 14px;
    }
    th, td {
        border: 1px solid #dddddd;
        text-align: left;
        padding: 10px;
    }
    th {
        background-color: #f2f2f2;
        font-weight: bold;
    }
    .meta-row {
        background-color: #f9f9f9;
        font-weight: bold;
    }
    .spacer-row {
        background-color: #ffffff;
        height: 15px;
    }
</style>
</head>
<body>

<table>
    <thead>
        <tr class="meta-row">
            <td>Test Content</td>
            <td colspan="7">Time taken to power up the Q203xxG9 series</td>
        </tr>
        <tr class="meta-row">
            <td>Test Platform</td>
            <td colspan="7">C3758R</td>
        </tr>
        <tr>
            <th>Vendor</th>
            <th>Module</th>
            <th>Chip</th>
            <th>Size</th>
            <th>Speed</th>
            <th>Socket</th>
            <th>First Time</th>
            <th>Secondary</th>
        </tr>
    </thead>
    <tbody>
        <!-- Micron Block -->
        <tr>
            <td rowspan="3">Micron</td>
            <td rowspan="3">MTA8ATF51264HZ-2G1A1<br>4GB 1RX8 PC4-2133P-SA0-10</td>
            <td rowspan="3">Micron</td>
            <td>4G</td>
            <td>2133</td>
            <td>sodimm1</td>
            <td>45s</td>
            <td>15s</td>
        </tr>
        <tr>
            <td>4G</td>
            <td>2133</td>
            <td>sodimm2</td>
            <td>47s</td>
            <td>15s</td>
        </tr>
        <tr>
            <td>8G (dual 4G)</td>
            <td>2133</td>
            <td>dual</td>
            <td>1m 19s</td>
            <td>19s</td>
        </tr>
        
        <tr class="spacer-row"><td colspan="8"></td></tr>

        <!-- Kingston Block -->
        <tr>
            <td rowspan="3">Kingston</td>
            <td rowspan="3">KVR32S22S8/16-SP</td>
            <td rowspan="3">Micron</td>
            <td>16G</td>
            <td>3200</td>
            <td>sodimm1</td>
            <td>55s</td>
            <td>25s</td>
        </tr>
        <tr>
            <td>16G</td>
            <td>3200</td>
            <td>sodimm2</td>
            <td>55s</td>
            <td>25s</td>
        </tr>
        <tr>
            <td>32G (dual 16G)</td>
            <td>3200</td>
            <td>dual</td>
            <td>1m 35s</td>
            <td>38s</td>
        </tr>

        <tr class="spacer-row"><td colspan="8"></td></tr>

        <!-- TEAMGROUP Block -->
        <tr>
            <td rowspan="3">TEAMGROUP</td>
            <td rowspan="3"><em>N/A</em></td>
            <td rowspan="2">Micron</td>
            <td>32G</td>
            <td>3200</td>
            <td>sodimm1</td>
            <td>1m 35s</td>
            <td>35s</td>
        </tr>
        <tr>
            <td>32G</td>
            <td>3200</td>
            <td>sodimm2</td>
            <td>1m 35s</td>
            <td>35s</td>
        </tr>
        <tr>
            <td>TEAMGROUP</td>
            <td>64G (dual 32G)</td>
            <td>3200</td>
            <td>dual</td>
            <td>No signal</td>
            <td>No signal</td>
        </tr>

        <tr class="spacer-row"><td colspan="8"></td></tr>

        <!-- Gowe Block -->
        <tr>
            <td rowspan="3">Gowe</td>
            <td rowspan="3">32G 2Rx8<br>PC4-3200AA-22-22-52</td>
            <td rowspan="3">Samsung</td>
            <td>32G</td>
            <td>3200</td>
            <td>sodimm1</td>
            <td>1m 35s</td>
            <td>35s</td>
        </tr>
        <tr>
            <td>32G</td>
            <td>3200</td>
            <td>sodimm2</td>
            <td>1m 35s</td>
            <td>35s</td>
        </tr>
        <tr>
            <td>64G (dual 32G)</td>
            <td>3200</td>
            <td>dual</td>
            <td>3m</td>
            <td>1m</td>
        </tr>

        <tr class="spacer-row"><td colspan="8"></td></tr>

        <!-- Lexar Block -->
        <tr>
            <td rowspan="3">Lexar</td>
            <td rowspan="3">32G 2Rx8 PC4-3200AA-SF4<br>LD4S32G32C22ST-HGN</td>
            <td rowspan="3">Sk hynix</td>
            <td>32G</td>
            <td>3200</td>
            <td>sodimm1</td>
            <td>1m 40s</td>
            <td>35s</td>
        </tr>
        <tr>
            <td>32G</td>
            <td>3200</td>
            <td>sodimm2</td>
            <td>1m 40s</td>
            <td>35s</td>
        </tr>
        <tr>
            <td>64G (dual 32G)</td>
            <td>3200</td>
            <td>dual</td>
            <td><em>N/A</em></td>
            <td><em>N/A</em></td>
        </tr>
    </tbody>
</table>




<img width="2542" height="272" alt="1736451587861" src="https://github.com/user-attachments/assets/93e9a0ff-95ff-4a21-b450-031e5ba39e20" />
https://forums.servethehome.com/index.php?threads/qotom-denverton-fanless-system-with-4-sfp.41331/page-32#post-452840
<img width="1506" height="653" alt="image" src="https://github.com/user-attachments/assets/d8d825bf-7342-458f-b5ca-9671dafc8432" />

