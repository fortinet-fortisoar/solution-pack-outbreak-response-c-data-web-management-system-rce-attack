# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard labs observed a critical level of attack attempts in the wild targeting a 2 year old vulnerability found on C-DATA Web Management Systems. 

 The **Outbreak Response - C-DATA Web Management System RCE Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.1.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/c-data-rce-attack) contains information about the outbreak alert **Outbreak Response - C-DATA Web Management System RCE Attack**. 

## Background: 

The vulnerability CVE-2022-4257, allows a remote attacker to execute arbitrary shell commands on the target system. A remote unauthenticated attacker can send a specially crafted HTTP POST request to the application and execute arbitrary OS commands on the target system. The exploit has been available publically and as of now, we are not aware of any patches available from the vendor. 

## Announced: 

 

## Latest Developments: 

25 April, 2024: FortiGuard labs observed and blocked attack attempts on 40,000+ unique IPS devices in the week of the release of this outbreak. The majority of the blocked attacks are from IPS devices located in Japan, the United States, and Australia respectively.    

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|