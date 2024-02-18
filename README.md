# SA-zTsAutobahn

Bootstrap configurations for a Splunk ES Autobahn.

## Current configurations

### Workflow Actions

Name | Description
---- | -----------
zts_wfa_virustotal | VirusTotal reputation for IP/File.
zts_wfa_xforce_file | IBM X-Force reputation for files.
zts_wfa_xforce_ip | IBM X-Force reputation for IPs.

### Navigation collection for ES

*Required Apps*

- [SA-investigator](https://splunkbase.splunk.com/app/3749)
- [InfoSec](https://splunkbase.splunk.com/app/4240)
- [SA-Detection Insights](https://splunkbase.splunk.com/app/7066)
- [Status Indicator](https://splunkbase.splunk.com/app/3119)
- [MITRE ATT&CK Heatmap](https://splunkbase.splunk.com/app/5742)
- [Sunburst Viz](https://splunkbase.splunk.com/app/4550)
- [Event Timeline Viz](https://splunkbase.splunk.com/app/4370)
- [Calendar Heat Map](https://splunkbase.splunk.com/app/3162)

*Required Image for "Autobahn Content Overview" dashboard*
[https://www.svgrepo.com/svg/406129/magnifying-glass-tilted-left](https://www.svgrepo.com/svg/406129/magnifying-glass-tilted-left)

Add navigation collection:

1. In ES, navigate to Configure > General > Navigation.
2. Click "Add a New Collection."
3. Select "Add existing."
4. Select SA-zTsAutobahn for the app.
5. Add the desired collection to the navigation and click save.