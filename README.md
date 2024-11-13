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
- momery Forensics Volatility Notes
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
      
- system investigation with PowerShell Notes
    - System Information and Metadata Collection
    - User Activity and Login Tracking
    - Network Information
    - Process and Service Monitoring
    - Inspecting Loaded Modules and DLLs
    - File System and Registry Analysis
    - Event Log Analysis
    - Browser and Internet Activity
    - Evidence Collection
    - Malware Detection and Analysis
    - File Integrity Verification
      
- registry Forensics with Regripper Notes
    - Startup and Persistence Plugins
    - User Activity
    - Networking Plugins
    - Malware Indicators
    - System Information Plugins
    - Registry Usage and Last Access
    - Browser History and Internet Activity
    -  File Access and Recent Documents
    -  Security and Logon Information
    -  USB and Device History
    -  Scheduled Tasks and Job Settings
    -  Miscellaneous Plugins
      
 - important registry Forensics aspects
    - SAM (Security Account Manager)
    - SYSTEM
    - NTUSER
    - USERCLASS
    - SECURITY
    - SOFTWARE
    - Browser Artifacts
      
- Prefetch Files
    - Program Execution Evidence: Indicates whether a specific application, possibly malware, was executed
    - Timeline and Frequency of Access: Provides timestamps to help in event reconstruction and understanding user or malware behavior
    - Resource and Dependency Analysis: Lists DLLs and files accessed by an application, useful for dependency tracking and spotting suspicious resources
    - Indicating Persistence and Malware Activity: Unusual executables in prefetch files or executables running from non-standard paths may indicate malware or persistence techniques.
      
 - Network Forensics with Wireshark
    - IP Filters
    - Port-Based Filters
    - Protocol-Specific Filters
    - Malicious Traffic Indicators
    - Analyzing Payloads and Content
    - searching for specific file
    - Detecting Anomalous Connections
    - Kerberos Traffic
    - LDAP Traffic (Active Directory)    

- Splunk Filters
    - List All Indexes
    - Identify Available Sourcetypes
    - Explore the Fields in Your Data
    - List Data Sources by Host
    - Network Connections
    - Identifying Brute Force Attacks
    - Detecting File Uploads
    - LOGON activity
    - Detect Changes to High-Value Accounts
    - Privilege Escalation Detection
    - Monitoring Malicious File Execution
    - Scheduled Task
    - Persistence Registry Detection
    - PowerShell Detection
    - Lateral Movement & Pivot Detection
    - Golden Ticket Attack Detection
    - Kerberoasting Attack Detection
       
