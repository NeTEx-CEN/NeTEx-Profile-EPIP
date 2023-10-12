# NeTEx-Profile-EPIP
Data4PT (Programme Support Action for Transmodel implementation) provides an XSD that adapts to European Passenger Information profile (EPIP). 
This tool aims to enable datasets validation against this minimum EU profile while also to be used as a base for national profiles specification, depending on national needs.

## XSDs

This repository contains the XSD files for the NeTEx European Passenger Information Profile (EPIP). The EPIP is a subset of the full NeTEx schema that covers the most important data elements for providing passenger information, such as stop locations, routes, timetables, and fares.

The following XSD files are available in this repository:


XSD File Name                          | Description
--------------------------------------|-------------------------------------------------------------
**`NeTEx_publication_EPIP.xsd`**            | Defines the schema for a NeTEx publication that conforms to the EPIP.
**`NeTEx_publication_EPIP-NoConstraint.xsd`**  | A simplified version of NeTEx_publication_EPIP.xsd, removing optional elements and constraints for easier use.
**`_content_NeTEx_EPIP.xsd`**                | Defines the content model for the NeTExPublication element in the EPIP. Specifies elements and their order.
**`gml_combo_v3_2_1_simplified.xsd`**        | A simplified version of the GML 3.2.1 schema, removing optional elements and constraints for easier use.


A graphic interactive technical presentation is available here https://data4pt.org/wiki/NeTEX#NeTEx_EPIP.
