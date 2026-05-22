<h1 align="center">Purple Team Security Lab</h1>
<h3 align="center">(Kali Linux | Metasploitable 2 | pfSense)</h3>

<p align="center">
  Hands-on <strong>Purple Team</strong> labs demonstrating the transition from vulnerability identification to enterprise-grade system hardening. These modules focus on the technical bridge between offensive exploitation and defensive remediation.
</p>

<hr>

<h2>🧪 Labs & Technical Validations</h2>

<table style="width:100%; border-collapse: collapse; margin-top: 10px; margin-bottom: 15px; font-size: 0.95em;">
  <thead>
    <tr style="background-color: #f6f8fa; text-align: left;">
      <th style="padding: 10px; border: 1px solid #d0d7de;">Project Module</th>
      <th style="padding: 10px; border: 1px solid #d0d7de;">Attack Vector</th>
      <th style="padding: 10px; border: 1px solid #d0d7de;">Security Controls & Remediation</th>
      <th style="padding: 10px; border: 1px solid #d0d7de;">Technical Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><strong>Legacy Service Remediation</strong></td>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><strong>vsFTPd Backdoor Exploitation:</strong> Leveraged Nmap and manual payloads to identify and exploit unpatched FTP services.</td>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><strong>System Hardening:</strong> Implemented service-layer remediation, port filtering, and configuration standardization.</td>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><a href="https://github.com/GaryCollinsAI-Sec/Legacy-Service-Remediation-vsFTPd-Exploitation-System-Hardening">View Lab</a></td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><strong>Credential Security & Auditing</strong></td>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><strong>Password Cracking & Audit:</strong> Extracted weak password hashes, executed brute-force attacks via John the Ripper, and utilized compromised credentials for unauthorized system access.</td>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><strong>Security Hardening:</strong> Enforced strong PAM (Pluggable Authentication Modules) password complexities, instituted account lockout policies, disabled root SSH login, and configured key-based authentication.</td>
      <td style="padding: 10px; border: 1px solid #d0d7de;"><a href="https://github.com/GaryCollinsAI-Sec/Purple-Team-Password-Cracking-Audit-Lab">View Lab</a></td>
    </tr>
  </tbody>
</table>

<hr>

<h2>🎯 Project Objectives</h2>
<p>
  This repository serves as a technical demonstration of the <strong>Remediation Lifecycle</strong>. Unlike standard "Capture the Flag" (CTF) exercises, these labs focus on the documentation and verification of security controls following a successful compromise.
</p>

<ul>
  <li><strong>Attack Surface Analysis:</strong> Identifying insecure open ports and unpatched legacy services within a segmented network environment.</li>
  <li><strong>Exploitation & PoC:</strong> Utilizing Kali Linux utilities to prove the risk of identified vulnerabilities through manual Proof-of-Concept (PoC) exploitation.</li>
  <li><strong>Remediation Engineering:</strong> Applying "Gold Standard" hardening techniques, including service-layer patching, disabling insecure daemons, and firewall rule enforcement via <strong>pfSense</strong>.</li>
  <li><strong>Defensive Validation:</strong> Documenting the final hardened state to ensure that previously successful exploit vectors are fully mitigated and the attack surface is reduced.</li>
</ul>

<hr>

<h2>🛠️ Tech Stack & Lab Environment</h2>
<ul>
  <li><strong>Offensive Suite:</strong> Kali Linux (Nmap, Netcat, John the Ripper, Hydra, Manual Exploitation Utilities)</li>
  <li><strong>Target Environment:</strong> Metasploitable 2 (Intentionally vulnerable Linux target)</li>
  <li><strong>Network Infrastructure:</strong> pfSense (VLAN Segmentation, Default-Deny Firewall Rules, Network Isolation)</li>
  <li><strong>Methodology:</strong> NIST-aligned Vulnerability Management and Purple Teaming</li>
</ul>

<hr>

<h2>🔗 Project Links</h2>
<p>
  <a href="https://github.com/GaryCollinsAI-Sec">
    <strong>Return to Main Portfolio</strong>
  </a>
</p>
