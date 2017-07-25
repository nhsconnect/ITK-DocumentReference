# Change History #

### Version 1.0.0-alpha.1 ###

 - Updated all CareConnect profiles to latest versions.
 - Renamed all COFE prefixed profiles to ITK across the specification.
 - Renamed CareConnect-Encounter-1 to CareConnect-ITK-Encounter-1.
 - Made the CareConnect-ITK-Encounter-1.indication,  hospitalization.admittingDiagnosis and hospitalization.dischargeDiagnosis 0..0 cardinality.
 - Replaced reference to CareConnect-Encounter-1 with CareConnect-ITK-Encounter-1 at CareConnect-ITK-Encounter-1.partOf.
 - Replaced reference to CareConnect-Encounter-1 with CareConnect-ITK-Encounter-1 at ITK-DocumentReference-1.context.encounter.
 - Corrected valueset at url https://fhir.nhs.uk/ValueSet/document-type-1.
 - Removed the following elements from ITK-DocumentReference-1:- relatesTo, securityLabel, content.format, context.event, context.facilityType, context.practiceSetting, context.sourcePatientInfo, context.related.
 - Replaced Extension-Care-Setting-Type-1 profile with Extension-ITK-Care-Setting-Type-1.
 - Made all values in extensions mandatory.
 - Added CareConnect-Practitioner-1 as a reference within Extension-ITK-Informant-1.
 - Added ITK-Related-Person-1 and CareConnect-Patient-1 as references within Extension-ITK-Information-Recipient-1.
 - Updated ITK-Bundle-Example-1 xml example.
 - Removed xml examples based on individual profiles.
 - Added references to CareConnect-Practitioner-1, CareConnect-Organization-1 and ITK-Device-1 within Extension-ITK-Participant-1. 
 - Added text and diagrams to Architecture page.
 - Added pdf visual representations of ITK Document Reference Header profile references and ITK DocumentReference-1 extensions and their associated references.
 

### Version: 1.0; Status: Draft A #

First draft of ITK Document Reference Header specification. 








