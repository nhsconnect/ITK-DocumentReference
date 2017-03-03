The COFE-Document-Bundle-1 bundle resource profile is used in the CDA on FHIR Document Reference interface as a container to collect the following profiles: 

- **[COFE-DocumentReference-1]**  An NHS Digital Composition profile which is used to describe a PDF document that is made available to a health or social care system, establish context and stores its contents in a base64 binary encoded format.
- **[COFE-Binary-1]**  An NHS Digital profile which stores a health or social care PDF document in a base64 binary format.  
- **[CareConnect-Patient-1]**  A CareConnect profile which carries the patient demographic details.
- **[CareConnect-Practitioner-1]**  A CareConnect profile which carries information about the healthcare professional.
- **[COFE-Related-Person-1]** An NHS Digital profile which carries information for a person with a relationship with the patient.
- **[CareConnect-Organization-1]**  A CareConnect profile which carries details of the Organization.
- **[COFE-Location-1]**  An NHS Digital profile which carries information and details on the physical location and the services provided.
- **[COFE-Device-1]**  An NHS Digital profile which identifies an instance of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity. The device may be a medical or non-medical device.

----------
**Examples**

The following example contains a composition resource and has been converted to a txt file  to allow better viewing within a web browser, xml copies are available within the examples folder within this specification.


This is an example of an eDischarge document Bundle [COFE-XML-1.txt]
 
This is an example of an eDischarge document Bundle after rendering [COFE-Rendered-1.html]

----------

[COFE-XML-1.txt]: ../Chapter.5.Examples/COFE-DocumentReference-Bundle-1-Example.txt
[COFE-Rendered-1.html]: ../Chapter.5.Examples/COFE-DocumentReference-Bundle-1-Example.html

[COFE-DocumentReference-1]: cofe-documentreference-1.html
[COFE-Binary-1]: cofe-binary-1.html
[CareConnect-TOC-Encounter-1]:	careconnect-toc-encounter-1.html
[CareConnect-Patient-1]: 	careconnect-patient-1.html
[CareConnect-Practitioner-1]:	careconnect-practitioner-1.html
[COFE-Related-Person-1]: 	cofe-related-person-1.html
[CareConnect-Organization-1]: careconnect-organization-1.html
[COFE-Location-1]: cofe-location-1.html
[COFE-Device-1]: cofe-device-1.html
