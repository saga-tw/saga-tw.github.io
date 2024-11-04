---
permalink: /
title: 
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---
<p style= "margin-bottom: 0 !important;">
  <strong style="color: #2F4F4F; font-family: 'Work Sans'; font-weight: bold;font-size:40px">SAGA: </strong>
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-weight: bold;font-size:40px">S</span>
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-size:36px; margin-left: -4px;">ynthetic </span>
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-weight: bold;font-size:40px">A</span>
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-size:36px; margin-left: -4px;">udit Log </span> 
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-weight: bold;font-size:40px">G</span>
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-size:36px; margin-left: -4px;">ener</span>
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-weight: bold;font-size:40px; margin-left: -4px;">A</span>
  <span style="color: #2F4F4F; font-family: 'Work Sans'; font-size:36px; margin-left: -4px;">tion for APT Campaigns </span>
</p>

<h1 style= "color:#2F4F4F; font-family: 'Work Sans'; margin-top: 1em !important;"> News! </h1>
<ul>
  <li> <span style="border-width: 3px ; width: 150px; height: 30px ; padding: 1px 5px 2px 5px; text-align: center; background-color:#A61C3C;border-radius: 4px;"><font style="font-weight:bold" color="white" size="1">Jun 2024</font></span><span style="font-family: 'Work Sans';"> Update SAGA dataset - v2.0!</span></li>
  <li> <span style="border-width: 3px ; width: 150px; height: 30px ; padding: 1px 5px 2px 5px; text-align: center; background-color:#A61C3C;border-radius: 4px;"><font style="font-weight:bold" color="white" size="1">Feb 2024</font></span><span style="font-family: 'Work Sans';"> Update SAGA dataset - v1.0!</span></li>  
</ul>

<h1 style= "color:#2F4F4F; font-family: 'Work Sans'; margin-top: 1em !important;">What is SAGA?</h1>
<p style="font-family: 'Work Sans'; margin-bottom: 0 !important;">SAGA can generate configured synthetic audit logs for any arbitrary time interval to embed stealthy APT attacks. Here, we are releasing serveral large-scale set of synthetic audit logs designed to simulate APT campaigns.</p>
<p style="margin-top: 1em !important; margin-bottom: 0 !important;"><span style="color: #006400; font-family: 'Work Sans'; font-size:24px; font-weight: bold;">SAGA has several features:</span></p>
<!-- <h2 style= "color:#2F4F4F; font-family: 'Work Sans';">SAGA has several features:</h2> -->
<table>
  <tr>
    <td>
      <ul style="margin: 0; padding: 0; list-style-position: inside;">
        <li style="font-family: 'Work Sans';">Realism</li>
        <li style="font-family: 'Work Sans';">Scenario coverage</li>
        <li style="font-family: 'Work Sans';">Detailed labeling</li>
        <li style="font-family: 'Work Sans';">Higher-Level representation</li>
        <li style="font-family: 'Work Sans';">Flexibility any duration </li>
        <li style="font-family: 'Work Sans';">Diversity</li>
      </ul>
    </td>
    <td>
      <ul style="margin: 0; padding: 0; list-style-position: inside;">
        <li style="font-family: 'Work Sans';">Host-based intrusion detection</li>
        <li style="font-family: 'Work Sans';">TTPs hunting</li>
        <li style="font-family: 'Work Sans';">Campaign attribution</li>
        <li style="font-family: 'Work Sans';">38 Campaigns (8 known, 20 random, 10 composite)</li>
        <li style="font-family: 'Work Sans';">80 Techniques defined in MITRE ATT&CK</li>
        <li style="font-family: 'Work Sans';">169 Attack patterns</li>
      </ul>
    </td>
  </tr>
</table>

<h1 style= "color:#2F4F4F; font-family: 'Work Sans'; margin-top: 1em !important;">Example</h1>
<p style="font-family: 'Work Sans'; margin-bottom: 0.5em !important;">SAGA demonstrates an attack scenario from APT28 along with <a href="https://cloud.google.com/security/resources/insights/targeted-attack-lifecycle" style="color: #FF8C00;">Mandiant adversary lifecycle</a>.</p>

<p style="font-family: 'Work Sans'; margin-bottom: 0.5em !important;">In the initial stages of the attack, phishing emails containing malicious attachments are sent to the victim to download the attachment IOC_09_11.rar. This activity is designated as the Technique <a href="https://attack.mitre.org/techniques/T1566/001/" style="color: #FF8C00;">T1566.001 Spearphishing Attachment</a> of the attack lifecycle stage <b style="color: #006400">Initial Compromise</b>.</p>

<p style="font-family: 'Work Sans'; margin-bottom: 0.5em !important;">This malicious attachment exploits a vulnerability in WinRAR versions below 6.23 (as mentioned in <a href="https://nvd.nist.gov/vuln/detail/cve-2023-38831" style="color: #FF8C00;">CVE-2023-38831</a>). When the victim clicks on the IOC_09_11.rar file, it triggers subsequent malicious activities designated as <a href="https://attack.mitre.org/techniques/T1204/002/" style="color: #FF8C00;">T1204.002 User Execution: Malicious File</a> of the attack lifecycle <b style="color: #006400">Establish Foothold</b>.</p>

<div align="center">
    <img src="/images/example_v2.png" width="90%" height="90%">
</div>
