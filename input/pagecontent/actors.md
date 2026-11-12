The following ActorDefinitions define the systems that plays a role in data exchange, and that have obligations associated with the role the actor plays, in an instance of the HIPS Local Directory Solution.

- [HIPS Local Directory Solution Searcher Actor](ActorDefinition-requester-actor-health-connect.html)

The HIPS Local Directory Solution Searcher is a clinical or administrative system at a HIPS LDS site that creates and initiates a data access request to retrieve provider directory information from LDS. The set of capabilities (behaviours) for this actor is defined in [HIPS Local Directory Solution Searcher CapabilityStatement](CapabilityStatement-health-connect-provider-directory-requester.html).

- [HIPS Local Directory Solution Enrichment Actor](ActorDefinition-bulk-export-requester-actor-health-connect.html)

The Health Connect Provider Directory Enrichment Actor is an administrative system at a HIPS LDS site that provides additional information to store in the local directory, beyond that which is syndicated from the national directory. The set of capabilities (behaviours) for this actor is defined in [Health Connect Provider Directory Enrichment Actor CapabilityStatement](CapabilityStatement-health-connect-bulk-export-requester.html).

- [HIPS Local Directory Solution Repository Actor](ActorDefinition-responder-actor-health-connect.html)

The HIPS Local Directory Solution Repository is the LDS component that stores and allows syndication, storage, export, searching and local enrichment of provider directory information. The set of capabilities (behaviours) for this actor is defined in [HIPS Local Directory Solution Repository CapabilityStatement](CapabilityStatement-health-connect-provider-directory-responder.html).
