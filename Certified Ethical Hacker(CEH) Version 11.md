# Certified Ethical Hacker(CEH) Version 11

![](img/00.00.jpg)

## Module 00 - Instructor
- ![](img/00.01.jpg)

## Module 01 - Introduction to Ethical Hacking

![](img/01.00.jpg)

### Module Objectives
- Understanding Elements of Information Security
- Understanding Information Security Attacks / Information Warfare
- Overview of Cyber Kill Chain Methodology, TTPs, and IoCs
- Overview of Hacking Concepts, Types, and Phases
- Understanding Ethical Hacking Concepts and Scope
- Overview of Information Security Concepts
- Overview of Information Security Acts and Laws

### Information Security Overview
- Information System
    - the protection or safeguarding of information and...
    - systems that use / store / transmit  infor
    - from unauthorized access, disclosure, alternation, and destruction
- Information
    - critical asset that organizations must secure

### Elements of Information Security
- ![](img/01.01.01.jpg)
    - Confidentiality
        - assurance that the information is accessible only to authorized
        - may occur due to improper data handling or a hacking attempt
    - Integrity
        - trustworthiness of data or resources in the prevention of improper and unauthorized changes—the assurance that information is sufficiently accurate for its purpose
    - Availability
        - assurance that the systems responsible for delivering, storing, and processing info are accessible when required by authorized users
        - Measures to maintain data availability include...
            - disk arrays for redundant systems and clustered machines, 
            - AV software to combat malware, and ... 
            - distributed denial-of-service (DDoS) prevention systems
    - Authenticity
        - characteristic of communication, documents, or any data 
            - that ensures the quality of being genuine or uncorrupted
        - user is genuine 
        - Controls include ...
            - biometrics, 
            - smart cards, 
            - digital certificates
                - ensure the authenticity of data, transactions, communications, and documents.
    - Non-Repudiation
        - guarantee that the sender of a message **cannot later deny** having sent msg
        - recipient **cannot deny having received** the msg
        - controls include...
            - digital signatures

### Motives, Goals, and Objectives of Information Security Attacks
- ![](img/01.02.01.jpg)
    - Motive
        - ![](img/01.02.02.jpg)
    - 
        - 
    - 
        - 

### Classification of Attacks
- Classification
    - ![](img/01.02.03.jpg)
        - passive - incercept/monitor network traffic / data flow
            - NOT TAMPER with data
            - like footprinting... sniffing... network traffic analysis
        - active attack
            - tampering with traffic
            - can be detected
            - ![](img/01.02.04.jpg)
        - close in attacks
            - only conducted IN CLOSE PROXIMITY
            - to gather / modify information
            - ![](img/01.03.01.jpg)
        - insider attack
            - performed by trusted personnel
            - violating rules to intentionally cause a threate
            - misuse organization's assets to affect CIA
            - examples
                - ![](img/01.03.02.jpg)
        - distribution attacks
            - tamper hardware / software ... AT SOURCE / WHEN IN TRANSIT
            - leverage bakcdoors to gain unauthorized access to access
            - ![](img/01.03.03.jpg)


### Information Warfare
- ![](img/01.04.01.jpg)
    - Definition
        - use of information / communication technologies for competitive advantages over an opponent
            - 
    - Categories of Information Warfare
        - C2 warfare
            - refers to the impact an attacker possesses over a compromised system
        - Intelligence-based warfare
            - **sensor based** technology to corrupt technological systems
        - Electronic Warfare
            - using RF/crypto techniques to degrade communication
        - Psychological warfare
            - to demoralize one's adversary
        - Hacker warfare
            - shutdown / data errors / info theft / services theft
        - Economic warfare
            - affecting the economy by blocking the flow of information
        - Cyberwarfare
            - utilizing Information Systems against individuals / groups
    - Offensive vs Defensive IW
        - ![](img/01.04.02.jpg)
            - 

### Cyber Kill Chain Concepts
- ![](img/01.05.01.jpg)
- ![](img/01.05.02.jpg)
    - component of intelligence-driven defense 
        - to help in ID'ing steps an adversaries conduct
        - to enhance intrusion detection/response
- ![](img/01.05.03.jpg)
    - Mnemoic
        - R
            - Recon
        - We
            - Weaponization
        - Declaring
            - Delivery
        - Emergencies
            - Exploitation
        - In
            - Installation
        - California
            - Command Control
        - Again
            - Action on object
    - Reconnaissance
        - collect as much info BEFORE an actual attack
            - across different network levels
                - to gain info such as network blocks, specific IP addresses, and employee details
        - ![](img/01.05.04.jpg)
    - Weaponization
        - analyzes data collection to identify vulnerabilites / techniques 
            - that can exploit / gain unauthorized access to target organization
        - ![](img/01.05.05.jpg)
            - 
    - Delivery
        - creating a weapon / transmit to victim
            - key stage that measures effectiveness of defensive strategies
        - ![](img/01.05.06.jpg)
    - Exploitation
        - triggering adversary's code to exploit a vulnerability
            - ![](img/01.05.07.jpg)
    - Installation
        - installs more software to maintain access to target network
            - ![](img/01.05.08.jpg)
    - Command and Control
        - establishing two-way communication 
            - ![](img/01.05.09.jpg)
    - Actions on Objectives
        - 
            - 
        - 

### Tactics, Techniques, and Procedures (TTPs)
- ![](img/01.05.10.jpg)
    - tactics --- guidelines
        - the way a hacker operates during different phases
        - used to gather info / privilege escalation / deploy measures for persistent access
        - 
    - techniques --- methods
        - tool methodology
        - include
            - initial exploitation,   
            - setting up and maintaining command and control channels,
            - accessing the target infrastructure,
            - covering the tracks of data exfiltration
    - procedures --- sequence
        - sequence of action to execute different steps of an attack

### Adversary Behavioral Identification
- ![](img/01.06.01.jpg)
    - identification of common methods to launch attacks
- ![](img/01.06.02.jpg)
- ![](img/01.06.03.jpg)
- ![](img/01.06.04.jpg)
- ![](img/01.06.05.jpg)

### Indicators of Compromise (IoCs)
- ![](img/01.07.01.jpg)
    - IoC are artifacts of potential intrusion / malicious activity
        - good source of information... but NOT INTELLIGENCE

### Categories of Indicators of Compromise
- ![](img/01.08.01.jpg)
    - email 
        - sending malicious data
    - network
        - CaC, malware delivery, reconnaisance of ports/OS
    - host-based
        - analysis of infected system
            - registry keys, dlls, changed file hashes
    - behavior
        - specific behavior analogous to malicious behavior
            - PS scripts running / remote command executions
            - ip addresses / virus signatures

### Hacking Concepts
- ![](img/01.09.01.jpg)

### What is Hacking?
- ![](img/01.10.01.jpg)
    - exploiting system vulnerabilities ... compromising security controls... to gain unauthorized/unintended access to...
        1. modify system/app to achieve a goal outside of creator's intention
        1.  redistribute intellectual property
        1.  cause business loss

### Who is a Hacker?
- ![](img/01.11.01.jpg)
    - someone with the ability to create/explore software/hardware
    - someone with a hobby to see how to compromise computers/networks
    - someone who wants financial gain

### Hacker Classes
- ![](img/01.12.01.jpg)

### Hacking Phases
- ![](img/01.16.01.jpg)

### Hacking Phase: Reconnaissance
- ![](img/01.13.01.jpg)
    - Overview
        - gather info about a target
        - target is known only on a broad scale
        - target can be clients / employees / networks /systems
    - Passive Recon
        - WITHOUT interacting with system
    - Active Recon
        - WITH interacting with target


### Hacking Phase: Scanning
- ![](img/01.14.01.jpg)
    - Pre-attack
        - first scan of network
            - to obtain specific information
    - Port Scanner
        - using port scanner, network mapper, ping tools, vulscanner
    - Extract Information
        - using the previoud methods to ascertain...
            - live machines
            - OS details
            - device types
            - system uptime

### Hacking Phase: Gaining Access
- ![](img/01.15.01.jpg)
    - where the real hacking occurs
        - point where the attack obtains access to OS/Apps on Computer/Network
    - NOT A REQUIREMENT
        - can be skipped via `consuming all outgoing communication links`
    - examples
        - password cracking
        - stack-based buffer overflows
        - session hacking
    - Two types of attacks
        - packet flooding
            - flooding availibility of essential services
        - smurf attack
            - covering your tracks by causing others to attack on your behalf
    - factors affecting hacker's ability to gain access
        - architecture/configuration of target
        - skill of agent
        - initial level of access 

### Hacking Phase: Maintaining Access
- ![](img/01.17.01.jpg)
    - retain their ownership
    - ensuring exclusive access via backdoors, rootkits, trojans
    - maintain access via manipulating data / apps / configurations

### Hacking Phase: Clearing Tracks
- ![](img/01.18.01.jpg)
    - clearing tracks to hide malicious acts
    - with the intention to remain unnoticed / avoid prosecution
        - steganography to hide data in image/sound files
        - tunneling to carry one protocol over another to hide information extraction
    - by overwriting logs in server / system / app
        - tools like PsTools, NetCat to erase footprints from system logs

### Ethical Hacking Concepts
- ![](img/01.19.01.jpg)

### What is Ethical Hacking?
- ![](img/01.20.01.jpg)
    - ![](img/01.20.02.jpg)

### Why Ethical Hacking is Necessary
- ![](img/01.21.01.jpg)
    - ![](img/01.21.02.jpg)
        - ![](img/01.21.03.jpg)
        - ![](img/01.21.04.jpg)

### Scope and Limitations of Ethical Hacking
- ![](img/01.22.01.jpg)
    - Scope
        - risks / remediation of Ethical Hacking
    - Limitations


