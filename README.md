# MSAG Conversaion Service

The MSAG Conversion Service provides a convenient way to provide data to, or get data from, a non-upgraded system that still uses MSAG data. This web service provides conversion between PIDF LO and MSAG data. Two functions are defined:

* PIDFLOtoMSAG: which takes a PIDF LO, as described in RFC 4119 [6] and updated by RFC 5139 [53] and RFC 5491 [52], and returns an MSAG address as an XML object conforming to NENA 02 010 Version 4, XML Format for Data Exchange;

* MSAGtoPIDFLO: which takes an MSAG address as an XML object conforming to NENA 02 010 Version 4, XML Format for Data Exchange, and returns a PIDF LO, as described in RFC 4119 and updated by RFC 5139 and RFC 5491.


## Owner

The owner of this repository approves all changes to the repository. 

This repository is owned by the NENA Core Services Committee, i3 Architecture working group.

#### Rules:

Specification Required. 

#### Contact:

[https://www.nena.org/page/911CoreSvcs](https://www.nena.org/page/911CoreSvcs) 

## Version History

### MSAG Conversion Service v 1.0

Version 1 OpenAPI schema for this service was originally defined in NENA-STA-010.3.2021. See https://www.nena.org/page/i3_Stage
