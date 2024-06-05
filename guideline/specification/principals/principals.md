#	Principals
##	Principal – support for LOTAR conformance
The LOTAR “Long Term Archiving of digital technical product information” series is an international standard for the long term archiving of Product Model data (such as computer aided design CAD or product data model PDM data). LOTAR extensively references and  extends ISO 14721 the “Open reference model for Archiving Information System”, (OAIS) but does not extend into areas detailed in the E-ARK common specification for information packages (CSIP). LOTAR also references and builds on ISO 10303, the Standard for the Exchange of Product Model data (STEP). This eArchiving 3D Product Model CITS creates a layered model for creating archival packages for Product Models that allows conformance to LOTAR and STEP whilst maintaining conformance with the CSIP and with the individual eArchiving package specifications (SIP, AIP and DIP). Specifically:
+	no requirements in this specification should conflict with mandatory requirements of  LOTAR;
+	requirements of LOTAR with regard to essential data or metadata elements in Information Packages become optional should requirements in the 3D PM CITS;
+	the scope of the E-ARK specifications  are not altered to encompass areas covered by LOTAR but not covered by E-ARK, for example process requirements and management procedures.
A conformant E-ARK 3D PM Information Package will not imply conformance or validation against LOTAR, but an archive will be able to use use the E-ARK 3D PM CITS together with the other E-ARK package specifications to produce Information Packages that support LOTAR compliance.
##	Principal – use of PREMIS
From the CSIP and PREMIS CITS: 
+	PREMIS should be used to record detailed technical metadata;
+	Information about agents carrying out preservation actions must be recorded in the PREMIS  metadata (this is because METS agents describe agents relevant for generic IP level events, such as the creation or submission of the package, not the preservation of the data);
+	Event descriptions should be included in PREMIS metadata. Use of the official PREMIS event vocabulary (https://id.loc.gov/vocabulary/preservation/eventType.html) is recommended;
+	Detailed rights information should be included in PREMIS. High-level rights information in METS indicates restrictions. Detailed, object-specific rights information will be included in the PREMIS metadata;
+	File format information for all files should be included as Persistent Unique Identifier (PUID) values in the appropriate PREMIS semantic units.
Technical and preservation metadata in the context of the 3DPM CITS can include:
+	Creating agent;
+	Reference to the content information standard (e.g. STEP);
+	Reference to the LOTAR standard part for the content information type; 
+	Information about the generating system.
Event descriptions include:
+	Creation events;
+	Conversion or change events;
+	Electronic signature events;
+	Verification events and results;
+	Validation events and results.
Detailed technical metadata in the context of the 3DPM CITS include:
+	File format, characterisation,  checksums;
+	Detailed part number, version, product model and issue information;
+	Relationships for the digital object (is part of, contains parts).
Rights information includes:
+	Access rights;
+	Export controls;
+	License restrictions;
+	Copyright owner;
+	Security classification;
+	Personal identifiable information restrictions;
+	Company specific classifications.
  
Use of PREMIS must conform to the requirements of the Preservation Metadata CITS. 