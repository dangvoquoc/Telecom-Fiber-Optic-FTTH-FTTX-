<h2>1. Network Architecture (FTTX Design)</h1>
Most modern fiber networks use a hierarchical design:
<h2>Core Network (Backbone)</h2>
<li>High-capacity routers and optical transport systems</li>
<li>Connect cities, data centers, and ISPs</li>
<li>Uses DWDM (Dense Wavelength Division Multiplexing) for huge bandwidth</li>
<h2>Metro Network</h2>
<li>Connects local exchange offices within a city</li>
<li>Aggregates traffic from multiple access networks</li>
<h2>Access Network (Last Mile)</h2>
<li>The most important part for users</li>
<ul>
<li>
  Typically FTTH (Fiber To The Home) or variants like
  <ul> 
    <li>FTTH (home)</li>
    <li>FTTB (building) </li>
    <li>FTTC (curb) </li>
  </ul>
</li>
</ul>
<h2>2. Common Fiber Access Technology: PON or GPON</h2>
<p>Most telecom fiber networks use PON (Passive Optical Network)</p>
<h3>How it works</h3>
<li>One OLT (Optical Line Terminal) at the ISP office</li>
<li>Fiber goes to passive splitter</li>
<li>Then distributed to multiple homes (ONT/ONU devices)</li>
<h3>Split ratio examples</h3>
<li>1:32 or 1:64 or 1:128 users per fiber port</li>
<h3>Advantages</h3>
<li>No active equipment in the field (cheaper maintenance)</li>
<li>Efficient bandwidth sharing</li>
<li>Scalable</li>
<h2>3. Key Design Components</h2>
<h3>a) Optical Line Terminal (OLT)</h3>
<li>Located at ISP central office</li>
<li>Controls traffic to all users</li>
<li>>Aggregates internet backbone traffic</li>
<h3>b) Optical Distribution Network (ODN)</h3>
<li>Passive fiber cables, splitters, connectors</li>
<li>The "physical fiber map" in streets and poles</li>
<h3>c) Optical Network Terminal (ONT)</h3>
<li>Installed at customer home</li>
<li>Converts optical signal --> Ethernet/Wi-Fi</li>
<h2> Design Considerations</h2>
<h3>Bandwidth Planning</h3>
<li>Estimate users per area</li>
<li>Define peak traffic (congestion control)</li>
<h3>Distance Limits</h3>
<li>GPON typical reach: ~20 km</li>
<li>Signal loss must be calculated (optical budget)</li>
<h3>Split Ratio Design</h3>
<li>Higher split = cheaper, but less speed per user</li>
<li>Lower split = better perfomance, higher cost</li>
<h3>Redundancy</h3>
<li>Ring or dual-homing in backbone</li>
<li>Backup fiber routers for outages</li>
<h3>Optical Power Budget</h3>
<p>Ensures signal strength is sufficent:</p>
<li>Fiber loss (dB/km)</li>
<li>Splitter loss</li>
<li>Connector/Splice loss</li>
<h2>5. Typicalll FTTH Layout</h2>
<img width="371" height="327" alt="image" src="https://github.com/user-attachments/assets/a5001878-c113-4b52-80d6-f56ec1717ad1" />
<h2>5. Modern Enhancements</h2>
<li><b>XG-PON / XGS-PON --> 10 Gbps fiber access</b></li>
<li><b>NG-PON2</b> --> wavelength-based upgrades</li>
<li><b>SDN(Software Defined Networking)</b> for control</li>
<li>Integration with <b>5G backhaul networks</b></li>
<h2>6. Summary</h2>
<p>Desigining fiber internet =</p>
<li>Build core + metro + access layers</li>
<li>Use PON (like GPON) for last-mile delivery</li>
<li>Carefully plan splits, distance, and power budget</li>
<li>Ensure scalability for future upgrades</li>
<h2>Common ITU-T fiber standards in GPON</h2>
<ul>
  <li>ITU-T G.652 (Standard SMF)</li>
  <ul>
      <li>Most widely used fiber in GPON networks</li>
      <li>Good performance for general telecom backbone and access networks</li>
  </ul>
  <li>ITU0T G.657 (Bend-insensitive SMF)</li>
  <ul>
      <li>Designed for FTTH (Fiber to the Home)</li>
      <li>Can be bent more without high signal loss</li>
      <li>Very common in indoor installations and last-mile connections</li>
  </ul>
</ul>
<h2>Why GPON uses single-mode fiber</h2>
<li>Works efficiently up to 20km or more</li>
<li>Supports high downstream/upstream speeds (2.5Gbps down/ 1.25 Gbps up in classic GPON)</li>
<li>Very low atennuation and dispersion</li>
<li>Ideal for passive splitters in the network</li>
