- *The Reason or justification for a referral or consultation is communicated through:
  1. `ServiceRequest.reason` or `ServiceRequest.reason`, and `Procedure.basedOn` that links the Procedure to the US Core ServiceRequest Profile.
     - `ServiceRequest.reasonCode` and `ServiceRequest.reasonReference` are marked as Additional USCDI Requirements. The certifying server system is not required to support both but **SHALL** support at least one of these elements. The certifying client application **SHALL** support both elements.
     - As documented [here](general-guidance.html#referencing-us-core-profiles), when using  `ServiceRequest.reasonReference`, the referenced resources **SHOULD** be a US Core Profile.
  1. `Procedure.reasonCode` or `Procedure.reasonReference` when the Procedure does not have an associated ServiceRequest.
     - Although both `Procedure.reasonCode` and `Procedure.reasonReference` are marked as Additional USCDI Requirements. The certifying server system is not required to support both but **SHALL** support at least one of these elements. The certifying client application **SHALL** support both elements.
     - As documented [here](general-guidance.html#referencing-us-core-profiles), when using  `Procedure.reasonReference`, the referenced resources **SHOULD** be a US Core Profile.

    Certifying Servers and Clients **SHALL** support options 1 and 2 as Additional USCDI Requirements.