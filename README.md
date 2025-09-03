# GRC
This blog features all my notes regarding Governance Risk and Compliance while studying Cyber Security at KEA .

### Unintended threats

- Power Failure
- Fire Hazards
- Wheather (Earthquake, floods and storms)


## Hardware

Hardware is expected to be maintained for 5 years, we need one to one equipment as bought, and service level agreements are made of 5 years duration.

## Physical/Power Security / Server Rooms / [Data Center Security](https://en.wikipedia.org/wiki/Data_center_security)

- UPS (battery) always cells are optimized by Electricians (prof.).
- Redundance in power supply. 
- Externally a diesel generator is supporting power.
- UPS also streamlines the voltage and removes peaks and valleys. 
- Metaldoors ensure serverrooms.
- Inactive gas is used to remove O2 (oxygen) from the room.
- Aircondition, to cool down servers.
- Humidity in server rooms need to be present, no zero humidity. Prefered (55 % Humidity).
- 25 degrees celcius is ok temperature to keep down.
- Cooling is not an issue.
- Early warnings alerting on mobile device regardning all instruments, powersupply (GOOD IDEA).
- Remote backup (important) - companies and people were vanished in 9-11 twin tower attack, and remote backups are critical.
- Norway has made atom-bomb safe vaults and backups in the mountains of norway.
- Split operations (2-sites) : remember to mirror eachother (complete redundant), perhaps lower the bandwith. Car security we have airbag and seatbelt.
- Consider wireless connections as backup for internet connections alwyas up.


## Intended threats

- EU, USA, China - are equally enemies in peace time regarding espionage.
- Advanced encryption used in Danish Foreign Affairs (active in the earlier Jugoslavian wars) technologies were being circumvented by backdoors to listen to high ranking politicians.
- Confidential about how we score things, and buy big military equipment, and that when
- Hacktivism -> anonymous, Terrists, Journalish
- Show-off hackers
- Internal / External fraud

 Governments