### Skills of an Ethical Hacker
- ![](img/01.23.01.jpg)
    - ![](img/01.23.02.jpg)

### Information Assurance (IA)
- ![](img/01.24.01.jpg)
    - Goal
        - assurance of Integrity, Availability, Confidentiality, Authenticity of information
        - in any information usage, processing, storage, and transmission
    - Hard Strategies
        - better authentication
        - id'ing network vulnerabilities
        - id'ing and planning around resource requirements
    - Soft Strategies
        - write/review policies
        - review IA controls
        - certification / accreditation
        - manpower training

### Defense-in-Depth
- ![](img/01.25.01.jpg)
    - unlike in the military
        - a leak in one can cause a failure of the system

### What is Risk?
- ![](img/01.26.01.jpg)
    - Definition of Risk
        -  degree of **uncertainty or expectation of potential damage** to the system or its resources
        - **probability of the occurrence** of a threat or an event that will damage,
        -  **possibility of a threat** acting upon an internal or external vulnerability
        -  **likelihood that an event** will occur
            - keywords
                - probability
                - likelihood
                - possibility
    - ATV = Asset-impact ... Threat ... Vulnerability

### Risk Management
- ![](img/01.27.01.jpg)
    - ![](img/01.27.02.jpg)
        - 
    - 
        - 
- Four Key Steps
    - ![](img/01.27.03.jpg)
    - ![](img/01.27.04.jpg)
    - ![](img/01.27.05.jpg)
        - prioritizing treatment based on assessment of `liklihood` and `severity`
    - ![](img/01.27.06.jpg)

### Cyber Threat Intelligence
- ![](img/01.28.01.jpg)
    - ![](img/01.28.02.jpg)
        - focuses on trends and impact of attack / reaction
    - ![](img/01.28.03.jpg)
        - focuses on HOW to perform an attack
    - ![](img/01.28.04.jpg)
        - focuses on WHO and THEIR PAST / CAPAIBILITIES
    - ![](img/01.28.05.jpg)
        - focues on TOOLS and RESOURCES

### Threat Modeling
- ![](img/01.29.01.jpg)
    - Basic definition
        - analyzing all aspects of a system affecting it's security
- Steps
    - ![](img/01.29.02.jpg)
        - establish goals / constraints of a system's CIA
        - need to ascertain effort for subsequent steps
    - ![](img/01.29.03.jpg)
        - identifying components, data flow, trust boundaries
        - admin should explain how system works, data flows, permissions
            - identify roles/permission
            - identify key scenarios (uploading, downloading)
            - identify technologies (hardware, software, networking)
            - identify application security mechanisms ()
    - ![](img/01.29.04.jpg)
        - further analysis on 
            - system boundaries
            - access control points
            - trust boundaries
    - ![](img/01.29.05.jpg)
        - identify threat IRT control scenario / context
        - development and test teams together to id potential threats
    - ![](img/01.29.06.jpg)
        - formally identifying vulnerabilities
        - identifying steps/resources to correct vulnerabilites

### Incident Management
- ![](img/01.30.01.jpg)
    - goal -- restore normal service operations
    - Consists of...
        - ![](img/01.30.02.jpg)
            - monitoring
            - detections
            - analysis
                - artifact
                - vulnerability
            - training
    - ![](img/01.30.03.jpg)

### Incident Handling and Response
- ![](img/01.31.01.jpg)
    - Overview
        -  process of taking organized and careful steps when reacting to a security incident or cyberattack
        -  set of procedures, actions, and measures taken against an unexpected event occurrence 
- Process
    - ![](img/01.31.02.jpg)
        - audit of resources/assets
        - reviewing purpose of security
        - define the rules, policies, and procedures that drive the IH&R process
    - ![](img/01.31.03.jpg)
        - 
    - ![](img/01.31.04.jpg)
        - 
    - ![](img/01.31.05.jpg)
        - 
    - ![](img/01.31.06.jpg)
        - 
    - ![](img/01.31.07.jpg)
        - 
    - ![](img/01.31.08.jpg)
        - 
    - ![](img/01.31.09.jpg)
        - 
    - ![](img/01.31.10.jpg)
        - 
    - 
        - 

### Role of AI and ML in Cyber Security
- ![](img/01.32.01.jpg)
    - ![](img/01.32.02.jpg)
        - ![](img/01.32.03.jpg)
- Supervised Learning 
    - input a set of labeled training data to attempt to learn the differences between the given labels.
        - Classification is for completely divided classes. 
            - to define the test sample to identify its class
        - Regression is used when data classes are not separated
            - ideal if data stream is continuous
- Unsupervised Learning
    -  input unlabeled training data to attempt to deduce all the categories without guidance
        - Clustering divides the data into clusters based on their similarities
        - Dimensionality reduction is the process of reducing the dimensions (attributes) of data.

### How Do AI and ML Prevent Cyber Attacks?
- ![](img/01.33.01.jpg)
    - ![](img/01.33.02.jpg)
    - ![](img/01.33.03.jpg)
    - ![](img/01.33.04.jpg)
    - ![](img/01.33.05.jpg)
    - ![](img/01.33.06.jpg)
    - ![](img/01.33.07.jpg)
    - ![](img/01.33.08.jpg)
    - ![](img/01.33.09.jpg)
    - ![](img/01.33.10.jpg)
    - ![](img/01.33.11.jpg)

### Information Security Laws and Standards
- ![](img/01.34.01.jpg)

### Payment Card Industry Data Security Standard (PCI DSS)
- ![](img/01.35.01.jpg)
    - ![](img/01.34.02.jpg)

### ISO/IEC 27001:2013
- ![](img/01.35.02.jpg)
    - 27001 -- 2013
        - improving information security management systems within context of an organization

### Health Insurance Portability and Accountability Act (HIPAA)
- ![](img/01.36.01.jpg)
    - covers transactions 
        -  adhere to the content and format requirements of each transaction
        - health care providers mush have..
            -  same health care transactions, code sets, and identifiers
    - privacy rules
        - safeguards
        - limits / conditions of disclosure
    - security rules
        - ensure the confidentiality, integrity, and security of electronically protected health information.
    - Employer Identifier Standard
        - standard national number for transactions
    - National Provider Identifier (NPI)
        - unique identification number assigned to covered health care providers
        - must use the NPIs in the administrative and financial transactions adopted under HIPAA.
        - 10-position, intelligence-free numeric identifier (10-digit number)

### Sarbanes Oxley Act (SOX)
- ![](img/01.37.01.jpg)
    -  Title I: Public Company Accounting Oversight Board (PCAOB):
        - independent oversight of public accounting firms
        - tasked with 
            - registering audit services, 
            - defining the specific processes and procedures for compliance audits, 
            - inspecting and policing conduct and quality control
    -  Title II: Auditor Independence
        - standards for external auditor independence
            -  to limit conflicts of interest.
        - covers
            - new auditor approval requirements,  
            - audit partner rotation,
            - and auditor reporting requirements
    -  Title III: Corporate Responsibility
        - mandates that senior executives take 
            - responsibility for the accuracy and completeness of corporate financial reports
    -  Title IV: Enhanced Financial Disclosures
        - enhanced reporting requirements for financial transactions
            - requires internal controls to ensure the accuracy of financial reports 
    -  Title V: Analyst Conflicts of Interest
        - code of conduct for securities analysts
        - requires that they disclose any knowable conflicts of interest
    -  Title VI: Commission Resources and Authority
        - SEC’s authority to censure or bar securities professionals from practice 
    -  Title VII: Studies and Reports
        -  requires Comptroller General and SEC to perform various studies and to report their findings.
    -  Title VIII: Corporate and Criminal Fraud Accountability
        -  specific criminal penalties for the manipulation, destruction, or alteration of financial records
    -  Title IX: White-Collar-Crime Penalty Enhancement
        -  criminal penalties associated with white-collar crimes and conspiracies.
    -  Title X: Corporate Tax Returns:
        - Chief Executive Officer should sign the company tax return.
    -  Title XI: Corporate Fraud Accountability
        - identifies corporate fraud and records tampering as criminal offenses

### The Digital Millennium Copyright Act (DMCA)
- ![](img/01.38.01.jpg)

### The Federal Information Security Management Act (FISMA)
- ![](img/01.38.02.jpg)
    - Two standards
        - mission impact of IS
        - minimum security requirements of IS
    - Three guidances
        - selecting security controls
        - assessing security controls
        - implementing security authorization
- 
    - 
        - 
    - 
        - 

