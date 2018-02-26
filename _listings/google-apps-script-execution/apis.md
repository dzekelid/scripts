---
name: Google Apps Script Execution
description: Runs a function in an Apps Script project. The project must be deployed
  for use with the Apps Script Execution API. This method requires authorization with
  an OAuth 2.0 token that includes at least one of the scopes listed in the Authorization
  section; script projects that do not require authorization cannot be executed through
  this API. To find the correct scopes to include in the authentication token, open
  the project in the script editor, then select File gt; Project properties and click
  the Scopes tab.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-apps-scripts-services.png
x-kinRank: "9"
x-alexaRank: ""
tags:
- Stack Network
- Scripts
- Google APIs
created: "2018-02-25"
modified: "2018-02-25"
url: https://raw.githubusercontent.com/streamdata-gallery/scripts/master/_listings/google-apps-script-execution/apis.yaml
specificationVersion: "0.14"
apis:
- name: Google Apps Script Execution API
  description: Runs a function in an Apps Script project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-apps-scripts-services.png
  humanURL: ""
  baseURL: ://script.googleapis.com//
  tags: Scripts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery/scripts/master/_listings/google-apps-script-execution/v1-scripts-scriptid-run-post.md
x-common:
- type: x-best-practices
  url: https://developers.google.com/apps-script/best_practices
- type: x-case-studies
  url: https://developers.google.com/apps-script/case-studies
- type: x-getting-started
  url: https://developers.google.com/apps-script/overview
- type: x-glossary
  url: https://developers.google.com/apps-script/glossary
- type: x-issues
  url: https://code.google.com/p/google-apps-script-issues/issues/list
- type: x-status-dashboard
  url: https://script.google.com/dashboard
- type: x-support
  url: https://developers.google.com/apps-script/support
- type: x-terms-of-service
  url: https://developers.google.com/apps-script/terms
- type: x-website
  url: https://developers.google.com/apps-script/execution/rest/v1/scripts/run
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---