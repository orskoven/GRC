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

##### Authoriy
##### Accuracy
##### Obejctivity
##### Coverage
##### Validity
