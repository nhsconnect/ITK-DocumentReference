# Change History #

### Version 1.0.0-alpha.1 ###

 - Updated all CareConnect profiles to latest versions.
 - Renamed CareConnect-Encounter-1 to CareConnect-COFE-Encounter-1.
 - Made the CareConnect-COFE-Encounter-1.indication,  hospitalization.admittingDiagnosis and hospitalization.dischargeDiagnosis 0..0 cardinality.
 -  - Replaced reference to CareConnect-Encounter-1 with CareConnect-COFE-Encounter-1 at CareConnect-COFE-Encounter-1.partOf.
 - Replaced reference to CareConnect-Encounter-1 with CareConnect-COFE-Encounter-1 at COFE-DocumentReference-1.context.encounter.
 - Corrected valueset at url https://fhir.nhs.uk/ValueSet/document-type-1.
 - Removed the following elements from COFE-DocumentReference-1:- relatesTo, securityLabel, content.format, context.event, context.facilityType, context.practiceSetting, context.sourcePatientInfo, context.related.
 - Replaced Extension-Care-Setting-Type-1 profile with Extension-COFE-Care-Setting-Type-1.
 - Made all values in extensions mandatory.
 - Added CareConnect-Practitioner-1 as a reference within Extension-COFE-Informant-1.
 - Added COFE-Related-Person-1 and CareConnect-Patient-1 as references within Extension-COFE-Information-Recipient-1.   

### Version: 1.0; Status: Draft A #

First draft of CDA On FHIR England - Document Reference DMS (Version 1.0 Draft A).








