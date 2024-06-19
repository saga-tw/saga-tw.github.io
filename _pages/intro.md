---
layout: archive
title: 
permalink: /intro/
author_profile: true
---
<span style="color:#be887b;font-weight:700;font-size:38px"> Abstract </span>
<p>With the increasing sophistication of Advanced Persistent Threats (APTs), the demand for robust detection and mitigation methods has escalated. Program execution leaves traces recorded in the system audit log that can be used to detect malicious activity. However, collecting and analyzing large volumes of audit logs over extended periods poses significant challenges. In addition, the lack of sufficient labeling in the audit log makes them difficult to use. This paper tackles the challenge of generating comprehensively labeled synthetic audit logs that mimic real-world system audit logs. Specifically, the synthetic audit log can be configurable to any arbitrary time interval to embed stealthy APT attacks. Such logs can serve as benchmark datasets for training machine learning models and evaluating the performance of various methods for APT detection. We propose <b>SAGA (Synthetic Audit log Generation for APT campaigns)</b>, a method to generate configurable labeled synthetic audit logs that embed malicious actions aligned with the MITRE ATT&CK framework. Synthetic audit log contains both benign and malicious audit logs. Benign audit logs are collected from normal user and system operations, whereas malicious audit logs are created from previously generated templates. Each malicious log follows a lifecycle, with each stage comprises several MITRE ATT&CK techniques. To demonstrate the usefulness of synthetic audit logs, we ran established baselines of event-based technique hunting or APT campaign detection using various synthetic audit logs with real-world and randomly generated APT campaigns of different durations. We anticipate expanding the content and scale of SAGA for further service.</p>

<div align="center">
    <img src="/images/intro.png" width="100%" height="80%">
</div>
