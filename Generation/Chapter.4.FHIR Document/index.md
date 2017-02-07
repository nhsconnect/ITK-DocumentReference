# FHIR Document #

The FHIR resource profiles within this DMS have been created to support the CDA on FHIR Document Reference Header:


 - **[CDA On FHIR England - Document Reference Header]** - FHIR resource profiles combined to support a generic CDA on FHIR Document Reference Header.

**CDA on FHIR England Document Header**

A visual representation of the CDA on FHIR England Document Reference header is available. The preview image below can be <a href="COFEDocumentHeaderHTMLv0.1.png" target="_blank">opened in a new tab</a> or [downloaded as PDF].

<div><a href="COFEDocumentHeaderHTMLv0.1.png" target="_blank"><img  src="COFEDocumentHeaderHTMLv0.1.png" alt="Interactions" height="300px" width="600px"></a></div>  



**Base Resources**

Implementers of the CDA to FHIR - Document Reference Header are required to support the following optional Base Resource elements (and properties) which are defined for all CDA on FHIR resources within this DMS:

**1. Resource Identity:**

Each resource has an "id" element which contains the logical identity of the resource assigned by the server responsible for storing it.

**2. Resource Metadata:**

Each FHIR resource profile contains an element "meta", of type "Meta", which is a set of metadata that provides technical and workflow context to the resource.
| Metadata Item | Type | Usage | | :---- | :---- | :---- | | profile (0..*) | [uri] | This defines resource profiles that are described in the FHIR Document section of the DMS e.g. NHS-Patient [http://hl7.org/fhir/StructureDefinition/Patient] |


**Further Information**

For more information about message profiles visit the [Profiling FHIR] and for resource Metadata visit [Base Resource Definitions].

The various downloads (including Schema files) and reference implementations are available on [FHIR website]. 
 

[CDA On FHIR England - Document Reference Header]: ../Profile.DocumentReference/Profile.DocumentReference.html
[Profiling FHIR]: http://hl7.org/fhir/profiling.html
[FHIR website]: http://hl7.org/fhir/index.html
[Base Resource Definitions]: http://hl7.org/fhir/resource.html
[downloaded as PDF]:COFEDocumentHeaderHTMLv0.1.pdf