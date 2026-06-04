<h1>1. Network Architecture (FTTX Design)</h1>
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
