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

Add navigation collection:

1. In ES, navigate to Configure > General > Navigation.
1. Click "Add a New Collection."
1. Select "Add existing."
1. Select SA-zTsAutobahn for the app.
1. Add the desired collection to the navigation and click save.