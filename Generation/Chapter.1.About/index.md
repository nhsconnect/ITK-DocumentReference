# About #

###Overview: CDA On FHIR England - Document Reference#

**Background**

In previous NHS Digital CDA specifications there is a structure which allows low maturity level systems to send embedded documents using the standard "CDA header". This was called the "NonXML Body" within the CDA model. It allows for documents in various formats to be sent (for example a .pdf, a .tif , a docx, .png) within the CDA header. This means that the embedded document is not just a "Blob", but has header information which can be used as meta data to give information about the embedded document for indexing, processing etc.

Some examples of the information carried in the CDA header are:

-  Author
-  Custodian
-  Recipients
-  Document type
-  Date of creation
-  Patient Details

This specification has been produced to enable the "NonXML Body" approach supported by CDA to be supported in FHIR. The structure and approach do differ, however the principle is the same.

The FHIR Specification uses the Document Reference resource in place of the CDA header structure. The information carried in the Document Reference, which can be used as meta data is  similar to what is available in CDA. The Binary Resource is used to carry the actual embedded document. As in CDA the embedded document is base64 encoded and has a MIME type to identify the format/type of embedded document.

**Further Information**

This FHIR Document reference specification is based on and intended to be used alongside the published [FHIR DSTU2 1.0.1] (October 2015) specification. 

[FHIR DSTU2 1.0.1]: http://hl7.org/fhir/index.html

<font color="red">**Note**

This FHIR Document specification is published as a 'work in progress' version and as such is subject to change. As it is a DRAFT, it is not in an implementable state. It has been published to show the direction of travel and to serve as a discussion document for parties involved with the implementation of CDA On FHIR England  Document communications.
</font>