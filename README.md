# Cybersecurity Forensics Ontology

## Description
This ontology models key concepts and relationships in cybersecurity forensics. It focuses on incidents, digital evidence, investigations, actors, and forensic tools used to analyze cybercrime events.

## Classes
- **Incident**: A cybersecurity breach or suspicious event triggering an investigation.
- **DigitalEvidence**: Digital data collected during investigations, including files, logs, and network traces.
- **Actor**: Participants involved in incidents, such as attackers, investigators, and victims.
- **Tool**: Software or hardware used during forensic investigations.
- **Action**: Specific steps or operations performed during the investigation process.
- **Investigation**: The process and activities aimed at analyzing incidents.

## Object Properties
- **collectedFrom**: Links digital evidence to the incident it was collected from.
- **performedBy**: Links an action to the actor performing it.
- **targetsActor**: Connects an incident to an involved actor (e.g., attacker or victim).
- **involvesEvidence**: Connects an investigation to the evidence it involves.
- **analyzedBy**: Links an investigation to the tools used.

## Data Properties
- **hasTimestamp**: Date and time when the evidence was collected.
- **hasFileType**: The file format of digital evidence.
- **hasHashValue**: Hash values associated with digital evidence.
- **hasName**: Name or identifier for actors or tools.
- **hasToolVersion**: Version information for forensic tools.

## Usage
Load the OWL file in Protégé or any OWL-compliant tool to explore the structure, relationships, and examples. This ontology can be extended to support digital forensic analysis, evidence management, and cybercrime investigations.

