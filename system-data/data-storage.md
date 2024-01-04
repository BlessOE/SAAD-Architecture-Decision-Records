# How the data will be stored

## Context
Chosing a method to store the data being collected and how they may interact with each other

## Decision
The system will include three main databases alongside the main visa processing system
1) The biometrics database, to store all of the collected data which can then be accessed by the applicant to add to their application
2) The visa application database, to store all of the data filled in for the visa application
3) The visa database, to store all of the information about the available visas and their requirements.

## Consequences
- Having only three databases might be considered too small for such a large system, so could affect the systems ability to be scaled

## Status
Accepted
