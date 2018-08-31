---
name: Infermedica
x-slug: infermedica
description: At Infermedica we believe in people. Every team member brings unique
  skills, talent and knowledge. Together we solve the most complex healthcare problems.
  Infermedica improves the diagnostic process using the most advanced reasoning technology
  for preliminary medical diagnosis.White-labelled enterprise platform (web, mobile,
  chatbot or voice-enabled applications) for symptom checking, patient triage and
  clinical decision support. Open developer portal that allows to easily integrate
  our diagnostic engine into 3rd party software.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
x-kinRank: "7"
x-alexaRank: "0"
tags: Infermedica
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/apis.md
specificationVersion: "0.14"
apis:
- name: Infermedica - Get Conditions
  x-api-slug: conditions-get
  description: Returns a list of all available conditions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/conditions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/conditions-get-openapi.md
- name: Infermedica - Get Conditions
  x-api-slug: conditionsid-get
  description: Returns details of a single condition specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/conditionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/conditionsid-get-openapi.md
- name: Infermedica - Post Diagnosis
  x-api-slug: diagnosis-post
  description: Suggests possible diagnoses and relevant observations based on provided
    patient information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/diagnosis-post-openapi.md
- name: Infermedica - Post Explain
  x-api-slug: explain-post
  description: Explains which evidence impact probability of selected condition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/explain-post-openapi.md
- name: Infermedica - Get Info
  x-api-slug: info-get
  description: Returns information about data used by diagnostic engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/info-get-openapi.md
- name: Infermedica - Get Lab Tests
  x-api-slug: lab-tests-get
  description: Returns a list of all available lab tests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/lab-tests-get-openapi.md
- name: Infermedica - Get Lab Tests
  x-api-slug: lab-testsid-get
  description: Returns details of a single lab test specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/lab-testsid-get-openapi.md
- name: Infermedica - Get Lookup
  x-api-slug: lookup-get
  description: Returns a single observation matching given phrase.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/lookup-get-openapi.md
- name: Infermedica - Post Parse
  x-api-slug: parse-post
  description: Returns list of mentions of observation found in given text.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/parse-post-openapi.md
- name: Infermedica - Get Risk Factors
  x-api-slug: risk-factors-get
  description: Returns a list of all available risk factors.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/risk-factors-get-openapi.md
- name: Infermedica - Get Risk Factors
  x-api-slug: risk-factorsid-get
  description: Returns details of a single risk factor specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/risk-factorsid-get-openapi.md
- name: Infermedica - Get Search
  x-api-slug: search-get
  description: Returns list of observations matching the given phrase.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/search-get-openapi.md
- name: Infermedica - Post Suggest
  x-api-slug: suggest-post
  description: Suggests possible symptoms based on provided patient information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/suggest-post-openapi.md
- name: Infermedica - Get Symptoms
  x-api-slug: symptoms-get
  description: Returns a list of all available symptoms.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/symptoms-get-openapi.md
- name: Infermedica - Get Symptoms
  x-api-slug: symptomsid-get
  description: Returns details of a single symptom specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/symptomsid-get-openapi.md
- name: Infermedica - Post Triage
  x-api-slug: triage-post
  description: Estimates triage level based on provided patient information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/triage-post-openapi.md
- name: Infermedica - List all observations
  x-api-slug: observations-get
  description: Returns a list of all available observations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/observations-get-openapi.md
- name: Infermedica - Get observation by id
  x-api-slug: observationsid-get
  description: Returns details of a single observation specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: API Provider, Healthcare, Artificial Intelligence, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/infermedica/master/_listings/infermedica/observationsid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://import.io.api.gallery.streamdata.io
- type: x-api-stack
  url: http://infermedica.stack.network
- type: x-blog
  url: https://blog.infermedica.com/
- type: x-blog-rss
  url: https://blog.infermedica.com/rss/
- type: x-curated-source
  url: https://developer.infermedica.com/
- type: x-developer
  url: http://developer.infermedica.com
- type: x-github
  url: https://github.com/infermedica
- type: x-status
  url: http://status.infermedica.com/
- type: x-twitter
  url: https://twitter.com/infermedica
- type: x-website
  url: http://infermedica.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---