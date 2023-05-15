<a href="https://www.spiderfoot.net/r.php?u=aHR0cHM6Ly93d3cuc3BpZGVyZm9vdC5uZXQv&s=os_gh"><img src="https://www.spiderfoot.net/wp-content/themes/spiderfoot/img/spiderfoot-wide.png"></a>


[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/smicallef/spiderfoot/master/LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.7+-green)](https://www.python.org)
[![Stable Release](https://img.shields.io/badge/version-4.0-blue.svg)](https://github.com/smicallef/spiderfoot/releases/tag/v4.0)
[![CI status](https://github.com/smicallef/spiderfoot/workflows/Tests/badge.svg)](https://github.com/smicallef/spiderfoot/actions?query=workflow%3A"Tests")
[![Last Commit](https://img.shields.io/github/last-commit/smicallef/spiderfoot)](https://github.com/smicallef/spiderfoot/commits/master)
[![Codecov](https://codecov.io/github/smicallef/spiderfoot/coverage.svg)](https://codecov.io/github/smicallef/spiderfoot)
[![Twitter Follow](https://img.shields.io/twitter/follow/spiderfoot?label=follow&style=social)](https://twitter.com/spiderfoot)
[![Discord](https://img.shields.io/discord/770524432464216074)](https://discord.gg/vyvztrG)

**SpiderFoot** is an open source intelligence (OSINT) automation tool. It integrates with just about every data source available and utilises a range of methods for data analysis, making that data easy to navigate. 

SpiderFoot has an embedded web-server for providing a clean and intuitive web-based interface but can also be used completely via the command-line.  It's written in **Python 3** and **MIT-licensed**.

<img src="https://www.spiderfoot.net/wp-content/uploads/2022/04/opensource-screenshot-v4.png" />

### FEATURES

- Web based UI or CLI
- Over 200 modules (see below)
- Python 3.7+
- YAML-configurable [correlation engine](/correlations/README.md) with [37 pre-defined rules](/correlations)
- CSV/JSON/GEXF export
- API key export/import
- SQLite back-end for custom querying
- Highly configurable
- Fully documented
- Visualisations
- TOR integration for dark web searching
- Dockerfile for Docker-based deployments
- Can call other tools like DNSTwist, Whatweb, Nmap and CMSeeK
- [Actively developed since 2012!](https://medium.com/@micallst/lessons-learned-from-my-10-year-open-source-project-4a4c8c2b4f64)

### WANT MORE?

Need more from SpiderFoot? Check out [SpiderFoot HX](https://www.spiderfoot.net/hx) for:
- 100% Cloud-based and managed for you
- Attack Surface Monitoring with change notifications by email, REST and Slack
- Multiple targets per scan
- Multi-user collaboration
- Authenticated and 2FA
- Investigations
- Customer support
- Third party tools pre-installed & configured
- Drive it with a fully RESTful API
- TOR integration built-in
- Screenshotting
- Bring your own Python SpiderFoot modules
- Feed scan data to Splunk, ElasticSearch and REST endpoints

See the full set of differences between SpiderFoot HX and the open source version [here](https://www.spiderfoot.net/open-source-vs-hx/).

### USES

SpiderFoot can be used offensively (e.g. in a red team exercise or penetration test) for reconnaissance of your target or defensively to gather information about what you or your organisation might have exposed over the Internet.

You can target the following entities in a SpiderFoot scan:

 - IP address
 - Domain/sub-domain name
 - Hostname
 - Network subnet (CIDR)
 - ASN
 - E-mail address
 - Phone number
 - Username
 - Person's name
 - Bitcoin address
 
SpiderFoot's 200+ modules feed each other in a publisher/subscriber model to ensure maximum data extraction to do things like:

- [Host/sub-domain/TLD enumeration/extraction](https://asciinema.org/a/295912)
- [Email address, phone number and human name extraction](https://asciinema.org/a/295947)
- [Bitcoin and Ethereum address extraction](https://asciinema.org/a/295957)
- [Check for susceptibility to sub-domain hijacking](https://asciinema.org/a/344377)
- DNS zone transfers
- [Threat intelligence and Blacklist queries](https://asciinema.org/a/295949)
- API integration with [SHODAN](https://asciinema.org/a/127601), [HaveIBeenPwned](https://asciinema.org/a/128731), [GreyNoise](https://asciinema.org/a/295943), AlienVault, SecurityTrails, etc.
- [Social media account enumeration](https://asciinema.org/a/295923)
- [S3/Azure/Digitalocean bucket enumeration/scraping](https://asciinema.org/a/295941)
- IP geo-location
- Web scraping, web content analysis
- [Image, document and binary file meta data analysis](https://asciinema.org/a/296274)
- Dark web searches
- [Port scanning and banner grabbing](https://asciinema.org/a/295939)
- [Data breach searches](https://asciinema.org/a/296145)
- So much more...

### INSTALLING & RUNNING

To install and run SpiderFoot, you need at least Python 3.7 and a number of Python libraries which you can install with `pip`. We recommend you install a packaged release since master will often have bleeding edge features and modules that aren't fully tested.

#### Kali-linux (packaged release):

```
 sudo apt-get update
```
###### ifconfig CMD for gettinh kali linux ip-add
```
 ifconfig eth0
```
###### copy your kali-linux ip from eth0 and replace below ip add 
```
 sudo spiderfoot -l your-kali-pi:8080
```
###### go back to your host system [windows11/10] open browser and past http://your-kali-ip:8080/ 

### Follow below screenshot
![image](https://github.com/keralahacker/kochi-workshop-09-23/assets/64751167/ff713390-ce8d-4f54-932d-9e0bbf63b382)

#### give a Scan Name and Scan Target [testphp.vulnweb.com]
#### run scan [click the red button]
#### follow below screenshot
![image](https://github.com/keralahacker/kochi-workshop-09-23/assets/64751167/decee411-fc49-4a0e-b4fa-4ba53472e519)

#### 75% of the project...!
