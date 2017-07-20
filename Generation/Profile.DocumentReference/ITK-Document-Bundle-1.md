The ITK-Document-Bundle-1 bundle profile is used in the CDA on FHIR Document Reference interface as a container to collect the following profiles: 

- **[ITK-DocumentReference-1]**  An NHS Digital DocumentReference profile used to carry base64 encoded binary content defined by a format other than FHIR, for example a PDF file or an image file. This encoded content must be included in the message bundle.
- **[ITK-Binary-1]**  An NHS Digital profile which stores a health or social care document in a base64 binary format.  
- **[CareConnect-Patient-1]**  A CareConnect profile which carries the patient demographic details.
- **[CareConnect-Practitioner-1]**  A CareConnect profile which carries information about the healthcare professional.
- **[ITK-RelatedPerson-1]** An NHS Digital profile which carries information about a person with a relationship to the patient.
- **[CareConnect-ITK-Encounter-1]** An NHS Digital profile which carries information about an encounter between a care professional and the patient (or patient's record).
- **[CareConnect-Organization-1]**  A CareConnect profile which carries details of an Organization such as a company, institution, corporation, department, community group or healthcare practice group.
- **[CareConnect-Location-1]**  An CareConnect profile which carries details and position information for a physical place where services are provided and resources and participants may be stored, found, contained or accommodated.
- **[ITK-Device-1]**  An NHS Digital profile which identifies an instance of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity. The device may be a medical or non-medical device.

----------
**Example**

The following xml bundle example contains an instance of a DocumentReference resource and has been converted to a txt file  to allow better viewing within a web browser; an [xml copy] is available within the examples folder in this specification.


This is an example of a document Bundle [ITK-Bundle-Example-1.txt]
 

----------

[ITK-Bundle-Example-1.txt]: ../Chapter.5.Examples/ITK-Bundle-Example-1.txt

[ITK-DocumentReference-1]: itk-documentreference-1.html
[ITK-Binary-1]: itk-binary-1.html
[CareConnect-ITK-Encounter-1]:	careconnect-itk-encounter-1.html
[CareConnect-Patient-1]: 	careconnect-patient-1.html
[CareConnect-Practitioner-1]:	careconnect-practitioner-1.html
[ITK-RelatedPerson-1]: 	itk-relatedperson-1.html
[CareConnect-Organization-1]: careconnect-organization-1.html
[CareConnect-Location-1]: careconnect-location-1.html
[ITK-Device-1]: itk-device-1.html
[CareConnect-ITK-Encounter-1]: careconnect-itk-encounter-1.html
[xml copy]: ../Examples/Profile.DocumentReference/ITK-Bundle-Example-1.xml
