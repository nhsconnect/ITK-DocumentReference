# About #

### Overview ###

**Background**

In previous NHS Digital CDA specifications there is a structure which allows low maturity level systems to send embedded documents using the standard "CDA header". This was called the "NonXML Body" within the CDA model. It allows for documents in various formats to be sent (for example a .pdf, a .tif , a docx, .png) within the CDA header. This means that the embedded document is not just a "Blob", but has header information which can be used as meta data to give information about the embedded document for indexing, processing etc.

Some examples of the information previously carried in the CDA header include:

-  Author
-  Custodian
-  Recipients
-  Document type
-  Date of creation
-  Patient Details

This specification has been produced to enable the "NonXML Body" approach supported by CDA to be supported in FHIR. The structure and approach do differ, however the principle is the same.

This FHIR specification uses the DocumentReference resource in place of the CDA header structure to allow the inclusion of pre-existing documents which are non-FHIR based within a message bundle. A pertinent example could be a pdf document requesting further information about a patient or containing other types of supporting information. The Binary Resource is used to carry the actual embedded document. As in CDA the embedded document is base64 encoded and has a MIME type to identify the format/type of embedded document. For more information on FHIR documents and their implementation, please consult the relevant [FHIR document guidelines].

**Further Information**

This FHIR Document reference specification is based on and intended to be used alongside the published [FHIR DSTU2 1.0.1] (October 2015) specification. 

[FHIR DSTU2 1.0.1]: http://hl7.org/fhir/DSTU2/index.html
[FHIR document guidelines]: https://www.hl7.org/fhir/DSTU2/documents.html

