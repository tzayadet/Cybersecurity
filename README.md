# Cybersecurity Research & Tooling

Repositorio de trabajo y documentación técnica sobre ciberseguridad ofensiva y defensiva. Reúne scripts propios, automatizaciones, manuales de herramientas, material de laboratorio, recursos de CTF y notas de análisis.

**Es un archivo de investigación y aprendizaje con proyectos de distinta madurez. No todos los scripts están mantenidos, probados ni preparados para producción.**

## Áreas de trabajo

### Reconocimiento y análisis de red
- `AutoNmap.py`, `NmapAutoZya.py`, `NmapAutoZya1.1.sh`
- `AutoRecon.sh`, `BannerGrabber.sh`, `PortScannerZ1.1.py`
- Manuales de Amass, Nmap, Recon-ng y TheHarvester.

### Seguridad web y evaluación de vulnerabilidades
- `SQLiZHunter.py`, `DirectoryFuzzer.sh`, `HTTPHeaderChecker.sh`
- Manuales de Burp Suite, Acunetix, Nikto, OpenVAS, Nessus y SQLmap.
- `OWASP_WSTG_Checklist.xlsx`: checklist de pruebas web.

### SOC, análisis y forense
- `SOCUtilities.py`, `SOCSetupKali.py`, `LogAnlZ.py`
- `MetadataExtZ.py`, `SnifferScapyZ.py`
- Manuales de Wireshark, Zeek y OSQuery.

### Identidad, sistemas y laboratorio
- Documentación de BloodHound, Impacket, CrackMapExec, Responder y Mimikatz.
- Material de laboratorio sobre Active Directory y hardening.
- Scripts de automatización para entornos controlados.

### CTF y formación
- `DocumentarCTF.py`, `GuiaCTF.py`, `GuiaCTFMejorada.py`
- `TrainingPlan.txt`, `ZSeries_TrainingPlan.txt`
- `TryHackMe_FreePath.txt`, `Hacknet_Manual.md`
- Directorios `cheatsheets/`, `guides-phases/`, `scripts-tools/` y `study-plans/`.

## Uso responsable y seguridad

Este repositorio contiene material de doble uso. Algunos scripts y manuales están relacionados con escaneo, auditoría de credenciales, explotación, acceso remoto o simulación de actividad ofensiva.

- Ejecuta herramientas únicamente en sistemas propios, laboratorios aislados o activos para los que tengas autorización explícita.
- Revisa el código, sus dependencias y sus efectos antes de ejecutarlo.
- No utilices credenciales reales ni datos de terceros en pruebas.
- No expongas servicios de laboratorio a redes públicas.
- Los ejemplos no sustituyen procedimientos de seguridad, revisión legal ni controles operativos.
- Trata los resultados de las herramientas como datos que requieren validación; no como evidencia concluyente por sí solos.

## Calidad y mantenimiento

El repositorio ha crecido como archivo de trabajo y conserva duplicados, versiones históricas y utilidades experimentales. Antes de considerar un script reutilizable, conviene revisar:

1. Dependencias y versiones.
2. Manejo de errores y validación de entradas.
3. Permisos y alcance de red.
4. Registro de actividad y tratamiento de datos.
5. Pruebas reproducibles y documentación específica.

## Licencia

Consulta [LICENSE](LICENSE). La licencia del repositorio no concede autorización para probar herramientas contra sistemas ajenos ni sustituye las condiciones de uso de herramientas externas.


## Project showcase

[Open the Cybersecurity Research showcase](https://tzayadet.github.io/Cybersecurity/) · [Showcase source](docs/index.html)

The page is a curated index of selected scripts and reference material. It does not execute tools or provide remote scanning functionality. GitHub Pages deployment is defined in `.github/workflows/pages.yml`; enable Pages with GitHub Actions in repository settings before the first deployment.
