<h1 align="center">🛡️ SOC Cybersecurity & Threat Detection Portfolio</h1>

<p align="center">
Hands-on Security Operations Center (SOC) simulation for detection engineering, threat hunting, and incident response.
</p>

<hr>

<h2>Overview</h2>

<p>
This project is a practical SOC (Security Operations Center) lab that simulates real-world cybersecurity monitoring, detection engineering, incident response, and threat hunting workflows.
</p>

<p>
It uses <b>DVWA (Damn Vulnerable Web Application)</b>, <b>Splunk SIEM</b>, and attack simulation tools such as <b>Hydra</b> to generate and analyze malicious activity in a controlled environment.
</p>

<hr>

<h2> System Architecture</h2>

<pre>
SOC LAB ENVIRONMENT
│
├── Attack Simulation Layer
│   ├── Hydra (Brute Force Attacks)
│   ├── Manual HTTP Requests
│   └── Reconnaissance Simulation
│
├── Target Environment
│   ├── DVWA (Vulnerable Web App)
│   ├── Apache Web Server Logs
│
├── Log Collection Layer
│   ├── Authentication Logs
│   ├── Web Access Logs
│
├── SIEM Platform
│   ├── Splunk Dashboards
│   ├── Event Indexing & Correlation
│   └── Real-Time Alerting Engine
│
└── Security Analytics Layer
    ├── Detection Rules
    ├── Threat Hunting Queries
    └── MITRE ATT&CK Mapping
</pre>

<hr>

<h2> Attack Simulation</h2>

<ul>
  <li><b>Brute Force Attack:</b> Hydra used against DVWA login portal to simulate credential attacks</li>
  <li><b>Web Enumeration:</b> Reconnaissance across multiple DVWA endpoints</li>
  <li><b>Suspicious Traffic:</b> Repeated login attempts to test authentication monitoring</li>
</ul>

<hr>

<h2>MITRE ATT&CK Mapping</h2>

<ul>
  <li><b>T1110 – Brute Force:</b> Repeated login attempts via Hydra</li>
  <li><b>T1595 – Active Scanning:</b> Web application endpoint discovery</li>
  <li><b>Framework Alignment:</b> All detections mapped to adversary behavior techniques</li>
</ul>

<hr>

<h2>Detection Engineering</h2>

<ul>
  <li>Brute force detection using threshold-based Splunk correlation searches</li>
  <li>Web enumeration detection via unique URL path analysis</li>
  <li>Anomaly detection using baseline behavior deviation</li>
  <li>Alert tuning to reduce false positives and improve accuracy</li>
</ul>

<hr>

<h2>Incident Response Case Studies</h2>

<ul>
  <li>Reconstructed attack timelines from DVWA and Apache logs</li>
  <li>Identified Indicators of Compromise (IOCs)</li>
  <li>Mapped attacker behavior to MITRE ATT&CK framework</li>
  <li>Proposed remediation: rate limiting & authentication hardening</li>
</ul>

<hr>

<h2>Threat Hunting Exercises</h2>

<ul>
  <li>Hypothesis-driven log analysis using Splunk</li>
  <li>Investigation of unusual login spikes</li>
  <li>Detection of reconnaissance activity missed by alerts</li>
  <li>Validation through iterative log investigation</li>
</ul>

<hr>

<h2>Tools Used</h2>

<ul>
  <li>DVWA (Damn Vulnerable Web Application)</li>
  <li>Hydra Attack Tool</li>
  <li>Kali Linux</li>
  <li>Apache Web Server Logs</li>
  <li>Splunk SIEM</li>
</ul>

<hr>

<h2>Key Skills Demonstrated</h2>

<ul>
  <li>Security Information & Event Management (SIEM)</li>
  <li>Detection Engineering & Rule Development</li>
  <li>Threat Hunting & Behavioral Analysis</li>
  <li>Incident Response & Log Investigation</li>
  <li>MITRE ATT&CK Framework Mapping</li>
</ul>

<hr>

<h2> Outcome</h2>

<p>
This project demonstrates practical SOC analyst capabilities including detection rule engineering, security monitoring, attack simulation, and threat intelligence mapping aligned with industry standards.
</p>

<hr>

<p align="center">

</p>
