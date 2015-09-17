# FIMS v1.2

This repository contains the version 1.2 release of the [EBU](http://tech.ebu.ch)/[AMWA](http://www.amwa.tv) 
[Framework for Interoparable Media Services (FIMS)](http://www.fims.tv). The specification has been approved 
by both sponsoring organisations.

## FIMS Overview

FIMS is a vendor-neutral common framework for implementing Interoperable Media Services using a Service 
Oriented Architecture (SOA) based system for use in broadcast, production, post production, media distribution, 
and media archive applications. The framework supports interoperability, interchangeability and reusability of 
media specific services.

This framework covers the following system and management requirements: 

* service management, 
* awareness, 
* behaviour and communication, 
* content and time awareness.

This version of the specification addresses media services for capture, transform, transfer, repository and 
quality control, with support for partial content and servive capability description.

## Significant updates

Four significant additions were made between v1.1 and v1.2 of the specification:

1. Added a new media Quality Assurance service.
2. Support for partial content, particularly for transfer, transform and QC operations from the FIMS _Timecode project_.
3. Enhancements and corrections to the REST mappings.
4. Added service capability description description aligned with the SMPTE 2072 Media Device and Control Framework.

A number of other minor enhancements and improvements were made, including an update of the EBUCore description metadata.

## What's in the package

The main starting point for FIMS is the Word Document Technical Specification `FIMS 1.2 Technical Specification - General 
Description.doc`. Technical specification is contained in the `WSDL-REST-XSD` folder. Note that the REST documentation is 
embedded within the equivalent WSDL file.

### Examples

Some simple [examples](/example/README.md/) are provided in the `example` folder.

## License

FIMS is released unded an the [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0), as detailed in files [LICENSE.txt](/LICENSE.txt/) and [NOTICE.txt](/NOTICE.txt/).

Copyright 2015 The European Broadcasting Union and the Advanced Media Workflow Association 

