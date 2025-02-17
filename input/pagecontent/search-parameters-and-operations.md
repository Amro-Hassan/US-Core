### Operations

The following operation has been defined for the US Core Implementation Guide. For more information on [FHIR RESTful operations], see the FHIR specification.

  {% include list-simple-operationdefinitions.xhtml %}

<br />

### Search Parameters

The following search parameters have been defined for the US Core Implementation Guide. The FHIR specification provides more information on the [FHIR RESTful search API] and the standard [Search Parameter Registry].

NOTE: The following search parameters **SHALL NOT** be interpreted as server requirements. The CapabilityStatement defines the search capabilities expectations for the US Core Server. This section lists the search parameter definitions used within the CapabilityStatement. It is not a list of search requirements for the client or server. Certain search parameters have been defined without explicit categorization as either Mandatory or Optional. They are provided to assist implementers who may find them relevant to their specific use cases.
{:.bg-warning}

#### Search Parameters defined by this Implementation Guide

##### CareTeam
- [role]

##### Condition
- [asserted-date]

##### Encounter
- [discharge-disposition]

##### Goal
- [description]

##### Patient
- [race]
- [ethnicity]
- [gender-identity]


#### Search Parameters derived from the Base FHIR Specification

These US Core SearchParameters are derived from the Base FHIR Specification to define the expectations for the following SearchParameter elements:

- [multipleAnd]
- [multipleOr]
- [comparator]
- [modifier]
- [chain]

{% include uscore_sp_list.md %}

{% include link-list.md %}
