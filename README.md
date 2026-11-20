# RAM MASTER - Windows Memory Forensics

**ALPHA RELEASE |RAM MASTER - Python 3 Windows Memory Forensics Command Centre**

<p align="center">
  <img src="https://github.com/BroadbentT/RAM-MASTER/blob/main/Windows%20Memory%20Forensics.png" alt="RAM MASTER – Windows Memory Forensics" width="100%">
</p>

## INSTALLATION

Clone the repository:

```bash
git clone https://github.com/BroadbentT/RAM-MASTER.git
cd RAM-MASTER
```

Install the required Python package:

```bash
pip install virustotal3
```

## VIRUSTOTAL API KEY

RAM MASTER supports VirusTotal integration.

An API key can be obtained by registering at:

https://www.virustotal.com/gui/join-us

Configure your API key as required by the application.

---

## PROJECT OVERVIEW

### COMMAND CENTRE – WINDOWS MEMORY FORENSICS

RAM MASTER is a Python 3 command-centre application designed to forensically investigate and analyse Microsoft Windows memory dump files using the Volatility Framework.

**Usage:**

```bash
python3 RamMaster.py
```

### PROJECT FILES

| Language | Filename | MD5 Hash | Description | Version |
|---|---|---|---|---|
| Python 3 | `RamMaster.py` | `e2afa7abea10422275349e2d7bdf108f` | Command Centre | Forensic |
| Text | `profiles.txt` | `380d793d31c90a09aae417b16cbaff22` | Windows Profiles | Forensic |

### FORENSIC CAPABILITIES

RAM MASTER provides forensic examination capabilities including:

- User account and username extraction.
- Password hash extraction.
- PCAP network capture extraction.
- System executable extraction.
- Master File Table (MFT) analysis.
- Console keystroke recovery.
- Screenshot recovery.
- Additional Windows memory artefact analysis.

### VOLATILITY FRAMEWORK

- [x] Uses and self-installs Linux Volatility 2.6.
- [x] Supports Windows memory dump investigations.

Volatility 2.6:

https://www.volatilityfoundation.org/26

### SAMPLE MEMORY DUMPS

Sample memory dump files are available from:

- https://github.com/volatilityfoundation/volatility/wiki/Memory-Samples
- http://downloads.digitalcorpora.org/corpora/scenarios/2009-m57-patents/ram/

---

## CONSOLE DISPLAY AND VIDEO DEMONSTRATION

<p align="center">
  <a href="https://youtu.be/JwJidOB__v0">
    <img src="https://github.com/BroadbentT/RAM-MASTER/blob/main/picture3.png" alt="RAM MASTER Console Demonstration" width="85%">
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/JwJidOB__v0">Watch the RAM MASTER demonstration on YouTube</a>
</p>

---

## LEGAL DISCLAIMER

### COMPUTER MISUSE ACT 1990 – SECTION 3A

This software has been specifically developed for legitimate digital forensic investigation, authorised security research and penetration testing.

It must not be used for unauthorised access, unlawful surveillance, malicious activity or any other purpose contrary to applicable law.

The user is responsible for ensuring that all investigations are conducted with appropriate authorisation.

---

## SUPPORT THE PROJECT

Found RAM MASTER useful, or would like to buy the developer a coffee?

Donations are appreciated:

https://paypal.me/TerenceBroadbent

---

**RAM MASTER (ALPHA) – Windows Memory Forensics | Python 3 | Volatility Framework**
