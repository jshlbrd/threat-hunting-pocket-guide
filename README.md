# Threat Hunting Pocket Guide
## Definition
> Threat hunting is the proactive, iterative search ("hunt") for indications of security incidents that evade existing security mechanisms

(This definition is based on previous work by [David Bianco](https://twitter.com/DavidJBianco))

## Guides
Guides bring focus to how a hunt is carried out
### Intelligence-Driven Hunts
Uses knowledge of adversary behavior (threat intelligence) to guide a hunt<br>
These hunts can be accomplished using specific or generalized adversary tactics, techniques, and procedures (TTPs)
### Anomaly-Driven Hunts
Uses knowledge of abnormal or unexpected behavior (anomalies) to guide a hunt<br>
These hunts can be accomplished using ad hoc (moment in time) or historical (long-term, "baseline") data

## Techniques
Techniques describe methods that can be used to carry out a hunt
### Searching
Uses pattern matching to identify events of interest
### Stacking
Uses key-value counting to identify events of interest
### Visualizations
Uses visualizations, such as box plots and heat maps, to identify events of interest
### Graphs
Uses linked graphs (tree data structures) to identify events of interest
### Machine Learning
Uses machine learning, such as linear regression or random forests, to identify events of interest

## Sources of Data
Sources of data are high-level categorizations of the types of data that can be used on a hunt
### Endpoint
Contains data that describes traits of and actions taken on an endpoint<br>
Examples: process execution, files on-disk, service modification
### File
Contains data that describes traits of and actions taken by a file<br>
Examples: embedded files, static analysis, dynamic analysis
### Network
Contains data that describes traits of and actions taken on a network<br>
Examples: flow records, proxy connections, email messages
### Cloud
Contains data that describes traits of and actions taken on a cloud deployment<br>
Examples: CloudTrail (AWS), Cloud Audit (GCP), Log Analytics (Azure)
### User
Contains data that describes traits of and actions taken by a user<br>
Examples: global address list, authentication events
### Infrastructure
Contains data that describes traits of and actions taken by infrastructure<br>
Examples: open ports/services, DNS resolution, BGP routes
### Application
Contains data that describes traits of and actions taken by an application<br>
Examples: database transactions

## Frameworks
Frameworks are additional resources that can be used to facilitate hunts
### [Hunting Maturity Model](https://www.threathunting.net/files/The%20Threat%20Hunting%20Reference%20Model%20Part%201_%20Measuring%20Hunting%20Maturity%20_%20Sqrrl.pdf)
### [Hunting Loop](https://www.threathunting.net/files/The%20Threat%20Hunting%20Reference%20Model%20Part%202_%20The%20Hunting%20Loop%20_%20Sqrrl.pdf)
### [Cyber Kill Chain](https://www.lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf)
### [MITRE ATT&CK](https://attack.mitre.org/)
### [Diamond Model](https://apps.dtic.mil/docs/citations/ADA586960)
