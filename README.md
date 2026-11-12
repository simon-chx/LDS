# HIPS Local Directory Solution (LDS)
The objective of the LDS is to provide a local copy of a subset of the HCAPD, with export, search and local enrichment capabilities, to simplify the integration of the HCAPD, a new national provider directory, with clinical and administrative systems in large and complex healthcare provider organisations such as state/territory health departments, private hospitals and diagnostic service providers.

One of the key objectives of the LDS is to enable local enrichment through integration of LDS with clinical and administrative systems. To support this, the LDS establishes a local directory hosted on a FHIR repository, where provider and organisation data will be structured using the same HL7 FHIR and SNOMED CT-AU standards as the national directory. To guide consistent implementation, the LDS team are developing tooling to enable LDS sites to author their own FHIR Implementation Guides that build upon the Health Connect Australia Provider Directory FHIR Implementation Guide. These guides will define how provider information will be enriched within their local LDS instances. These guides will build on existing standards, including the Health Connect Australia Provider Directory FHIR IG, and provide a clear reference for integrators and system vendors within LDS sites to support secure, scalable, and standards-compliant access to directory data.

As several jurisdictions and other LDS sites may encounter the need to add similar local enrichment to their LDS instances, it is envisioned that a community process could be established to allow the sharing of LDS local enrichment guides and even standardisation at a national level into the HL7 Australia Provider Directory implementation guide where appropriate.

# LDS FHIR Implementation Guide (IG)
 
## Overview
This repository hosts a FHIR Implementation Guide (IG) for the out-of-the-box functionality of the LDS itself. It supports the same search capabilities as the national directory, but adds on the ability to create or update records in the local directory. Local and national changes to directory records are tracked and audited using Provenance resources. Sites can utilise this IG directly or modify it and load the new StructureDefinition and related resources into the LDS, to add their own extensions and slices to store additional kinds of information, identifiers, contact details and other content attached to the records in the local directory.

### link to published site
TBD

## How to Build

### Pre-requisites
[SUSHI](https://fshschool.org/docs/sushi/installation/) - Ensure you have Node JS installed, and then install SUSHI via `npm install -g fsh-sushi`

[Jekyll](https://jekyllrb.com/docs/installation/) - Jekyll is a Ruby Gem and instructions are available for various operating systems.

### Building
Run either the `_genonce.bat` or `_genonce.sh` script.

 
## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute.
 
## License
This project is licensed under Creative Commons license 4.0 - see the [LICENSE](LICENSE) file for details.

