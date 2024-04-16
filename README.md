**\*\*\*\* Tools list will be updated frequently \*\*\*\*\***

**CTF Categories:**

**Forensics - Steganography, Digital Forensics**

**Cryptography**

**Web Exploitation**

**OSINT**

**Reverse Engineering**

**Networking**

**\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\*

**Forensic Tools:**

- File format identification (and "magic bytes")
- All of **Eric Zimmermann** Tools (Digital Forensics)
- [**FTK Imager**](https://medium.com/@the_harvester/forensics-with-ftk-imager-f629bd52174d) - It allows us to create perfect copies (or images) of computer disks for analysis, preserving the integrity of the evidence. It also lets us view and analyze the contents of data storage devices without altering the data.
- [**Autopsy**](https://github.com/sleuthkit/autopsy) \- Open-source digital forensics platform used for analyzing disk images, file systems, and various artifacts to uncover evidence in investigations.
- [**Volatility**](https://github.com/volatilityfoundation/volatility) \- Advanced memory forensics framework for analyzing volatile memory (RAM) dumps to extract information about running processes, network connections, and other system activities.
- [**KAPE**](https://github.com/EricZimmerman/KapeFiles) - Command-line tool designed for automating the collection and parsing of digital forensic artifacts from Windows systems, aiding in rapid evidence collection and analysis.
- [**Velociraptor**](https://github.com/Velocidex/velociraptor) - Open-source endpoint visibility and digital forensics platform designed for monitoring and collecting detailed information from endpoints in enterprise environments, enabling threat hunting, incident response, and security monitoring at scale.
- [**MFT Explorer**:](https://ericzimmerman.github.io/#!index.md) A tool used in digital forensics to analyze the Master File Table (MFT) of a Windows NTFS file system, providing insights into file metadata, directory structure, and file system usage for investigative purposes.
- [**Amcache Parser**](https://github.com/EricZimmerman/AmcacheParser) is a specialized tool used in digital forensics to analyze the Amcache.hve registry hive on Windows systems. It extracts information about program execution, including details such as executed binaries, timestamps, and file paths.
- [**Scalpel**](https://github.com/sleuthkit/scalpel) is an open-source forensic tool used for file carving, which is the process of extracting files from disk images or other storage media without relying on file system metadata.
- [**TimeLine Explorer**](https://thesecuritynoob.com/dfir-tools/dfir-tools-timeline-explorer-what-is-it-how-to-use/)\- Used to read CSV files generated from KAPE output.
- [**Registry Explorer**](https://www.sans.org/tools/registry-explorer/) is a digital forensics tool used to navigate and analyze the Windows Registry, assisting in uncovering evidence of malicious activities and system configurations by examining registry entries and tracking changes over time.
- Command Line utility - Command-line utility for parsing and analyzing **Windows Event Log files (EVTX**), allowing forensic investigators and security analysts to extract valuable information such as system events, user activities, and security-related events for incident response and threat hunting purposes.
- [**RegRipper**](https://github.com/keydet89/RegRipper3.0) - Command line tool to analyze registry hives  
    **PECmd (Program Execution)** is a command-line tool commonly utilized in digital forensics and incident response to analyze program execution artifacts on Windows systems. It aids investigators in extracting valuable information regarding executed programs, their associated metadata, timestamps, and execution paths.
- **DeepBlueCLI** It enables cybersecurity professionals to efficiently manage security policies, monitor threat detection, orchestrate incident responses, and perform various security operations directly from the command line interface
- [**Binwalk**](https://github.com/ReFirmLabs/binwalk)\- Binwalk is a command-line tool used for analyzing, extracting, and identifying embedded files within binary data, commonly employed in digital forensics and reverse engineering tasks.
- [**Jsteg**](https://wiki.bi0s.in/steganography/jsteg/) - It is a package for hiding data inside jpeg files
- [**Foremost**](https://github.com/gerryamurphy/Foremost?tab=readme-ov-file) \- Extract particular kind of files using headers
- [**Audacity**](https://sourceforge.net/projects/audacity/) - Analyze sound files (mp3, m4a, whatever)


**\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\*

**Cryptography:**

- [**Cipher Identifier**](https://www.dcode.fr/cipher-identifier) - to identify the cipher
- [**Code chef**](https://gchq.github.io/CyberChef/) \- see “Magic” option (Cipher Decoder)
- [**ROT Cipher/ Caesar Cipher**](https://www.cachesleuth.com/rot.html) **\-** To solve ROT Cipher
- [**Cracking station**](https://crackstation.net/) - Hash decrypter
- [**John the ripper**](https://www.stationx.net/how-to-use-john-the-ripper/)\- John the Ripper is utilized as a tool to find the passwd for dictionary attacks, brute force attacks .
- [**Hash cat**](https://www.kali.org/tools/hashcat/) \- password decrypter
- [**Hash Identifier**](https://github.com/psypanda/hashID) - to find what type of hash
- [**Xor tool**](https://github.com/hellman/xortool) \- A tool to analyze multi-byte xor cipher
- [**RSA tools**](https://www.dcode.fr/rsa-cipher) - To solve RSA cipher
- [**RSActf tool**](https://github.com/RsaCtfTool/RsaCtfTool) \- RSA cipher tool decrypter
- [**Ophcrack**](http://ophcrack.sourceforge.net/) – Windows password cracker based on rainbow tables.

**\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\*


**Web exploitation:**

- [**BurpSuite**](https://github.com/SNGWN/Burp-Suite-Pro) – A graphical tool for testing website security.
- [**Commix**](https://github.com/commixproject/commix) – Automated All-in-One OS Command Injection and Exploitation Tool.
- [**Hackbar**](https://addons.mozilla.org/en-US/firefox/addon/hackbar/) – Firefox addon for easy web exploitation
- [**OWASP ZAP**](https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project) – Intercepting proxy to replay, debug, and fuzz HTTP requests and responses
- [**Postman**](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) – Add on for chrome for debugging network requests
- [**SQLMap**](https://github.com/sqlmapproject/sqlmap) – Automatic SQL injection and database takeover tool
- [**W3af**](https://github.com/andresriancho/w3af) – Web Application Attack and Audit Framework.
- [**XSSer**](http://xsser.sourceforge.net/) – Automated XSS tester


**\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\*

**OSINT:**

- [**Epieos**](https://epieos.com/) - Helps in searching a person's details based on email id or phone number
- [**intelx.io**](https://intelx.io/) \- Used for searching a domain, URL, email, Bitcoin address
- [**whatsmyname.app**](https://whatsmyname.app/) \-Used for searching and gathering social links of a person
- [**haveibeenpwned.com**](https://haveibeenpwned.com/) - Used for checking if an email ID has been breached
- [**urlscan.io**](https://urlscan.io/) - Used for knowing details about a URL
- [**osintframework.com**](https://osintframework.com/) - Used for knowing about the OSINT approach of a target
- [**whois.com**](https://www.whois.com/) \- Used for knowing about IP address, domain name
- [**builtwith.com**](https://builtwith.com/) - Used for knowing about the tech stack used for a website
- [**web.archive.org**](http://web.archive.org/) - Used for checking if any archives of a URL is present
- [**exploit-db**](https://www.exploit-db.com/) - Used for knowing about the vulnerabilities along with the CVE ID
- [**wappalyzer.com**](https://www.wappalyzer.com/) - Used for finding technology of a website
- [**crunchbase.com**](https://www.crunchbase.com/) - Used for finding details about an organization and its employees
- [**viewdns.info/reversewhois**](https://viewdns.info/reversewhois/) - Used for finding DNS Info about a domain
- [**justgetmydata.com**](https://justgetmydata.com/) - Used for finding maximum possible details about in different websites
- [**cybdetective.com/osintmap**](https://cybdetective.com/osintmap/) - An OSINT Global Map for finding Governmental Details
- [**namechk.com**](https://namechk.com/) - For checking a Name in over 30 domains and 90 social media accounts
- [**checkusernames.com**](https://checkusernames.com/) - Used for checking a username or brand over 160 social media accounts
- [**thelawpages**](https://www.thelawpages.com/court-cases/court-case-search.php?mode=1)\- Law Records of the UK Government
- [**blackbird-osint.herokuapp.com**](https://blackbird-osint.herokuapp.com/) \- Used for finding out social media accounts with username
- [**meertens**](https://www.meertens.knaw.nl/nvb/naam/is/Giancarlo) -Dutch Name Database
- [**scb.se/hitta-statistik**](https://scb.se/hitta-statistik/sverige-i-siffror/namnsok/) - Sweden Name Database
- [**emailrep.io**](https://emailrep.io/) - Website for checking reputation of a email address
- [**numberway**](https://sur.ly/o/numberway.com/AA000014) - Reverse Phone Number Lookup
- [**192.**](http://www.192.com/) - Used for searching people, business and places in the UK
- [**personlookup**](https://personlookup.co.za/) - South Africa People & Phone Number Database
- [**fastpeoplesearc**h](http://fastpeoplesearch.com/) - Database of people in USA


**\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\*

**Reverse Engineering:**

- [**Ghidra**](https://github.com/NationalSecurityAgency/ghidra) **-** Ghidra is a free and open source reverse engineering tool
- [**Androguard**](https://github.com/androguard/androguard) **-** It is a full python tool to play with android files
- [**Apktool**](https://github.com/iBotPeaches/Apktool) - It is another reverse engineering tool to decompile Android APKs.
- [**BinUtils**](http://www.gnu.org/software/binutils/binutils.html) - The GNU Binary Utilities, or Binutils, are a set of programming tools for creating and managing binary programs, object files, libraries, profile data, and assembly source code.
- [**GDB**](https://www.gnu.org/software/gdb/) **-** GDB, the GNU Project debugger, allows you to see what is going on ‘inside’ another program while it executes
- [**IDA Pro**](https://www.hex-rays.com/products/ida/) \- IDA is a Windows, Linux or Mac OS X hosted multi-processor disassembler and debugger that offers so many features.
- [**Detox**](https://github.com/svent/jsdetox) - Detox is the most popular JS malware analysis tool which works on most Linux distributions. The development is currently done on Linux with the latest chrome browser.


**\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\***\*\*\*\*

**Networking :**

- [**Wireshark**](https://www.wireshark.org/) is a popular open-source network protocol analyzer
- [**Nmap**](https://github.com/nmap/nmap) Nmap is a network scanning tool
- [**Shodan**](https://www.shodan.io/) Shodan is a search engine designed to map and gather information about internet-connected devices and systems.
- [**Zmap**](https://zmap.io/) ZMap is a free, open-source network scanner that can be used for information security research.
- [**DNS lookup**](https://www.nslookup.io/) to look up about domain names and their history
- [**Who is**](https://www.whois.com/whois/) to find about history of some Ip address or domain name
