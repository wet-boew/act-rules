---
title: Not found
permalink: /rules/functional/not_found
---

# Not found

Rule id: https://wet-boew.github.io/act-rules/rules/functional/not_found

## Rule type: 
Atomic rule

## Accessibility requirement mappings:
(none)

## Input aspects:

* [DOM Tree](https://www.w3.org/TR/act-rules-aspects/#input-aspects-dom)
* [Source code](https://www.w3.org/TR/act-rules-aspects/#input-aspects-code)

## Description

Could not find a document at the URL provided. The link may refer to a document that no longer exists, or is pointing to the wrong place.

## Applicability

To be defined

## Expectation

Every URL is fetchable for any HTML anchor element, link, JS fetched file.

## Assumptions

To be defined

## Accessibility support

To be defined

## Test cases

### Passed - Test link manually

All link do sucessfully resolve and return a document or an HTTP 200 response

### Pass - Browser network tab

Open the browser network tab, refresh the page and wait until the page load is completed.
Do all the in-page action (action that don't navigate the user outide the current page URL)
Observer the status beside every entry in the network tab.
Expected that all URL response code are in the 200 HTTP status category.

### Failed - Test link manually

Link return an HTTP error like 404 or any 400 or 500 HTTP error category.

### Failed - Error in browser network tab

Open the browser network tab, refresh the page and wait until the page load is completed.
Do all the in-page action (action that don't navigate the user outide the current page URL)
Observer the status beside every entry in the network tab.
Expected that we can found one or some that are returning 400 or 500 error category.

### Inapplicable

There is no link in the tested subject

## Glossary

(none)
