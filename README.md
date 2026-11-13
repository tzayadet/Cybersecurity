<p align="center">
  <img src="https://img.shields.io/badge/SECURITY_RESEARCH-CYBERSECURITY_TOOLKIT-101010?style=for-the-badge&labelColor=050805&color=00FF41" alt="Cybersecurity research toolkit"/>
  <img src="https://img.shields.io/badge/OFFENSIVE_%2F_DEFENSIVE-LAB_RESOURCES-101010?style=for-the-badge&logo=kalilinux&logoColor=00FF41" alt="Security labs"/>
</p>

# Cybersecurity Research & Tooling

Technical workspace covering offensive and defensive cybersecurity. It brings together personal scripts, automation, tool references, lab material, CTF notes and analysis resources.

<p align="center">
  <a href="https://tzayadet.github.io/Cybersecurity/"><strong>LIVE DEMO ↗</strong></a> ·
  <a href="https://github.com/tzayadet/Cybersecurity"><strong>SOURCE CODE</strong></a>
</p>

## Repository map

### Reconnaissance and network analysis

- `AutoNmap.py`, `NmapAutoZya.py`, `NmapAutoZya1.1.sh`
- `AutoRecon.sh`, `BannerGrabber.sh`, `PortScannerZ1.1.py`
- References for Amass, Nmap, Recon-ng and TheHarvester.

### Web security and vulnerability assessment

- `SQLiZHunter.py`, `DirectoryFuzzer.sh`, `HTTPHeaderChecker.sh`
- References for Burp Suite, Acunetix, Nikto, OpenVAS, Nessus and SQLmap.
- `OWASP_WSTG_Checklist.xlsx`: web testing checklist.

### SOC, analysis and forensics

- `SOCUtilities.py`, `SOCSetupKali.py`, `LogAnlZ.py`
- `MetadataExtZ.py`, `SnifferScapyZ.py`
- References for Wireshark, Zeek and OSQuery.

### Identity, systems and lab environments

- References for BloodHound, Impacket, CrackMapExec, Responder and Mimikatz.
- Active Directory lab material and hardening notes.
- Automation scripts for controlled environments.

### CTF and training

- `DocumentarCTF.py`, `GuiaCTF.py`, `GuiaCTFMejorada.py`
- `TrainingPlan.txt`, `ZSeries_TrainingPlan.txt`
- `TryHackMe_FreePath.txt`, `Hacknet_Manual.md`
- Directories: `cheatsheets/`, `guides-phases/`, `scripts-tools/` and `study-plans/`.

## Use and safety

This repository contains dual-use material. Some scripts and notes relate to scanning, credential auditing, exploitation, remote access or offensive activity simulation.

- Run tools only against systems you own, isolated labs or assets for which you have explicit authorisation.
- Review source code, dependencies and side effects before execution.
- Do not use real credentials or third-party data in tests.
- Do not expose lab services to public networks.
- Treat tool output as data requiring validation, not conclusive evidence by itself.

## Maintenance status

This repository has grown as a working archive and retains historical versions, duplicate utilities and experimental scripts. It is not a single installable product and not every item is maintained, tested or production-ready.

Before reusing a script, review dependencies, input validation, error handling, network scope, permissions, logging and reproducible tests.

## Showcase

The [Cybersecurity Research showcase](https://tzayadet.github.io/Cybersecurity/) is a curated index of selected scripts and reference material. It does not execute tools or provide remote scanning functionality. GitHub Pages deployment is defined in `.github/workflows/pages.yml`; enable Pages with GitHub Actions in repository settings before the first deployment.

## License

See [LICENSE](LICENSE). The repository licence does not grant permission to test tools against systems belonging to others or override the terms of third-party tools.