- Economic spionage
- Intelligence for the sake of National Security
- Investigation by Military or Police
- [Act of war](https://en.wikipedia.org/wiki/Casus_belli)

- USA iraq, one week prior to attack jam all big radiosender, tv's phone communication, to disable Iraq in communication reasonably.
- Jamming at Lolland (Denmark) Kaleningrad. Jam equipment. Russian forces were trying to jam sonars listening (FMI's Dalo Saildrones survailing russians) to cable destroyer in the baltic sea. ([Alexandr Frolov](https://www.marinetraffic.com/en/ais/details/ships/shipid:4937128/mmsi:273542930/imo:0/vessel:ALEKSANDR_FROLOV) ships where jamming) 
- All Airports in denmark are equipted with visual landing systems (manuel landing) . But finland is harder hit with only GPS landing systems.


## Frameworks of defence

- USA has released [Ghidra](https://en.wikipedia.org/wiki/Ghidra) free NSA tool for reverse engineering and Kali.
- Ransomeware attacks are handlede by the attacker as a "Business".
- Industry of attack on the Dark Web.
- Surveilance 5 (Common wealth) - 9 (Denmark included) - 14 eyes (Sweden Germany)
- Denmark has been critised by [XKeyscore](https://en.wikipedia.org/wiki/XKeyscore) cable working together with the 9 eyes countries.
- Russian has [TOBOL GPS](https://www.gpsworld.com/russian-electronic-warfare-base-linked-to-gps-jamming-across-baltic-region/) jamming tools for targeted GPS jamming attacks Kaliningrad.
- [Stuxnet](https://en.wikipedia.org/wiki/Stuxnet) 
- Difficult to ensure no spys in hiren in big organisations.


## Exercise: Examine Exploits

### What's [CaddyWiper](https://attack.mitre.org/software/S0693/)?

-  "is a destructive data wiper that has been used in attacks against organizations in Ukraine since at least March 2022."
-  [Data Destruction](https://blog.talosintelligence.com/threat-advisory-caddywiper/)
- [ Disk Wipe: Disk Structure Wipe ](https://www.welivesecurity.com/2022/03/15/caddywiper-new-wiper-malware-discovered-ukraine/)
-  [File and Directory Discovery](https://www.threatdown.com/blog/double-header-isaacwiper-and-caddywiper/)
-  [File and Directory Permissions Modification: Windows File and Directory Permissions Modification ](https://blog.talosintelligence.com/threat-advisory-caddywiper/)

-  [Campaings](https://cloud.google.com/blog/topics/threat-intelligence/sandworm-disrupts-power-ukraine-operational-technology/)


### [Triple Fantasy](https://www.colocationamerica.com/blog/kaspersky-uncovers-equation-group)

###### APT
Exploits the cache when the HDD read write operations stored in the RAM (for speed up pupose). Linux system handles in the HDD the control of the cache. The SYSTEM was compromised, and can compromise the HDD even though the OS has been wiped, and cannot be inspected without physical acess to the HDD bios. Kaspersky discovered this since they wiped the systems and they still were communicating with the internet in their lab. 

One of the most serious and advanced persistent threats in modern history.
 

###### We have to assume breach 

### Attack Surfaces




#### Stegosploit

Embedded picture with malware.


# ISO27001 & ISO27002 

###### Change management is hard

When hired for it-security we will find change management and implementing the more secure practices as the hardest part of the job, which is often the standard job when hired from college/ junior cyber security governance employee. 

C-Suit, leaders are "busy" and often hard to get to listen. 

We cannot implement the technologies alone, we have to orchestrate cross diciplinary (HR, IT, Operations, Leaders at all levels). 

## ISO27001 & 2 Ongoing Identifcation: 

- Assets
  
- Vulnerabilties

How exposed am i?
  
- Threats

How likely am i to be attacked?
  
- Internal organization
  
- Central Documents
  
- Risks

## Relevant links for Governance Focus (DK)

- [Attack Mitre](https://attack.mitre.org)
- [Digitaliseringsstyrelsen](https://digst.dk)
- [Erhvervsstyrelsen](https://erhvervsstyrelsen.dk)
- [Datatilsynet](https://www.datatilsynet.dk)
- [Dansk Standard](https://www.ds.dk/da?utm_source=Google&utm_medium=cpc&utm_campaign=Brand&gad_source=1&gad_campaignid=328242370&gbraid=0AAAAADqzrM6erMjkvFFZ-KyU7UtG_V-yg&gclid=Cj0KCQjwzt_FBhCEARIsAJGFWVmfQC1sjxFkWtJungS1dDmlpafymOqb6KGRI4p93DSRGpz2hTnlfCsaAtYVEALw_wcB)
- [CFCS](https://www.cfcs.dk/en/about-us/cert/)
- [CERT](https://sektorcert.dk)
- [OWASP](https://owasp.org)


# OSINT ( Open Source Intelligence)

- Authoriy
- Accuracy
- Obejctivity
- Coverage
- Validity


# Case : Rigspolitiet / national police hacked

##### Under attack : Rigspolitiet / Systems of [CSC](https://da.wikipedia.org/wiki/Computer_Sciences_Corporation) (USA software-system developer) | Dansih Driver Licenses and shared EU-System for wanted persons and ID-papers (1,2 million) [SCHENGEN INFORMATION SYSTEMS](https://www.computerworld.dk/art/234507/det-store-csc-hack-datatilsynet-klar-med-haard-kritik-af-rigspolitiet) 

##### Security measures were low 

##### Who is attacking? : Pirate Bay co-founder colaborated  un-known Østerbro (Dansish) guy 

##### Confidentiality [High-Impact] 

 - Breach in the security and disclosure of 1,2 millions records of PII.
   
##### Integrity  [High-Impact] 

 - IDS was not logging and active
   
 - No seperations and compartmentalisation of data-controllers system and data processor services. CSC systems mainframe partitioned and used for storing Rigspolitiets data.
 - Mainframe not isolated from the internet
 - [LPAR](https://en.wikipedia.org/wiki/Logical_partition) access to open to the internet and open to another datacontrollers operational needs. 
 - network security was designed at the needs of the dataprocessor and not data controller.
 - Containment of Schengen informationssytem data stored after processed and not needed any longer.


###### Ensure all orders [evidence](https://en.wikipedia.org/wiki/Evidence_(law))  everything signed 

### ISO27001 First Move

Organisation is an organism. The size of organisation is growing and complexity is rising and maturity in the it leadership is often too low. 

##### Who is responsible? 

Firstly we must, as IT-professional, throw the ball to the CEO (in a well communicated manner towards our own boss). 

We need the buy-in from the CEO, to get the authority to communicate to other employees the authority. 

##### Make a Security Commitee

Key stakeholders in the company must be assembled to point out and describe the most effective policies.

##### Tasks of Security Commitee
- Guidelines for making policies
- Develop guidlines and rules for Risk Assesments for current and future systems.
- Employee security to protect against employees.
- Asset management and classification (electronic, spoken, paper).
-  #### Annual Wheel, meetings, reports and action plans

##### Organizational employees of IT-Security

- ###### Information Security Commitee
- ###### IT-Security Manager
- Data Manager
- Opertion Manager
- Network Manager
- DPO


#### [Statement of Applicability](https://www.ds.dk/media/dy1bzsbs/foss-statement-of-applicability-public.pdf?srsltid=AfmBOorYIZMcnjc84qyaQGkoJMXYob20dIoepjH75fwqpo4QZE6ICpZf)

Annex A of [ISO27001 [Strategic]](https://en.wikipedia.org/wiki/ISO/IEC_27001) -> more specific in [ISO27002 [Tactical]](https://en.wikipedia.org/wiki/ISO/IEC_27002)

- Legal Requirements can adjust controls to higher level of security/necessity.
- Must always write why not control has been applied.
- [SoA](https://www.ds.dk/media/dy1bzsbs/foss-statement-of-applicability-public.pdf?srsltid=AfmBOorYIZMcnjc84qyaQGkoJMXYob20dIoepjH75fwqpo4QZE6ICpZf) enables
- [Asset list](https://www.imperial.ac.uk/media/imperial-college/institute-of-global-health-innovation/centre-for-health-policy/BDAU-SE-ISO-27001-Handbook-20240521-Public.pdf) - find BDAU SE Asset Registry SOP



### SCOPING ISO27001

ISO27001 [CERTIFIED] - includes - ISO27002 are tighly coupled 

- Risk owner in larger companies
- Management
- Employees
- Operation Responsible
- Network Responsible
- Leaders and Managers
- more

#### Security Policy

- ISMS and the org
- Employee Safety
- Assets and Classification
- Access Control
- Methode for Risk Assesment
- Communication Plan
- Supplier Management
- Development and Test
- Operation Safety
- Perimeter Safety
- Supplier Management
- Security Incidents and IT-Contigency + Incident Response
- Annual Reports

Remember to describe all incident plans. 
How to go from incident back to normal operation. (Remember!)
We need a guide to act reasonable.

###### Rules and Penalty for violating policies!

As security advisors, we can order the manager to fire people, since they get a salary compensation for firing.


#### ISO27002:2022

Newly revised to match Cyber Security & Cloud growing need in ISMS controls. 

- People Controls
- Physical Controls
- Technological Controls (most controls)
- Organisational Controls

Mapping 27002:2013

#### Technological Controls
IMPORTANT MONITORING ## SIEM ## :
- Logging (we need to log) SIEM products analyse logs [Important Controls]. False negative / False positives. SWEET SPOT.


###### 5 Attributes

- Control Types
- Information Security Properties
- Cybersecurity Properties
- Operational Capabilities
- Security Domains


Further controls that could add on to ISO27002 93 controls:
### [GDPR](https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng)
### [AI ACT](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) 
### [DORA](https://www.eiopa.europa.eu/digital-operational-resilience-act-dora_en)
### [NIS2](https://digital-strategy.ec.europa.eu/da/policies/nis2-directive) 

### Important factors for defining policies and ongoing work

- risk analysis - need for more policies
- all 14 controls to analyse need for policies
- control the Asset List: Any system need not covered
- C-suit meeting conrolling need for special policies
- Policy testing

### Align All Policies

- Emergency rules
- Departments have specific rules based on location
- Legislation have rules all must obey prior polocies obeying
- Combine all policies and references in one place to ensure employees stay informed, not miss "must knows".
- 