### General Data Protection Regulation (GDPR)
- ![](img/01.40.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Data Protection Act 2018 (DPA)
- ![](img/01.41.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Cyber Law in Different Countries
- ![](img/01.42.01.jpg)
- ![](img/01.42.02.jpg)
- ![](img/01.42.03.jpg)



### REVIEW......
- ![](img/01.99.01.jpg)
    - Threat Modeling
        - analyzing security by capturing info that affects it
    - Incident Management
        - processes to ID/resolve security incidents TO RESTORE
    - Information Assurance (IA)
        - CIAA of IS during usage of info
    - Defense-In-Depth
        - more difficult for an enemy to defeat
- ![](img/01.99.02.jpg)
- ![](img/01.99.03.jpg)
    - Supervised Learning (labeled training) (think CpR)
        - Classification is for completely **divided classes**. 
            - to define the test sample to **identify its class**
        - Regression is used when data **classes are not separated**
            - ideal if data stream is **continuous**
    - Unsupervised Learning (unlabeled)
        - Clustering divides the data into clusters **based on their similarities**
        - Dimensionality reduction is the process of **reducing the dimensions** (attributes) of data.
- ![](img/01.99.04.jpg)
    - Active - tamper with data
    - Distribution - tamper with hardware
- ![](img/01.99.05.jpg)
- ![](img/01.99.06.jpg)
    - Strategic threat intelligence
        - high-level info
    - Operational threat intelligence
        - contextual info about an event
        - focuses on methodologies
    - Technical threat intelligence
        - response to threat
    - Tactical threat intelligence
        - protecting a specific resource
- 
- 
- 
- 

## Module 02 - Footprinting and Reconnaissance
- ![](img/02.00.jpg)

### Module Objectives
- ![](img/02.01.01.jpg)
    - ![](img/02.01.02.jpg)

### Footprinting Concepts
- ![](img/02.02.01.jpg)
    - Passive
        - ![](img/02.02.02.jpg)
    - Active
        - ![](img/02.02.03.jpg)
            -social engineering

### Types of Footprinting
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Information Obtained in Footprinting
- Organization Information
    - ![](img/02.03.01.jpg)
- Network Information
    - ![](img/02.03.02.jpg)
- System Infromation
    - ![](img/02.03.03.jpg)

### Objectives of Footprinting
- Security Posture Knowledge
    - 
        - 
- Focus Area Reduction
    - 
        - 
- Vulnerability Identification
    - 
        - 
- Network Mapping
    - 
        - 

### Footprinting Threats
- Social Engineering
    -  hackers directly and indirectly collect information through persuasion 
- System and Network Attacks
    - gather info related to ...
        - target organization’s system configuration, 
        - the operating system running on the machine
    - use information to find vulnerabilities
- Information leakage
    - information can be used to mount attacks
- Privacy Loss
    - even escalate the privileges up to admin levels
        - resulting in the loss of privacy for the organization as a whole and for its individual personnel
- Corporate Espionage
    -  to secure sensitive data through footprinting
    - can use in ...
        - launch similar products in the market, 
        - alter prices, 
        - undermine the market position of a target organization.
- Business Loss

### Footprinting Methodology
- Basic
    jihanledo21504  Jihanvai521- procedure for collecting information about a target organization from all available sources
- Techniques
    - ![](img/02.03.04.jpg)

### Footprinting through Search Engines
- ![](img/02.04.01.jpg)

### Footprinting Using Advanced Google Hacking Techniques
- ![](img/02.05.01.jpg)
    -  art of creating complex search engine queries
        - valuable data about a target company from Google search results
    - `title:`
    - `site:`
    - `index.of`
    - 
    - 
    - 

### What can a Hacker do with Google Hacking?
- Overall
    -  filter large amounts of search results to obtain information related to computer security
        -  also locate private, sensitive information about others
    - ![](img/02.06.01.jpg)
- ![](img/02.06.02.jpg)
    - ![](img/02.06.03.jpg)

### Google Hacking Database
- ![](img/02.06.04.jpg)
    - You can
        - will find search terms for files containing usernames, vulnerable servers, and even files containing passwords
        -  rapidly identify all the publicly available exploits and vulnerabilities of the target organization’s IT infrastructure

### VoIP and VPN Footprinting through Google Hacking Database
- ![](img/02.07.01.jpg)
    - can be used to 
        -  footprinting VoIP and VPN networks
        - extract info such as login portals, VoIP login portals, directories with keys of VPN servers,
    - ![](img/02.07.02.jpg)
        - ![](img/02.07.03.jpg)

### Other Techniques for Footprinting through Search Engines
- ![](img/02.08.01.jpg)
    - FTP
        - ![](img/02.08.02.jpg)
        - ![](img/02.08.03.jpg)

### Finding a Company’s Top-Level Domains (TLDs) and Sub-domains
- ![](img/02.08.04.jpg)
    - Search
        - ![](img/02.09.01.jpg)
    - sublister
        - ![](img/02.09.02.jpg)
    - pentest-tools.com
        - ![](img/02.09.03.jpg)
- 
    - 
        - 
    - 
        - 

### Finding the Geographical Location of the Target
- ![](img/02.10.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### People Search on Social Networking Sites
- ![](img/02.11.01.jpg)
    - 
        - 
    - 
        - 

### People Search on People Search Services
- ![](img/02.12.01.jpg)
    - 
        - 
    - 
        - 

### Gathering Information from LinkedIn
- ![](img/02.13.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Harvesting Email Lists
- ![](img/02.14.01.jpg)s
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Gathering Information from Financial Services
- ![](img/02.15.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Footprinting through Job Sites
- ![](img/02.16.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Deep and Dark Web Footprinting
- ![](img/02.17.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Determining the Operating System
- ![](img/02.18.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### VoIP and VPN Footprinting through SHODAN
- ![](img/02.19.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Competitive Intelligence Gathering
- ![](img/02.20.01.jpg)
    - ![](img/02.20.02.jpg)
        - 
    - 
        - 
- Sources of Competitive Intelligence
    - ![](img/02.20.03.jpg)
    - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Competitive Intelligence - When Did this Company Begin? How Did it Develop?
- ![](img/02.21.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Competitive Intelligence - What Are the Company's Plans?
- ![](img/02.22.01.jpg)
    - ![](img/02.22.02.jpg)
    - ![](img/02.22.03.jpg)
    - 
        - 
- ![](img/02.22.04.jpg)
    - ![](img/02.22.05.jpg)
    - ![](img/02.22.06.jpg)
    - 
        - 

### Competitive Intelligence - What Expert Opinions Say About the Company?
- ![](img/02.23.01.jpg)
    - ![](img/02.23.02.jpg)
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Techniques for Footprinting through Web Services
- ![](img/02.24.01.jpg)
    - ![](img/02.24.02.jpg)
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Footprinting through Social Networking Sites
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Collecting Information through Social Engineering on Social Networking Sites
- ![](img/02.25.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### General Resources for Locating Information from Social Media Sites
- ![](img/02.26.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Conducting Location Search on Social Media Sites
- ![](img/02.26.02.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tools for Footprinting through Social Networking Sites
- ![](img/02.27.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Website Footprinting
- ![](img/02.28.01.jpg)
    - ![](img/02.28.02.jpg)
        - ![](img/02.28.03.jpg)
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Website Footprinting using Web Spiders
- ![](img/02.29.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Mirroring Entire Website
- ![](img/02.30.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Extracting Website Information from https://archive.org
- ![](img/02.31.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Extracting Website Links
- ![](img/02.32.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Gathering Wordlist from the Target Website
- ![](img/02.33.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Extracting Metadata of Public Documents
- ![](img/02.34.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Techniques for Website Footprinting
- ![](img/02.35.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Email Footprinting
- ![](img/02.37.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tracking Email Communications
- ![](img/02.36.01.jpg)
    - ![](img/02.36.02.jpg)
    - ![](img/02.36.03.jpg)
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Collecting Information from Email Header
- ![](img/02.38.01.jpg)
    - ![](img/02.38.02.jpg)s
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Email Tracking Tools
- ![](img/02.39.01.jpg)
    - ![](img/02.39.02.jpg)
    - ![](img/02.39.03.jpg)
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Whois Footprinting
- ![](img/02.40.01.jpg)
    - ![](img/02.40.02.jpg)
        - ![](img/02.40.03.jpg)
        - ![](img/02.40.04.jpg)
    - ![](img/02.40.05.jpg)
    - ![](img/02.40.06.jpg)

### Finding IP Geolocation Information
- ![](img/02.41.01.jpg)
    - 
        - 
    - 
        - 

### DNS Footprinting
- ![](img/02.42.01.jpg)
    - ![](img/02.42.02.jpg)
        - 
    - 
        - 

### Reverse DNS Lookup
- ![](img/02.43.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Network Footprinting
- ![](img/02.44.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Locate the Network Range
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Traceroute
- ![](img/02.45.01.jpg)
    - ![](img/02.44.02.jpg)
        - ![](img/02.45.02.jpg)
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Traceroute Analysis
- ![](img/02.46.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Traceroute Tools
- ![](img/02.47.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Footprinting through Social Engineering
- ![](img/02.48.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Collecting Information Using Eavesdropping, Shoulder Surfing, Dumpster Diving, and Impersonation
- ![](img/02.49.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Footprinting Tools
- ![](img/02.50.01.jpg)
    - ![](img/02.50.02.jpg)
    - ![](img/02.51.01.jpg)
    - ![](img/02.50.03.jpg)
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Footprinting Countermeasures
    - ![](img/02.51.02.jpg)
        - ![](img/02.51.03.jpg)

### REVIEW......
- ![](img/02.99.01.jpg)
    - Sherlock
        - social media
    - BeRoot
        - misconfigurations once Root is obtained 
    - OpUtils
        - SNMP utility for sending modified SNMP 
    - Sublister
        - enumerates subdomains
-   ![](img/02.99.02.jpg)
- ![](img/02.99.03.jpg)
    - intelius
        - people search 
    - mention
        - online reputation (blog, somed)
- ![](img/02.99.05.jpg)
- ![](img/02.99.06.jpg)
    - 
        - 
- ![](img/02.99.07.jpg)
- ![](img/02.99.08.jpg)
    - 
        - 
    - 
        - 
- ![](img/02.99.09.jpg)
- ![](img/02.99.10.jpg)
        - 
    - 
        - 
- ![](img/02.99.11.jpg)
    - 
        - 
    - 
        - 
- ![](img/02.99.12.jpg)

<hr />

## Module 03 - Scanning Networks
- ![](img/03.00.jpg)

### Network Scanning Concepts
- ![](img/03.01.01.jpg)
    - ![](img/03.01.02.jpg)
    - ![](img/03.01.03.jpg)
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Overview of Network Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### TCP Communication Flags
- ![](img/03.02.01.jpg)
    - ![](img/03.02.02.jpg)
        - 
    - 
        - 

### TCP/IP Communication
- ![](img/03.03.01.jpg)
    - ![](img/03.03.02.jpg)
    - ![](img/03.03.03.jpg)

### Scanning Tools
- ![](img/03.04.01.jpg)
- ![](img/03.04.02.jpg)
    - ![](img/03.04.03.jpg)
        - ![](img/03.04.05.jpg)
- ![](img/03.04.04.jpg)
    - netscantools
        -  troubleshoot, monitor, discover, and detect devices on your network.
- 
    - 
        - 
    - 
        - 

### Scanning Tools for Mobile
- ![](img/03.05.01.jpg)
    - ![](img/03.05.02.jpg)
    - ![](img/03.05.03.jpg)
    - ![](img/03.05.04.jpg)

### Host Discovery
- ![](img/03.06.01.jpg)

### Host Discovery Techniques
- ![](img/03.07.01.jpg)
    - ![](img/03.07.02.jpg)

### ARP Ping Scan and UDP Ping Scan
- ![](img/03.08.01.jpg)
    - ![](img/03.08.04.jpg)
        - ![](img/03.08.02.jpg)
    - ![](img/03.08.03.jpg)
        - ![](img/03.08.05.jpg)
- 
    - 
        - 
    - 
        - 

### ICMP ECHO Ping Scan
- ![](img/03.09.01.jpg)
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### ICMP ECHO Ping Sweep
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Ping Sweep Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Ping Sweep Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Host Discovery Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Port and Service Discovery
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Port Scanning Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### TCP Connect/Full Open Scan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Stealth Scan (Half-open Scan)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Inverse TCP Flag Scan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Xmas Scan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### TCP Maimon scan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### ACK Flag Probe Scan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IDLE/IPID Header Scan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### UDP Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SCTP INIT Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SCTP COOKIE ECHO Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SSDP and List Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IPv6 Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Service Version Discovery
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Nmap Scan Time Reduction Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Port Scanning Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### OS Discovery (Banner Grabbing/OS Fingerprinting)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### OS Discovery/Banner Grabbing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Identify Target System OS
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### OS Discovery using Nmap and Unicornscan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### OS Discovery using Nmap Script Engine
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### OS Discovery using IPv6 Fingerprinting
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Banner Grabbing Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Scanning Beyond IDS and Firewall
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IDS/Firewall Evasion Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Packet Fragmentation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Source Routing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Source Port Manipulation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IP Address Decoy
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IP Address Spoofing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IP Spoofing Detection Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IP Spoofing Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Creating Custom Packets
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Randomizing Host Order and Sending Bad Checksums
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Proxy Servers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Proxy Chaining
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Proxy Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Proxy Tools for Mobile
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Anonymizers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Censorship Circumvention Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Anonymizers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Anonymizers for Mobile
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Draw Network Diagrams
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Drawing Network Diagrams
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Network Discovery and Mapping Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Network Discovery Tools for Mobile
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Summary
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 


## Module 04 - Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Objectives
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Enumeration Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is Enumeration?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Techniques for Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Services and Ports to Enumerate
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NetBIOS Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NetBIOS Enumeration Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Enumerating User Accounts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Enumerating Shared Resources Using Net View
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SNMP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Working of SNMP
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Management Information Base (MIB)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SNMP Enumeration Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### LDAP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### LDAP Enumeration Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTP and NFS Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTP Enumeration Commands
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTP Enumeration Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NFS Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NFS Enumeration Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SMTP and DNS Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SMTP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SMTP Enumeration Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DNS Enumeration Using Zone Transfer
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DNS Cache Snooping
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DNSSEC Zone Walking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Enumeration Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IPsec Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### VoIP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### RPC Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Unix/Linux User Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Telnet Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SMB Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### FTP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### TFTP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IPv6 Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### BGP Enumeration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Enumeration Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Summary
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 


## Module 05 - Vulnerability Analysis
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Objectives
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Assessment Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Research
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Resources for Vulnerability Research
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is Vulnerability Assessment?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Scoring Systems and Databases
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Common Vulnerability Scoring System (CVSS)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Common Vulnerabilities and Exposures (CVE)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### National Vulnerability Database (NVD)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Common Weakness Enumeration (CWE)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability-Management Life Cycle
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Pre-Assessment Phase
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Assessment Phase
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Post Assessment Phase
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Classification and Assessment Types
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Classification
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Vulnerability Assessment
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Assessment Solutions and Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Comparing Approaches to Vulnerability Assessment
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Characteristics of a Good Vulnerability Assessment Solution
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Working of Vulnerability Scanning Solutions
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Vulnerability Assessment Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Choosing a Vulnerability Assessment Tool
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Criteria for Choosing a Vulnerability Assessment Tool
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Best Practices for Selecting Vulnerability Assessment Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Assessment Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Assessment Tools for Mobile
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Assessment Reports
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Analyzing Vulnerability Scanning Report
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Summary
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 


## Module 06 - System Hacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Objectives
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### System Hacking Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### CEH Hacking Methodology (CHM)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### System Hacking Goals
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Gaining Access
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Microsoft Authentication
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How Hash Passwords Are Stored in Windows SAM?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTLM Authentication Process
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Kerberos Authentication
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Password Cracking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Password Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Non-Electronic Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Active Online Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Active Online Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Passive Online Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Offline Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Password Recovery Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tools to Extract the Password Hashes
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Password-Cracking Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Password Salting
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against Password Cracking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against LLMNR/NBT-NS Poisoning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tools to Detect LLMNR/NBT-NS Poisoning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Exploitation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Exploit Sites
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Buffer Overflow
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Buffer Overflow
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Simple Buffer Overflow in C
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Windows Buffer Overflow Exploitation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Buffer Overflow Detection Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Defending against Buffer Overflows
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Escalating Privileges
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation Using DLL Hijacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation by Exploiting Vulnerabilities
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation Using Dylib Hijacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation using Spectre and Meltdown Vulnerabilities
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation using Named Pipe Impersonation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation by Exploiting Misconfigured Services
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Pivoting and Relaying to Hack External Machines 
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Privilege Escalation Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Privilege Escalation Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend Against Privilege Escalation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tools for Defending against DLL and Dylib Hijacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Defending against Spectre and Meltdown Vulnerabilities
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tools for Detecting Spectre and Meltdown Vulnerabilities
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Maintaining Access
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Executing Applications
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Remote Code Execution Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tools for Executing Applications
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Keylogger
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Keystroke Loggers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Hardware Keyloggers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Keyloggers for Windows
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Keyloggers for Mac
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Spyware
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Spyware Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against Keyloggers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Anti-Keyloggers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against Spyware
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Anti-Spyware
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Hiding Files
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Rootkits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Rootkits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How a Rootkit Works
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Popular Rootkits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Detecting Rootkits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Steps for Detecting Rootkits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against Rootkits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Anti-Rootkits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTFS Data Stream
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Create NTFS Streams
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTFS Stream Manipulation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against NTFS Streams
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### NTFS Stream Detectors
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is Steganography?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Classification of Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Steganography based on Cover Medium
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Whitespace Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Image Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Document Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Video Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Audio Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Folder Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Spam/Email Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Steganography Tools for Mobile Phones
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Steganalysis
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Steganalysis Methods/Attacks on Steganography
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Detecting Steganography (Text, Image, Audio, and Video Files)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Steganography Detection Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Clearing Logs
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Covering Tracks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Disabling Auditing: Auditpol
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Clearing Logs
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Manually Clearing Event Logs
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Ways to Clear Online Tracks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Covering BASH Shell Tracks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Covering Tracks on a Network
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Covering Tracks on an OS
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Delete Files using Cipher.exe
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Disable Windows Functionality
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Track-Covering Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Defending against Covering Tracks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Summary
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 


## Module 07 - Malware Threats
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Objectives
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Malware Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Introduction to Malware
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Different Ways for Malware to Enter a System
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Common Techniques Attackers Use to Distribute Malware on the Web
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Components of Malware
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### APT Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What are Advanced Persistent Threats?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Characteristics of Advanced Persistent Threats
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Advanced Persistent Threat Lifecycle
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Trojan Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is a Trojan?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How Hackers Use Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Common Ports used by Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Remote Access Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Backdoor Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Botnet Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Rootkit Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### E-banking Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Working of E-banking Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

###  E-banking Trojan: Dreambot
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Point-of-Sale Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Defacement Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Service Protocol Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Mobile Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IoT Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Security Software Disabler Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Destructive Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DDoS Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Command Shell Trojans
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Infect Systems Using a Trojan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Creating a Trojan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Employing a Dropper or Downloader
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Employing a Wrapper
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Employing a Crypter
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Propagating and Deploying a Trojan
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Deploy a Trojan through Emails
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Deploy a Trojan through Covert Channels
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Deploy a Trojan through Proxy Servers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Deploy a Trojan through USB/Flash Drives
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Techniques for Evading Antivirus Software
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Exploit Kits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Virus and Worm Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Introduction to Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Stages of Virus Lifecycle
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Working of Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How does a Computer Get Infected by Viruses?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### System or Boot Sector Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### File Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Multipartite Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Macro Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Cluster Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Stealth Viruses/Tunneling Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Encryption Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Sparse Infector Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Polymorphic Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Metamorphic Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Overwriting File or Cavity Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Companion/Camouflage Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Shell Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### File Extension Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### FAT Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Logic Bomb Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Scripting Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### E-mail Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Armored Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Add-on Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Intrusive Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Direct Action or Transient Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Terminate and Stay Resident (TSR) Viruses
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Ransomware
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Infect Systems Using a Virus
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Creating a Virus
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Propagating and Deploying a Virus
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Virus Hoaxes
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Fake AntiVirus
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Computer Worms
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Worm Makers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Fileless Malware Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is Fileless Malware?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Taxonomy of Fileless Malware Threats
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How does Fileless Malware Work?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Launching Fileless Malware through Document Exploits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Launching Fileless Malware through In-Memory Exploits
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Launching Fileless Malware through Script-based Injection
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Launching Fileless Malware by Exploiting System Admin Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Launching Fileless Malware through Phishing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Maintaining Persistence with Fileless Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Fileless Malware
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Fileless Malware Obfuscation Techniques to Bypass Antivirus
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Malware Analysis
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is Sheep Dip Computer?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Antivirus Sensor Systems
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Introduction to Malware Analysis
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Malware Analysis Procedure
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Preparing Testbed
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Static Malware Analysis
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### File Fingerprinting
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Local and Online Malware Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Performing Strings Search
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Identifying Packing/Obfuscation Methods
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Finding the Portable Executables (PE) Information
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Identifying File Dependencies
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Malware Disassembly
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Dynamic Malware Analysis
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Port Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Process Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Registry Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Windows Services Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Startup Programs Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Event Logs Monitoring/Analysis
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Installation Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Files and Folders Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Device Drivers Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Network Traffic Monitoring/Analysis
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### DNS Monitoring/Resolution
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### API Calls Monitoring
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Virus Detection Methods
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Trojan Analysis: Emotet
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Emotet Malware Attack Phases
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Infection Phase
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Maintaining Persistence Phase
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### System Compromise Phase
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Network Propagation Phase
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Virus Analysis: SamSam Ransomware
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### SamSam Ransomware Attack Stages
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Fileless Malware Analysis: Astaroth Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Trojan Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Backdoor Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Virus and Worm Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Fileless Malware Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Anti-Malware Software
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Anti-Trojan Software
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Antivirus Software
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Fileless Malware Detection Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Fileless Malware Protection Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Module Summary
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    


## Module 08 - Sniffing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Module Objectives
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Concepts
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Network Sniffing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How a Sniffer Works
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Types of Sniffing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How an Attacker Hacks the Network Using Sniffers
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Protocols Vulnerable to Sniffing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing in the Data Link Layer of the OSI Model
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Hardware Protocol Analyzers
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### SPAN Port
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Wiretapping
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Lawful Interception
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Technique: MAC Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### MAC Address
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### CAM Table
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How CAM Works
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### What Happens when a CAM Table is Full?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### MAC Flooding
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Switch Port Stealing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend against MAC Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Technique: DHCP Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How DHCP Works
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### DHCP Request/Reply Messages
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### IPv4 DHCP Packet Format
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### DHCP Starvation Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Rogue DHCP Server Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend Against DHCP Starvation and Rogue Server Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Technique: ARP Poisoning
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### What Is Address Resolution Protocol (ARP)?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### ARP Spoofing Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Threats of ARP Poisoning
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### ARP Poisoning Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend Against ARP Poisoning
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Configuring DHCP Snooping and Dynamic ARP Inspection on Cisco Switches
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### ARP Spoofing Detection Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Technique: Spoofing Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### MAC Spoofing/Duplicating
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### MAC Spoofing Technique: Windows
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### MAC Spoofing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### IRDP Spoofing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### VLAN Hopping
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### STP Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend Against MAC Spoofing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend Against VLAN Hopping
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend Against STP Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Technique: DNS Poisoning
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### DNS Poisoning Techniques
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Intranet DNS Spoofing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Internet DNS Spoofing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Proxy Server DNS Poisoning
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### DNS Cache Poisoning
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### DNS Poisoning Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend Against DNS Spoofing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Wireshark
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Follow TCP Stream in Wireshark
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Display Filters in Wireshark
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Additional Wireshark Filters
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Packet Sniffing Tools for Mobile Phones
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Defend Against Sniffing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffing Detection Techniques
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### How to Detect Sniffing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Sniffer Detection Techniques
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Promiscuous Detection Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Module Summary
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    


## Module 09 - Social Engineering
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Module Objectives
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Social Engineering Concepts
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### What is Social Engineering?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Common Targets of Social Engineering
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Impact of Social Engineering Attack on an Organization
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Behaviors Vulnerable to Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Factors that Make Companies Vulnerable to Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Why is Social Engineering Effective?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Phases of a Social Engineering Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Social Engineering Techniques
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Types of Social Engineering
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Impersonation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Impersonation (Vishing)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Eavesdropping
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Shoulder Surfing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Dumpster Diving
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Reverse Social Engineering
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Piggybacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Tailgating
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Diversion Theft
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Honey Trap
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Baiting
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Quid Pro Quo
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Elicitation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Computer-based Social Engineering
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Phishing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Examples of Phishing Emails
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Types of Phishing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Phishing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Mobile-based Social Engineering
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Publishing Malicious Apps
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Repackaging Legitimate Apps
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### Fake Security Applications
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 
    

### SMiShing (SMS Phishing)
    - 
        - 
    - 
        - 

### Insider Threats
    - 
        - 
    - 
        - 

### Behavioral Indications of an Insider Threat
-
    - 
        - 
    - 
        - 

### Types of Insider Threats
-
    - 
        - 
    - 
        - 

### Why are Insider Attacks Effective?
-
    - 
        - 
    - 
        - 

### Impersonation on Social Networking Sites
-
    - 
        - 
    - 
        - 

### Social Engineering through Impersonation on Social Networking Sites
-
    - 
        - 
    - 
        - 

### Impersonation on Facebook
-
    - 
        - 
    - 
        - 

### Social Networking Threats to Corporate Networks
-
    - 
        - 
    - 
        - 

### Identity Theft
-
    - 
        - 
    - 
        - 

### Common Techniques Attackers Use to Obtain Personal Information for Identity Theft
-
    - 
        - 
    - 
        - 

### Indications of Identity Theft
-
    - 
        - 
    - 
        - 

### Types of Identity Theft
-
    - 
        - 
    - 
        - 

### Countermeasures
-
    - 
        - 
    - 
        - 

### Social Engineering Countermeasures
-
    - 
        - 
    - 
        - 

### Detecting Insider Threats
-
    - 
        - 
    - 
        - 

### Insider Threats Countermeasures
-
    - 
        - 
    - 
        - 

### Identity Theft Countermeasures
-
    - 
        - 
    - 
        - 

### How to Detect Phishing Emails?
-
    - 
        - 
    - 
        - 

### Anti-Phishing Toolbar
-
    - 
        - 
    - 
        - 

### Common Social Engineering Targets and Defense Strategies
-
    - 
        - 
    - 
        - 

### Social Engineering Tools
-
    - 
        - 
    - 
        - 

### Audit Organization's Security for Phishing Attacks using OhPhish
-
    - 
        - 
    - 
        - 

### Module Summary
-
    - 
        - 
    - 
        - 


## Module 10 - Denial-of-Service
-
    - 
        - 
    - 
        - 

### Module Objectives
-
    - 
        - 
    - 
        - 

### DoS/DDoS Concepts
-
    - 
        - 
    - 
        - 

### How do DDoS Attacks Work?
-
    - 
        - 
    - 
        - 

### What is a DoS Attack?
-
    - 
        - 
    - 
        - 

### What is a DDoS Attack?
-
    - 
        - 
    - 
        - 

### DoS/DDoS Attack Techniques
-
    - 
        - 
    - 
        - 

### Basic Categories of DoS/DDoS Attack Vectors
-
    - 
        - 
    - 
        - 

### DoS/DDoS Attack Techniques
-
    - 
        - 
    - 
        - 

### UDP Flood Attack
-
    - 
        - 
    - 
        - 

### ICMP Flood Attack
-
    - 
        - 
    - 
        - 

### Ping of Death Attack
-
    - 
        - 
    - 
        - 

### Smurf Attack
-
    - 
        - 
    - 
        - 

### Pulse Wave DDoS Attack
-
    - 
        - 
    - 
        - 

### Zero-Day DDoS Attack
-
    - 
        - 
    - 
        - 

### SYN Flood Attack
-
    - 
        - 
    - 
        - 

### Fragmentation Attack
-
    - 
        - 
    - 
        - 

### Spoofed Session Flood Attack
-
    - 
        - 
    - 
        - 

### HTTP GET/POST Attack
-
    - 
        - 
    - 
        - 

### Slowloris Attack
-
    - 
        - 
    - 
        - 

### UDP Application Layer Flood Attack
-
    - 
        - 
    - 
        - 

### Multi-Vector Attack
-
    - 
        - 
    - 
        - 

### Peer-to-Peer Attack
-
    - 
        - 
    - 
        - 

### Permanent Denial-of-Service Attack
-
    - 
        - 
    - 
        - 

### Distributed Reflection Denial-of-Service (DRDoS) Attack
-
    - 
        - 
    - 
        - 

### Botnets
-
    - 
        - 
    - 
        - 

### Organized Cyber Crime: Organizational Chart
-
    - 
        - 
    - 
        - 

### Botnets
-
    - 
        - 
    - 
        - 

### A Typical Botnet Setup
-
    - 
        - 
    - 
        - 

### Botnet Ecosystem
-
    - 
        - 
    - 
        - 

### Scanning Methods for Finding Vulnerable Machines
-
    - 
        - 
    - 
        - 

### How Does Malicious Code Propagate?
-
    - 
        - 
    - 
        - 

### DDoS Case Study
-
    - 
        - 
    - 
        - 

### DDoS Attack
-
    - 
        - 
    - 
        - 

### Hackers Advertise Links for Downloading Botnets
-
    - 
        - 
    - 
        - 

### Use of Mobile Devices as Botnets for Launching DDoS Attacks
-
    - 
        - 
    - 
        - 

### DDoS Case Study: DDoS Attack on GitHub
-
    - 
        - 
    - 
        - 

### DoS/DDoS Attack Tools
-
    - 
        - 
    - 
        - 

### DoS/DDoS Attack Tools
-
    - 
        - 
    - 
        - 

### DoS/DDoS Attack Tools for Mobiles
-
    - 
        - 
    - 
        - 

### Countermeasures
-
    - 
        - 
    - 
        - 

### Detection Techniques
-
    - 
        - 
    - 
        - 

### DoS/DDoS Countermeasure Strategies
-
    - 
        - 
    - 
        - 

### DDoS Attack Countermeasures
-
    - 
        - 
    - 
        - 

### Protect Secondary Victims
-
    - 
        - 
    - 
        - 

### Detect and Neutralize Handlers
-
    - 
        - 
    - 
        - 

### Prevent Potential Attacks
-
    - 
        - 
    - 
        - 

### Deflect Attacks
-
    - 
        - 
    - 
        - 

### Mitigate Attacks
-
    - 
        - 
    - 
        - 

### Post-Attack Forensics
-
    - 
        - 
    - 
        - 

### Techniques to Defend against Botnets
-
    - 
        - 
    - 
        - 

### Additional DoS/DDoS Countermeasures
-
    - 
        - 
    - 
        - 

### DoS/DDoS Protection at ISP Level
-
    - 
        - 
    - 
        - 

### Enabling TCP Intercept on Cisco IOS Software
-
    - 
        - 
    - 
        - 

### DoS/DDoS Protection Tools
-
    - 
        - 
    - 
        - 

### Advanced DDoS Protection Appliances
-
    - 
        - 
    - 
        - 

### DoS/DDoS Protection Tools
-
    - 
        - 
    - 
        - 

### DoS/DDoS Protection Services
-
    - 
        - 
    - 
        - 

### Module Summary
-
    - 
        - 
    - 
        - 


## Module 11 - Session Hijacking
-
    - 
        - 
    - 
        - 

### Module Objectives
-
    - 
        - 
    - 
        - 

### Session Hijacking Concepts
-
    - 
        - 
    - 
        - 

### What is Session Hijacking?
-
    - 
        - 
    - 
        - 

### Why is Session Hijacking Successful?
-
    - 
        - 
    - 
        - 

### Session Hijacking Process
-
    - 
        - 
    - 
        - 

### Packet Analysis of a Local Session Hijack
-
    - 
        - 
    - 
        - 

### Types of Session Hijacking
-
    - 
        - 
    - 
        - 

### Session Hijacking in OSI Model
-
    - 
        - 
    - 
        - 

### Spoofing vs. Hijacking
-
    - 
        - 
    - 
        - 

### Application Level Session Hijacking
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Sniffing
-
    - 
        - 
    - 
        - 

### Compromising Session IDs by Predicting Session Token
-
    - 
        - 
    - 
        - 

### How to Predict a Session Token
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Man-in-the-Middle Attack
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Man-in-the-Browser Attack
-
    - 
        - 
    - 
        - 

### Steps to Perform Man-in-the-Browser Attack:
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Client-side Attacks
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Client-side Attacks: Cross-site Script Attack
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Client-side Attacks: Cross-site Request Forgery Attack
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Session Replay Attacks
-
    - 
        - 
    - 
        - 

### Compromising Session IDs Using Session Fixation
-
    - 
        - 
    - 
        - 

### Session Hijacking Using Proxy Servers
-
    - 
        - 
    - 
        - 

### Session Hijacking Using CRIME Attack
-
    - 
        - 
    - 
        - 

### Session Hijacking Using Forbidden Attack
-
    - 
        - 
    - 
        - 

### Session Hijacking Using Session Donation Attack
-
    - 
        - 
    - 
        - 

### Network Level Session Hijacking
-
    - 
        - 
    - 
        - 

### Three-way Handshake
-
    - 
        - 
    - 
        - 

### TCP/IP Hijacking
-
    - 
        - 
    - 
        - 

### IP Spoofing: Source Routed Packets
-
    - 
        - 
    - 
        - 

### RST Hijacking
-
    - 
        - 
    - 
        - 

### Blind Hijacking
-
    - 
        - 
    - 
        - 

### UDP Hijacking
-
    - 
        - 
    - 
        - 

### MITM Attack Using Forged ICMP and ARP Spoofing
-
    - 
        - 
    - 
        - 

### Session Hijacking Tools
-
    - 
        - 
    - 
        - 

### Session Hijacking Tools for Mobile Phones
-
    - 
        - 
    - 
        - 

### Countermeasures
-
    - 
        - 
    - 
        - 

### Session Hijacking Detection Methods
-
    - 
        - 
    - 
        - 

### Protecting against Session Hijacking
-
    - 
        - 
    - 
        - 

### Web Development Guidelines to Prevent Session Hijacking
-
    - 
        - 
    - 
        - 

### Web User Guidelines to Prevent Session Hijacking
-
    - 
        - 
    - 
        - 

### Session Hijacking Detection Tools
-
    - 
        - 
    - 
        - 

### Approaches Causing Vulnerability to Session Hijacking and their Preventative Solutions
-
    - 
        - 
    - 
        - 

### Approaches to Prevent Session Hijacking
-
    - 
        - 
    - 
        - 

### Approaches to Prevent MITM Attacks
-
    - 
        - 
    - 
        - 

### IPsec
-
    - 
        - 
    - 
        - 

### IPsec Authentication and Confidentiality
-
    - 
        - 
    - 
        - 

### Session Hijacking Prevention Tools
-
    - 
        - 
    - 
        - 

### Module Summary
-
    - 
        - 
    - 
        - 


## Module 12 - Evading IDS, Firewalls, and Honeypots
-
    - 
        - 
    - 
        - 

### Module Objectives
-
    - 
        - 
    - 
        - 

### IDS, IPS, Firewall, and Honeypot Concepts
-
    - 
        - 
    - 
        - 

### Intrusion Detection System (IDS)
-
    - 
        - 
    - 
        - 

### How an IDS Detects an Intrusion?
-
    - 
        - 
    - 
        - 

### General Indications of Intrusions
-
    - 
        - 
    - 
        - 

### Types of Intrusion Detection Systems
-
    - 
        - 
    - 
        - 

### Types of IDS Alerts
-
    - 
        - 
    - 
        - 

### Intrusion Prevention System (IPS)
-
    - 
        - 
    - 
        - 

### Firewall
-
    - 
        - 
    - 
        - 

### Firewall Architecture
-
    - 
        - 
    - 
        - 

### Demilitarized Zone (DMZ)
-
    - 
        - 
    - 
        - 

### Types of Firewalls
-
    - 
        - 
    - 
        - 

### Firewall Technologies
-
    - 
        - 
    - 
        - 

### Packet Filtering Firewall
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Circuit-Level Gateway Firewall
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Application-Level Firewall
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Stateful Multilayer Inspection Firewall
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Application Proxy
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Network Address Translation (NAT)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Virtual Private Network
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Firewall Limitations
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Honeypot
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Types of Honeypots
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IDS, IPS, Firewall, and Honeypot Solutions
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Intrusion Detection Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Intrusion Detection Tools for Mobile Devices
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Intrusion Prevention Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Firewalls
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Firewalls for Mobile Devices
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Honeypot Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Evading IDS
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IDS Evasion Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Insertion Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Evasion
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Denial-of-Service Attack (DoS)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Obfuscating
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### False Positive Generation
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Session Splicing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Unicode Evasion Technique
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Fragmentation Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Overlapping Fragments
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Time-To-Live Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Invalid RST Packets
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Urgency Flag
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Polymorphic Shellcode
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### ASCII Shellcode
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Application-Layer Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Desynchronization
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Types of Evasion
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Evading Firewalls
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Firewall Evasion Techniques
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Firewall Identification
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IP Address Spoofing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Source Routing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Tiny Fragments
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypass Blocked Sites Using an IP Address in Place of a URL
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypass Blocked Sites Using Anonymous Website Surfing Sites
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypass a Firewall Using a Proxy Server
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through the ICMP Tunneling Method
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through the ACK Tunneling method
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through the HTTP Tunneling Method
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through the SSH Tunneling Method
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through the DNS Tunneling Method
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through External Systems
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through MITM Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing Firewalls through Content
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing the WAF using an XSS Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IDS/Firewall Evading Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Packet Fragment Generator Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Detecting Honeypots
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Detecting and Defeating Honeypots
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Honeypot Detection Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### IDS/Firewall Evasion Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend Against IDS Evasion
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend Against Firewall Evasion
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Summary
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 


## Module 13 - Hacking Web Servers
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Objectives
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Operations
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Security Issues
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Why are Web Servers Compromised?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DoS/DDoS Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DNS Server Hijacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DNS Amplification Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Directory Traversal Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Man-in-the-Middle/Sniffing Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Phishing Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Website Defacement
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Misconfiguration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### HTTP Response-Splitting Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Cache Poisoning Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SSH Brute Force Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Password Cracking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Server-Side Request Forgery (SSRF) Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Attack Methodology
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Information Gathering
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Information Gathering from Robots.txt File
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Footprinting/Banner Grabbing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Footprinting Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Enumerating Web Server Information Using Nmap
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Website Mirroring
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Finding Default Credentials of Web Server
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Finding Default Content of Web Server
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Finding Directory Listings of Web Server
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Finding Exploitable Vulnerabilities
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Session Hijacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Password Hacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Using Application Server as a Proxy
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Attack Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Immunity’s CANVAS
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Metasploit
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Metasploit Modules
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Attack Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Place Web Servers in Separate Secure Server Security Segment on Network
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Countermeasures: Patches and Updates
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Countermeasures: Protocols and Accounts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Countermeasures: Files and Directories
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Detecting Web Server Hacking Attempts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend Against Web Server Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against HTTP Response-Splitting and Web Cache Poisoning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend against DNS Hijacking
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Patch Management
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Patches and Hotfixes
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is Patch Management?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Installation of a Patch
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Patch Management Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Security Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Security Scanners
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Security Scanners
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Malware Infection Monitoring Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Security Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Security Scanners
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Security Scanners
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Malware Infection Monitoring Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Security Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Server Pen Testing Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Summary
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 


## Module 14 - Hacking Web Applications
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Module Objectives
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Concepts
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Introduction to Web Applications
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Architecture
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Services
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Vulnerability Stack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Threats
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### OWASP Top 10 Application Security Risks – 2017
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A1 - Injection Flaws
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### SQL Injection Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Command Injection Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Command Injection Example
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### File Injection Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### LDAP Injection Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Injection Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A2 - Broken Authentication
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A3 - Sensitive Data Exposure
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A4 - XML External Entity (XXE)
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A5 - Broken Access Control
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A6 - Security Misconfiguration
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A7 - Cross-Site Scripting (XSS) Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### XSS Attack in Blog Posting
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### XSS Attack in Comment Field
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Cross-Site Scripting Attack Scenario: Attack via Email
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A8 - Insecure Deserialization
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A9 - Using Components with Known Vulnerabilities
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### A10 - Insufficient Logging and Monitoring
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Web Application Threats
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Directory Traversal
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Unvalidated Redirects and Forwards
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Watering Hole Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Cross-Site Request Forgery (CSRF) Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Cookie/Session Poisoning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Service Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Service Footprinting Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Service XML Poisoning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Hidden Field Manipulation Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web-based Timing Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### MarioNet Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Clickjacking Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### DNS Rebinding Attack
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Hacking Methodology
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Footprint Web Infrastructure
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Analyze Web Applications
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypass Client-side Controls
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Authentication Mechanism
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Authorization Schemes
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Access Controls
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Session Management Mechanism
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Perform Injection/Input Validation Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Application Logic Flaws
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Shared Environments
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Database Connectivity
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Web Application Client
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Attack Web Services
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Additional Web Application Hacking Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web API, Webhooks, and Web Shell
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What is Web API?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Service APIs
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### What are Webhooks?
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### OWASP Top 10 API Security Risks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### API Vulnerabilities
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web API Hacking Methodology
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Identify the Target
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Detect Security Standards
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Identify the Attack Surface
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Launch Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Other Techniques to Hack an API
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### REST API Vulnerability Scanning
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Bypassing IDOR via Parameter Pollution
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Shells
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Shell Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Gaining Backdoor Access via Web Shell
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Prevent Installation of a Web Shell
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Shell Detection Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Secure API Architecture
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### API Security Risks and Solutions
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Best Practices for API Security
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Best Practices for Securing Webhooks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Security
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Security Testing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Fuzz Testing
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Source Code Review
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Encoding Schemes
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Whitelisting vs. Blacklisting Applications
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Application Whitelisting and Blacklisting Tools
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend Against Injection Attacks
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### Web Application Attack Countermeasures
- 
    - 
        - 
    - 
        - 
- 
    - 
        - 
    - 
        - 

### How to Defend Against Web Application Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### RASP for Protecting Web Servers
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bug Bounty Programs
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Web Application Security Testing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Web Application Firewalls
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Summary
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 


## Module 15 - SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Objectives
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection Concepts
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### What is SQL Injection?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection and Server-side Technologies
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Understanding HTTP POST Request
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Understanding Normal SQL Query
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Understanding an SQL Injection Query
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Understanding an SQL Injection Query—Code Analysis
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Example of a Web Application Vulnerable to SQL Injection: BadProductList.aspx
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Example of a Web Application Vulnerable to SQL Injection: Attack Analysis
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Examples of SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Types of SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### In-Band SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Error Based SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Union SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind/Inferential SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection: No Error Message Returned
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection: WAITFOR DELAY (YES or NO Response)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection: Boolean Exploitation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection: Heavy Query
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Out-of-Band SQL injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection Methodology
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Information Gathering and SQL Injection Vulnerability Detection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Information Gathering
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Identifying Data Entry Paths
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Extracting Information through Error Messages
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection Vulnerability Detection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Additional Methods to Detect SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection Black Box Pen Testing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Source Code Review to Detect SQL Injection Vulnerabilities
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Testing for Blind SQL Injection Vulnerability in MySQL and MSSQL
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Launch SQL Injection Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform Union SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform Error Based SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform Error Based SQL Injection using Stored Procedure Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bypass Website Logins Using SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform Blind SQL Injection—Exploitation (MySQL)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection—Extract Database User
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection—Extract Database Name
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection—Extract Column Name
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blind SQL Injection—Extract Data from ROWS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform Double Blind SQL Injection—Classical Exploitation (MySQL)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform Blind SQL Injection Using Out-of-Band Exploitation Technique
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Exploiting Second-Order SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bypass Firewall using SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform SQL Injection to Insert a New User and Update Password
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Exporting a Value with Regular Expression Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Advanced SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Database, Table, and Column Enumeration
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Advanced Enumeration
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Creating Database Accounts
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Password Grabbing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Grabbing SQL Server Hashes
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Transfer Database to Attacker's Machine
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Interacting with the Operating System
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Interacting with the File System
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Network Reconnaissance Using SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Network Reconnaissance Full Query
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Finding and Bypassing Admin Panel of a Website
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### PL/SQL Exploitation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Creating Server Backdoors using SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### HTTP Header-Based SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### DNS Exfiltration using SQL Injection
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Case Study: SQL Injection Attack and Defense
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection Tools for Mobile Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Techniques
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evading IDS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Types of Signature Evasion Techniques
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: In-line Comment
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Char Encoding
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: String Concatenation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Obfuscated Code
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Manipulating White Spaces
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Hex Encoding
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Sophisticated Matches
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: URL Encoding
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Null Byte
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Case Variation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Declare Variables
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: IP Fragmentation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evasion Technique: Variation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### How to Defend Against SQL Injection Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Defenses in the Application
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Detecting SQL Injection Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SQL Injection Detection Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Summary
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 


## Module 16 - Hacking Wireless Networks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Objectives
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Concepts
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Terminology
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Networks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Standards
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Service Set Identifier (SSID)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Authentication Modes
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Authentication Process Using a Centralized Authentication Server
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Types of Wireless Antennas
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Encryption
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Types of Wireless Encryption
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wired Equivalent Privacy (WEP) Encryption
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Protected Access (WPA) Encryption
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WPA2 Encryption
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WPA3 Encryption
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Comparison of WEP, WPA, WPA2, and WPA3
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Issues in WEP, WPA, and WPA2
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Threats
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Access Control Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Integrity Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Confidentiality Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Availability Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Authentication Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Rogue AP Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Client Mis-Association
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Misconfigured AP Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Unauthorized Association
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Ad-Hoc Connection Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Honeypot AP Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### AP MAC Spoofing
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Denial-of-Service Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Key Reinstallation Attack (KRACK)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Jamming Signal Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Jamming Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### aLTEr Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wormhole Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Sinkhole Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Hacking Methodology
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Network Footprinting
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Finding Wi-Fi Networks in Range to Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Finding WPS-Enabled APs
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Discovery Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile-based Wi-Fi Discovery Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### GPS Mapping Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Hotspot Finder Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Network Discovery Through WarDriving
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Traffic Analysis
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Choosing the Optimal Wi-Fi Card
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Sniffing Wireless Traffic
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Perform Spectrum Analysis
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Launch of Wireless Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Aircrack-ng Suite
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Detection of Hidden SSIDs
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Fragmentation Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### MAC Spoofing Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Denial-of-Service: Disassociation and De-authentication Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Man-in-the-Middle Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### MITM Attack Using Aircrack-ng
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless ARP Poisoning Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### ARP Poisoning Attack Using Ettercap
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Rogue APs
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Creation of a Rogue AP Using MANA Toolkit
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Evil Twin
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Set Up of a Fake Hotspot (Evil Twin)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### aLTEr Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Jacking Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WEP Encryption Cracking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Cracking WEP Using Aircrack-ng
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WPA/WPA2 Encryption Cracking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Cracking WPA-PSK Using Aircrack-ng
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Cracking WPA/WPA2 Using Wifiphisher
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Cracking WPS Using Reaver
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WPA3 Encryption Cracking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WEP Cracking and WPA Brute Forcing Using Wesside-ng and Fern Wifi Cracker
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Hacking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WEP/WPA/WPA2 Cracking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WEP/WPA/WPA2 Cracking Tools for Mobile
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Packet Sniffers
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Traffic Analyzer Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WarDriving Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### RF Monitoring Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Raw Packet Capturing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Spectrum Analyzing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluetooth Hacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluetooth Stack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluetooth Hacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluetooth Threats
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluejacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluetooth Reconnaissance Using BlueZ
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Btlejacking Using BtleJack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluetooth Hacking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Security Layers
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Defense Against WPA/WPA2/WPA3 Cracking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Defense Against KRACK Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Defense Against aLTEr Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Detection and Blocking of Rogue APs
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Defense Against Wireless Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Defense Against Bluetooth Hacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Security Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wireless Intrusion Prevention Systems
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### WIPS Deployment
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Security Auditing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi IPSs
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Predictive Planning Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Vulnerability Scanning Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bluetooth Security Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Wi-Fi Security Tools for Mobile
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Summary
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 


## Module 17 - Hacking Mobile Platforms
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Objectives
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Platform Attack Vectors
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Vulnerable Areas in Mobile Business Environment
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Platform Attack Vectors
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OWASP Top 10 Mobile Risks - 2016
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Anatomy of a Mobile Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### How a Hacker can Profit from Mobile Devices that are Successfully Compromised
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Attack Vectors and Mobile Platform Vulnerabilities
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Security Issues Arising from App Stores
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### App Sandboxing Issues
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Spam
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SMS Phishing Attack (SMiShing) (Targeted Attack Scan)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SMS Phishing Attack Examples
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Pairing Mobile Devices on Open Bluetooth and Wi-Fi Connections
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Agent Smith Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Exploiting SS7 Vulnerability
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Simjacker: SIM Card Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking Android OS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android OS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Device Administration API
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Rooting
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Rooting Android Using KingoRoot
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Rooting Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking Android Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Blocking Wi-Fi Access Using NetCut
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Identifying Attack Surfaces Using drozer
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking with zANTI and Network Spoofer
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Launch DoS Attack using Low Orbit Ion Cannon (LOIC)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Session Hijacking Using DroidSheep
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking with Orbot Proxy
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Exploiting Android Device through ADB Using PhoneSploit
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android-based Sniffers
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Launching Man-in-the-Disk Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Launching Spearphone Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Other Techniques for Hacking Android Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Trojans
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Hacking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Securing Android Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Security Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Security Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Device Tracking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Android Vulnerability Scanners
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Online Android Analyzers
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking iOS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Apple iOS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Jailbreaking iOS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Jailbreaking Techniques
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Jailbreaking iOS 13.2 Using Cydia
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Jailbreaking iOS 13.2 Using Hexxa Plus
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking using Spyzie
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking Network using Network Analyzer Pro
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### iOS Trustjacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### iOS Malware
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### iOS Hacking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Securing iOS Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### iOS Device Security Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### iOS Device Tracking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Device Management
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Device Management (MDM)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Device Management Solutions
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Bring Your Own Device (BYOD)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### BYOD Risks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### BYOD Policy Implementation
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### BYOD Security Guidelines
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Security Guidelines and Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OWASP Top 10 Mobile Controls
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### General Guidelines for Mobile Platform Security
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Device Security Guidelines for Administrator
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SMS Phishing Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Reverse Engineering Mobile Applications
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Security Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Source Code Analysis Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Reverse Engineering Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### App Repackaging Detector
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Protection Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Anti-Spyware
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Mobile Pen Testing Toolkit
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Summary
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 


## Module 18 - IoT and OT Hacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Module Objectives
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Hacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Concepts
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### What is the IoT?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### How the IoT Works
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Architecture
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Application Areas and Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Technologies and Protocols
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Communication Models
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Challenges of IoT
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Threat vs Opportunity
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Security Problems
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OWASP Top 10 IoT Threats
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Vulnerabilities
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Threats
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking IoT Devices: General Scenario
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### DDoS Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Exploit HVAC
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Rolling Code Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### BlueBorne Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Jamming Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Hacking Smart Grid/Industrial Devices: Remote Access using Backdoor
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### SDR-Based Attacks on IoT
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Identifying and Accessing Local IoT Devices
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Fault Injection Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Other IoT Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Attacks in Different Sectors
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Case Study: Dyn Attack
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Hacking Methodology
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### What is IoT Device Hacking?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Hacking Methodology
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Hacking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Information-Gathering Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Sniffing Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Vulnerability-Scanning Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Tools to Perform SDR-Based Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Hacking Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Countermeasures
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### How to Defend Against IoT Hacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### General Guidelines for IoT Device Manufacturing Companies
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OWASP Top 10 IoT Vulnerabilities Solutions
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Framework Security Considerations
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Device Management
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IoT Security Tools
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OT Hacking
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OT Concepts
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### What is OT?
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Essential Terminology
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### IT/OT Convergence (IIOT)
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### The Purdue Model
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Challenges of OT
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Introduction to ICS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### Components of an ICS
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OT Technologies and Protocols
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OT Attacks
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OT Vulnerabilities
-
    - 
        - 
    - 
        - 
-
    - 
        - 
    - 
        - 

### OT Threats
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### HMI-based Attacks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Side-Channel Attacks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Hacking Programmable Logic Controller (PLC)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Hacking Industrial Systems through RF Remote Controllers
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Malware
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Malware Analysis: LockerGoga Ransomware
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Hacking Methodology
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### What is OT Hacking?
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Hacking Methodology
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Hacking Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Information-Gathering Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Sniffing and Vulnerability-Scanning Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Hacking Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Countermeasures
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### How to Defend Against OT Hacking
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Vulnerabilities and Solutions
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### How to Secure an IT/OT Environment
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### International OT Security Organizations
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Security Solutions
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OT Security Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Module Summary
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -



## Module 19 - Cloud Computing
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Module Objectives
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Computing Concepts
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Introduction to Cloud Computing
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Types of Cloud Computing Services
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Separation of Responsibilities in Cloud
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Deployment Models
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### NIST Cloud Deployment Reference Architecture
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Storage Architecture
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Role of AI in Cloud Computing
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Virtual Reality and Augmented Reality on Cloud
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Service Providers
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Container Technology
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### What is a Container?
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Containers Vs. Virtual Machines
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### What is Docker?
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Microservices Vs. Docker
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Docker Networking
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Container Orchestration
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### What is Kubernetes?
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Kubernetes Vs. Docker
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Container Security Challenges
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Container Management Platforms
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Kubernetes Platforms
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Serverless Computing
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### What is Serverless Computing?
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Serverless Vs. Containers
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Serverless Computing Frameworks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Computing Threats
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OWASP Top 10 Cloud Security Risks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### OWASP Top 10 Serverless Security Risks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Computing Threats
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Container Vulnerabilities
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Kubernetes Vulnerabilities
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Service Hijacking using Social Engineering
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Service Hijacking using Network Sniffing
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Side-Channel Attacks or Cross-guest VM Breaches
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Wrapping Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Man-in-the-Cloud (MITC) Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Hopper Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Cryptojacking
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloudborne Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Other Cloud Attacks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Hacking
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### What is Cloud Hacking?
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Container Vulnerability Scanning using Trivy
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Kubernetes Vulnerability Scanning using Sysdig
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Enumerating S3 Buckets
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Identifying Open S3 Buckets using S3Scanner
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Enumerating Kubernetes etcd
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Enumerating AWS Account IDs
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Enumerating IAM Roles
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Enumerating Bucket Permissions using S3Inspector
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Exploiting Amazon Cloud Infrastructure using Nimbostratus
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Exploiting Misconfigured AWS S3 Buckets
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Compromising AWS IAM Credentials
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Hijacking Misconfigured IAM Roles using Pacu
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cracking AWS Access Keys using DumpsterDiver
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Exploiting Docker Containers on AWS using Cloud Container Attack Tool (CCAT)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Exploiting Docker Remote API
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Hacking Container Volumes
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### CloudGoat AWS – Vulnerable by Design
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Gaining Access by Exploiting SSRF Vulnerabilities
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### AWS IAM Privilege Escalation Techniques
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Escalating Privileges of Google Storage Buckets using GCPBucketBrute
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Backdooring Docker Images using dockerscan
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Maintaining Access and Covering Tracks on AWS Cloud Environment by Manipulating the CloudTrial Servi
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### AWS Hacking Tool: AWS pwn
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Security
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Security Control Layers
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Security is the Responsibility of both Cloud Provider and Consumer
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Computing Security Considerations
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Placement of Security Controls in the Cloud
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Best Practices for Securing the Cloud
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### NIST Recommendations for Cloud Security
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Kubernetes Vulnerabilities and Solutions
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Serverless Security Risks and Solutions
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Best Practices for Container Security
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Best Practices for Docker Security
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Best Practices for Kubernetes Security
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Best Practices for Serverless Security
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Zero Trust Networks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Organization/Provider Cloud Security Compliance Checklist
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### International Cloud Security Organizations
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cloud Security Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Container Security Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Kubernetes Security Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Serverless Application Security Solutions
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Module Summary
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -



## Module 20 - Cryptography
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Module Objectives
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptography Concepts
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptography
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Government Access to Keys (GAK)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Encryption Algorithms
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Ciphers
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Data Encryption Standard (DES)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Triple Data Encryption Standard (3DES)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Advanced Encryption Standard (AES)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### RC4, RC5, and RC6 Algorithms
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Blowfish
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Twofish
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Threefish
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Serpent
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### TEA
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### CAST-128
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### GOST Block Cipher
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Camellia
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### DSA and Related Signature Schemes
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Rivest Shamir Adleman (RSA)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Diffie–Hellman
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### YAK
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Message Digest (One-way Hash) Functions
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### CHAP
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### EAP
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### GOST – Hash Function
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Message Digest Function: MD5 and MD6
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Message Digest Function: Secure Hashing Algorithm (SHA)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### RIPEMD-160
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### HMAC
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Other Encryption Techniques
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Comparison of Cryptographic Algorithms
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptography Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### MD5 and MD6 Hash Calculators
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Hash Calculators for Mobile
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptography Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptography Tools for Mobile
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Public Key Infrastructure (PKI)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Certification Authorities
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Signed Certificate (CA) vs. Self-Signed Certificate
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Email Encryption
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Digital Signature
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Secure Sockets Layer (SSL)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Transport Layer Security (TLS)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptography Toolkits
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Pretty Good Privacy (PGP)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### GNU Privacy Guard (GPG)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Web of Trust (WOT)
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Email Encryption Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Disk Encryption
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Disk Encryption Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptanalysis
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptanalysis Methods
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Code Breaking Methodologies
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptography Attacks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Brute-Force Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Birthday Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Birthday Paradox: Probability
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Meet-in-the-Middle Attack on Digital Signature Schemes
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Side-Channel Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Hash Collision Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### DUHK Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Rainbow Table Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Related-Key Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Padding Oracle Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### DROWN Attack
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Cryptanalysis Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Online MD5 Decryption Tools
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Countermeasures
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### How to Defend Against Cryptographic Attacks
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -


### Key Stretching
-
    -
        -
    -
        -
-
    -
        -
    -
        -
-
    -
        -
    -
        -
