# Investigator-Hand
## Introduction to the Windows Registry - Event Codes Maps for forensic investigations 

- Events Codes: provides a detailed and visually structured map of Windows Event Codes, designed to assist incident responders, SOC analysts, and cybersecurity professionals in monitoring, detecting, and investigating security incidents. The map visualizes various event codes, their categories, and their relationships, offering a clear and intuitive way to understand and track key system activities, such as logon attempts, policy changes, and system audits-Focus on Incident Response: Tailored to professionals preparing for certifications like eCIR, this map can be a useful reference during incident detection and investigation.

The map organizes event codes into distinct categories, such as 
- Network Activity
- initial access
- Privilege Escalation Detection
- Process Creation
- Persistence Detection - schedule task
- Persistence Registry    Detection
- PowerShell Detection
- Buffer Overflow Detection
- lateral movement Detection
- DCSync Activity Detection
- Golden Ticket Detection
- Pass-the-Hash (PtH) Attack Detection
- Pass-the-Ticket (PtT) Attack Detection


 - Windows Registry: The Windows Registry is a hierarchical database that stores low-level settings for the operating system and applications. It is a critical component in managing system configurations, user preferences, and operational details such as files, folders, user profiles, and network settings. The Registry is divided into multiple root keys that contain numerous subkeys, values, and data used by Windows to manage both hardware and software , This Registry map provides a visual and organized representation of important registry locations, categorized based on their relevance to files, folders, users, system, and network configurations. By understanding these key registry paths, administrators and cybersecurity professionals can efficiently monitor, investigate, and secure critical aspects of the system.

This map is divided into the following categories:

- Files and Folders: Tracks recently opened files, user-specific folders, and mounted devices.
- System Information: Stores key system details such as Windows version, computer name, and timezone.
- Network Information: Identifies network interfaces, physical cards, and connection history.
- User Information: Manages user profiles, last logon details, and user-specific settings.

Each section in the map highlights critical registry keys that can be used for system analysis, troubleshooting, and forensic investigations, helping to maintain control over system behavior and security.

## introduction to Digital Forensics and Incident Response Notes 

- This part contains detailed notes and command references for tools and techniques used in digital forensics and incident response. The notes focus on memory analysis with Volatility & network forensics with wireshark & system investigation with PowerShell & registry Forensics with regripper & important registry Forensics aspects shuch as NTUSER - USERCLASS - Browser Artifacts , It includes essential tools and guides for analyzing registry files, network traffic, and prefetch files, and memory analysis with a focus on threat indicators and patterns that can assist in tracing attacker actions and understanding system activities. Each section provides specific filters and paths useful in various forensic contexts. covering various areas essential for incident responders and forensic analysts.

### Contents
- Volatility Notes
    - Process Analysis
    - DLL & Handle Analysis
    - File & Registry Analysis
    - Network Analysis
    - User & Session Information
    - Memory Dumps
    - Module & Driver Analysis
    - Malware & Anomaly Detection
    - Miscellaneous
    - Memory Dumping & Extraction
    - Memory Artifacts
    - Event Log Extraction
    - Lateral Movement Detection
    - Registry-based Persistence Detection
    - Timeline Creation

  
