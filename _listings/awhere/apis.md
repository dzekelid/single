---
name: aWhere
x-slug: awhere
description: aWhere Ag Data Management harnesses agriculture analytics to create unprecedented
  visibility and insight from farm level to national policy. Learn more at aWhere.com!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
x-kinRank: "7"
x-alexaRank: "891345"
tags: Single
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/single/master/_listings/awhere/apis.md
specificationVersion: "0.14"
apis:
- name: aWhere API Platform - Get a Single Field by ID
  x-api-slug: v2fieldsfield1-get
  description: |-
    ####Request
    This API call retrieves a single field by ID.

    [Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)


    ####Security
    This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21116-developer-awhere-com.jpg
  humanURL: http://developer.awhere.com/
  baseURL: https://api.awhere.com//
  tags: SaaS, Enterprise, Agriculture, Technology, General Data, Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/single/master/_listings/awhere/v2fieldsfield1-get-openapi.md
x-common:
- type: x-blog-rss
  url: http://blog.awhere.com/rss.xml
- type: x-github
  url: https://github.com/aWhereAPI
- type: x-website
  url: http://www.awhere.com
- type: x-api-gallery
  url: http://automox.api.gallery.streamdata.io
- type: x-api-stack
  url: http://awhere.stack.network
- type: x-blog
  url: http://blog.awhere.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/awhere
- type: x-developers
  url: http://developer.awhere.com/
- type: x-website
  url: http://awhere.com
- type: x-support
  url: http://www.awhere.com/services-and-support
- type: x-twitter
  url: https://twitter.com/aWhere
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---