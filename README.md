# Splunk TA For SecOnion Hunting


## Requirements & Recommendations:
### Requirements:
- **TA For Zeek**
  - https://splunkbase.splunk.com/app/5466
- **Datamodels Must Be Configured To Your Indexes/Sourcetypes & Accelerated **
  - _Does Not Apply When MA-SecOnion Is Utilized w/ Recommended Inputs.conf_
    
### Recommendations: 
- **Splunk App For Lookup File Editing**
  - https://splunkbase.splunk.com/app/1724
- **MA-SecOnion**
  - https://github.com/GregKeil/Inputs-For-Splunk-UF/tree/main/SecOnion


## Other Notes:
### Usage Notes
- **Known_Scanners.csv**
  - When changes are made to the Known_Scanners.csv (Utilized To Filter Scanners Out), The Zeek_Suite & Suricata_Suite datamodels must be rebuilt
- **IOC Integration**
  - Changes can be made freely without the need to modify anything else & will apply immediately
  - Available IOC Lookup Files:
    - _Domain_iocs.csv_
    - _IP_iocs.csv_
    - _MD5_iocs.csv_
    - _URL_iocs.csv_

   
## Upcoming Additions:
### Dashboards
- Zeek HTTP Overview
- Zeek SMB Overview
- Zeek DNS Overview

### Functionality:
- Identifying Any Flaws In Current Version
