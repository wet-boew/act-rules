# Closed functionality - EN 301 549 v3

Rule id: https://wet-boew.github.io/act-rules/rules/en301549_v3/clause_func/c5_1_2_1_closed_functionality.html

Rule type: Atomic rule

Accessibility requirement mappings:
* Clause 5.1.2.1 Closed functionality
  * **Required for conformance** to EN 301 549 v3
  * Outcome mapping:
    * Any `failed` outcomes: clause is not satisfied.
    * All `passed` outcomes: clause needs further testing.
    * An `inapplicable` outcome: clause is satisfied.

Input aspects:
* Closed functionality

## Description

This rule check if the element are in scope or out of scope of a closed functtinality

## Applicability

This rule apply to any ICT

## Expectation

1. The ICT prevent a end-user from attaching, installing or using assistive technology.

## Assumptions

There is no known assumptions, limitiation or exceptions.

## Accessibility support

There is no known accessibility support issues.

## Test cases

### Passed

1. Determine the closed functions of the ICT.
2. Check that the tests C.5.1.3 to C.5.1.6 can be carried out without the attachment or installation of any assistive technology except personal headsets or inductive loops.

Check 2 is true

### Failed

1. Determine the closed functions of the ICT.
2. Check that the tests C.5.1.3 to C.5.1.6 can be carried out without the attachment or installation of any assistive technology except personal headsets or inductive loops.

Check 2 is false

### Inapplicable

The ICT has no closed functionality.

## Change log

Information carried over the EN 301 549 standard PDF

## Glossary

* **closed functionality:** functionality that is limited by characteristics that prevent a user from attaching, installing or using assistive technology
