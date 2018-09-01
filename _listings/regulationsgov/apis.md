---
name: Regulations.gov
x-slug: regulationsgov
description: Regulations.gov is a multi-agency website where citizens can view and
  comment on federal regulations and other agency actions that affect their daily
  lives. More than 35 federal departments and agencies participate in Regulations.gov,
  which is designed to encourage public involvement and citizen input.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/regulations-gov-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Regulations.gov
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/apis.md
specificationVersion: "0.14"
apis:
- name: Regulations.gov Returns Docket information
  x-api-slug: regulationsgov
  description: Returns Docket information
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/regulations-gov-logo.png
  humanURL: https://www.regulations.gov/
  baseURL: https://api.data.gov//regulations/v3//docket.{response_format}
  tags: Regulations,Dockets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/docketresponse-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/docketresponse-format-get-openapi.md
- name: Regulations.gov Returns Document information
  x-api-slug: regulationsgov
  description: Returns Document information
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/regulations-gov-logo.png
  humanURL: https://www.regulations.gov/
  baseURL: https://api.data.gov//regulations/v3//document.{response_format}
  tags: Regulations,Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/documentresponse-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/documentresponse-format-get-openapi.md
- name: Regulations.gov Search for Documents
  x-api-slug: regulationsgov
  description: This API allows users to build a query based on any of the parameters
    below.  If you have trouble building queries, you may wish to try them through
    the Advanced Search page on the Regulations.gov website.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/regulations-gov-logo.png
  humanURL: https://www.regulations.gov/
  baseURL: https://api.data.gov//regulations/v3//documents.{response_format}
  tags: Regulations,Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/documentsresponse-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/documentsresponse-format-get-openapi.md
- name: Regulations.gov
  x-api-slug: regulationsgov
  description: Regulations.gov is a multi-agency website where citizens can view and
    comment on federal regulations and other agency actions that affect their daily
    lives. More than 35 federal departments and agencies participate in Regulations.gov,
    which is designed to encourage public involvement and citizen input.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/regulations-gov-logo.png
  humanURL: https://www.regulations.gov/
  baseURL: https://api.data.gov//regulations/v3
  tags: Regulations.gov
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/regulations.gov/master/_listings/regulationsgov/openapi.md
x-common:
- type: x-developer
  url: http://regulationsgov.github.io/developers/
- type: x-website
  url: https://www.regulations.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---