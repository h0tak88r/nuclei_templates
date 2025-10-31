# Nuclei Templates Collection

A curated collection of community Nuclei templates for vulnerability scanning and security testing.

## About

[Nuclei](https://github.com/projectdiscovery/nuclei) is a fast and customizable vulnerability scanner based on simple YAML-based templates. This repository aggregates high-quality Nuclei templates from various security researchers and organizations to provide a comprehensive resource for security testing.

## What are Nuclei Templates?

Nuclei templates are YAML files that define how to detect specific vulnerabilities, misconfigurations, or security issues in web applications, APIs, and infrastructure. Each template contains:
- Detection logic
- Severity classification
- References and remediation guidance

## Usage

To use these templates with Nuclei:

```bash
# Install Nuclei
go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest

# Clone this repository
git clone https://github.com/yourusername/nuclei_templates.git
cd nuclei_templates

# Run Nuclei with custom templates
nuclei -u https://example.com -t ./templates/

# Or use specific template directories
nuclei -u https://example.com -t ./templates/cves/
```

## Template Sources

This collection includes templates from the following community contributors:

### General Purpose Templates
- [ayadim/Nuclei-bug-hunter](https://github.com/ayadim/Nuclei-bug-hunter)
- [pikpikcu/nuclei-templates](https://github.com/pikpikcu/nuclei-templates)
- [esetal/nuclei-bb-templates](https://github.com/esetal/nuclei-bb-templates)
- [ARPSyndicate/kenzer-templates](https://github.com/ARPSyndicate/kenzer-templates)
- [medbsq/ncl](https://github.com/medbsq/ncl)
- [notnotnotveg/nuclei-custom-templates](https://github.com/notnotnotveg/nuclei-custom-templates)
- [foulenzer/foulenzer-templates](https://github.com/foulenzer/foulenzer-templates)
- [clarkvoss/Nuclei-Templates](https://github.com/clarkvoss/Nuclei-Templates)
- [z3bd/nuclei-templates](https://github.com/z3bd/nuclei-templates)
- [joanbono/nuclei-templates](https://github.com/joanbono/nuclei-templates)
- [peanuth8r/Nuclei_Templates](https://github.com/peanuth8r/Nuclei_Templates)
- [ree4pwn/my-nuclei-templates](https://github.com/ree4pwn/my-nuclei-templates)
- [im403/nuclei-temp](https://github.com/im403/nuclei-temp)
- [geeknik/nuclei-templates-1](https://github.com/geeknik/nuclei-templates-1)
- [geeknik/the-nuclei-templates](https://github.com/geeknik/the-nuclei-templates)
- [obreinx/nuceli-templates](https://github.com/obreinx/nuceli-templates)
- [zinminphyo0/KozinTemplates](https://github.com/zinminphyo0/KozinTemplates)
- [n1f2c3/mytemplates](https://github.com/n1f2c3/mytemplates)
- [kabilan1290/templates](https://github.com/kabilan1290/templates)
- [smaranchand/nuclei-templates](https://github.com/smaranchand/nuclei-templates)
- [Saimonkabir/Nuclei-Templates](https://github.com/Saimonkabir/Nuclei-Templates)
- [yavolo/nuclei-templates](https://github.com/yavolo/nuclei-templates)
- [sadnansakin/my-nuclei-templates](https://github.com/sadnansakin/my-nuclei-templates)
- [5cr1pt/templates](https://github.com/5cr1pt/templates)
- [rahulkadavil/nuclei-templates](https://github.com/rahulkadavil/nuclei-templates)
- [Nithissh0708/Custom-Nuclei-Templates](https://github.com/Nithissh0708/Custom-Nuclei-Templates)
- [shifa123/detections](https://github.com/shifa123/detections)
- [daffainfo/my-nuclei-templates](https://github.com/daffainfo/my-nuclei-templates)
- [javaongsan/nuclei-templates](https://github.com/javaongsan/nuclei-templates)
- [AshiqurEmon/nuclei_templates](https://github.com/AshiqurEmon/nuclei_templates.git)
- [ChiaraNRTT96/BountySkill](https://github.com/ChiaraNRTT96/BountySkill)
- [NitinYadav00/My-Nuclei-Templates](https://github.com/NitinYadav00/My-Nuclei-Templates)
- [securitytest3r/nuclei_templates_work](https://github.com/securitytest3r/nuclei_templates_work)
- [MR-pentestGuy/nuclei-templates](https://github.com/MR-pentestGuy/nuclei-templates)
- [thelabda/nuclei-templates](https://github.com/thelabda/nuclei-templates)
- [1in9e/my-nuclei-templates](https://github.com/1in9e/my-nuclei-templates)
- [redteambrasil/nuclei-templates](https://github.com/redteambrasil/nuclei-templates)
- [Saptak9983/Nuclei-Template](https://github.com/Saptak9983/Nuclei-Template)
- [Harish4948/Nuclei-Templates](https://github.com/Harish4948/Nuclei-Templates)
- [R-s0n/Custom_Vuln_Scan_Templates](https://github.com/R-s0n/Custom_Vuln_Scan_Templates)
- [meme-lord/Custom-Nuclei-Templates](https://github.com/meme-lord/Custom-Nuclei-Templates)
- [Akokonunes/Private-Nuclei-Templates](https://github.com/Akokonunes/Private-Nuclei-Templates)
- [rafaelwdornelas/my-nuclei-templates](https://github.com/rafaelwdornelas/my-nuclei-templates)
- [rafaelcaria/Nuclei-Templates](https://github.com/rafaelcaria/Nuclei-Templates)
- [panch0r3d/nuclei-templates](https://github.com/panch0r3d/nuclei-templates)
- [0x727/ObserverWard_0x727](https://github.com/0x727/ObserverWard_0x727)
- [ethicalhackingplayground/erebus-templates](https://github.com/ethicalhackingplayground/erebus-templates)
- [Str1am/my-nuclei-templates](https://github.com/Str1am/my-nuclei-templates)
- [d3sca/Nuclei_Templates](https://github.com/d3sca/Nuclei_Templates)
- [c-sh0/nuclei_templates](https://github.com/c-sh0/nuclei_templates)
- [glyptho/templatesallnuclei](https://github.com/glyptho/templatesallnuclei)
- [0xAwali/Virtual-Host](https://github.com/0xAwali/Virtual-Host)
- [praetorian-inc/chariot-launch-nuclei-templates](https://github.com/praetorian-inc/chariot-launch-nuclei-templates)
- [brinhosa/brinhosa-nuclei-templates](https://github.com/brinhosa/brinhosa-nuclei-templates)
- [wr00t/templates](https://github.com/wr00t/templates)
- [alexrydzak/rydzak-nuclei-templates](https://github.com/alexrydzak/rydzak-nuclei-templates)
- [adampielak/nuclei-templates](https://github.com/adampielak/nuclei-templates)
- [ShangRui-hash/my-nuclei-templates](https://github.com/ShangRui-hash/my-nuclei-templates)
- [dk4trin/templates-nuclei](https://github.com/dk4trin/templates-nuclei)
- [Elsfa7-110/mynuclei-templates](https://github.com/Elsfa7-110/mynuclei-templates)
- [ping-0day/templates](https://github.com/ping-0day/templates)
- [wasp76b/nuclei-templates](https://github.com/wasp76b/nuclei-templates)
- [th3r4id/nuclei-templates](https://github.com/th3r4id/nuclei-templates)
- [themastersunil/Nuclei-TamplatesBackup](https://github.com/themastersunil/Nuclei-TamplatesBackup.git)
- [blazeinfosec/nuclei-templates](https://github.com/blazeinfosec/nuclei-templates)
- [ekinsb/Nuclei-Templates](https://github.com/ekinsb/Nuclei-Templates)
- [KeepHowling/all_freaking_nuclei_templates](https://github.com/KeepHowling/all_freaking_nuclei_templates)
- [Odayex/Random-Nuclei-Templates](https://github.com/Odayex/Random-Nuclei-Templates)
- [themastersunil/nucleiDB](https://github.com/themastersunil/nucleiDB)
- [Linuxinet/nuclei-templates](https://github.com/Linuxinet/nuclei-templates)
- [aels/CVE-2022-37042](https://github.com/aels/CVE-2022-37042)
- [tamimhasan404/Open-Source-Nuclei-Templates-Downloader](https://github.com/tamimhasan404/Open-Source-Nuclei-Templates-Downloader)
- [pentest-dev/Profesional-Nuclei-Templates](https://github.com/pentest-dev/Profesional-Nuclei-Templates)
- [Aituglo/nuclei-templates](https://github.com/Aituglo/nuclei-templates)
- [badboy-sft/badboy_17-Nuclei-Templates-Collection](https://github.com/badboy-sft/badboy_17-Nuclei-Templates-Collection)
- [NightRang3r/misc_nuclei_templates](https://github.com/NightRang3r/misc_nuclei_templates)
- [0XParthJ/Nuclei-Templates](https://github.com/0XParthJ/Nuclei-Templates)
- [trungkay2/Nuclei-template](https://github.com/trungkay2/Nuclei-template)
- [ExpLangcn/NucleiTP](https://github.com/ExpLangcn/NucleiTP)

### Specialized Templates

#### Mobile Security
- [optiv/mobile-nuclei-templates](https://github.com/optiv/mobile-nuclei-templates)

#### SAP Systems
- [randomstr1ng/nuclei-sap-templates](https://github.com/randomstr1ng/nuclei-sap-templates)

#### Kubernetes
- [sharathkramadas/k8s-nuclei-templates](https://github.com/sharathkramadas/k8s-nuclei-templates)

#### Specific Vulnerabilities
- [thebrnwal/Content-Injection-Nuclei-Script](https://github.com/thebrnwal/Content-Injection-Nuclei-Script)
- [System00-Security/backflow](https://github.com/System00-Security/backflow)
- [kh4sh3i/CVE-2022-23131](https://github.com/kh4sh3i/CVE-2022-23131)
- [justmumu/SpringShell](https://github.com/justmumu/SpringShell)

#### Log4j
- [trickest/log4j](https://github.com/trickest/log4j)
- [toramanemre/apache-solr-log4j-CVE-2021-44228](https://github.com/toramanemre/apache-solr-log4j-CVE-2021-44228)
- [toramanemre/log4j-rce-detect-waf-bypass](https://github.com/toramanemre/log4j-rce-detect-waf-bypass)
- [test502git/log4j-fuzz-head-poc](https://github.com/test502git/log4j-fuzz-head-poc)

### Gists
- [ResistanceIsUseless](https://gist.github.com/ResistanceIsUseless/e46848f67706a8aa1205c9d2866bff31)
- [0x240x23elu](https://gist.github.com/0x240x23elu)

## Contributing

Contributions are welcome! If you have custom Nuclei templates or know of other quality template repositories:

1. Fork this repository
2. Add your templates or update the sources list
3. Submit a pull request

Please ensure templates are:
- Well-documented
- Follow Nuclei template best practices
- Include severity ratings
- Have been tested

## Disclaimer

⚠️ **Important**: These templates are for authorized security testing only. Always obtain proper permission before scanning systems you don't own or have explicit authorization to test.

- The maintainers of this repository are not responsible for misuse of these templates
- Use these tools ethically and legally
- Follow responsible disclosure practices

## License

This collection aggregates templates from various sources. Please refer to individual repositories for their specific licenses.

## Resources

- [Nuclei Documentation](https://nuclei.projectdiscovery.io/)
- [Official Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates)
- [Template Writing Guide](https://nuclei.projectdiscovery.io/templating-guide/)
- [Nuclei Discord Community](https://discord.gg/projectdiscovery)

## Acknowledgments

Thanks to all the security researchers and organizations who contribute their templates to the community. Your work helps make the internet more secure.