---
name: ChainGenie
x-slug: chaingenie
description: ChainGenie provides a plug and play platform that helps you connect your
  existing (or create new) applications to DLTs for lodging and workflow management
  using a simple easy to use user interface. ChainGenie is a platform to create blockchain
  apps that provide speed-to-market for companies looking to launch faster, rather
  than reinvent the wheel. Write your applications to run on popular Blockchain networks
  like Ethereum, Bitcoin Blockchain etc with great ease when you require to validate
  credentials or make your existing traditional applications use the power of DLT
  and blockchain overnight!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28902-api-chaingenie-com.jpg
x-kinRank: "7"
x-alexaRank: ""
tags: Balance
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/balance/master/_listings/chaingenie/apis.md
specificationVersion: "0.14"
apis:
- name: ChainGenie = DLT + Blockchain + Magic - Get user's account balance (*)
  x-api-slug: basicfnsgetaccountbalance-post
  description: Get information about an user's account balance.  The call is restricted
    to the unlocked user's account / query only. <br/>* In this sandbox, you can query
    any user's account balance for testing purposes.  All accounts are test accounts
    and no actual value or account is exposed in the sandbox.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28902-api-chaingenie-com.jpg
  humanURL: http://chaingenie.com
  baseURL: https://api.chaingenie.com//api/v1
  tags: Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/balance/master/_listings/chaingenie/basicfnsgetaccountbalance-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/balance/master/_listings/chaingenie/basicfnsgetaccountbalance-post-openapi.md
- name: ChainGenie = DLT + Blockchain + Magic - Bank balance (user)
  x-api-slug: ethbankbalance-get
  description: Displays user bank balance information
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28902-api-chaingenie-com.jpg
  humanURL: http://chaingenie.com
  baseURL: https://api.chaingenie.com//api/v1
  tags: Blockchain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/balance/master/_listings/chaingenie/ethbankbalance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/balance/master/_listings/chaingenie/ethbankbalance-get-openapi.md
x-common:
- type: x-github
  url: https://github.com/ChainGenie
- type: x-website
  url: http://chaingenie.com
- type: x-api-gallery
  url: http://broadleaf.commerce.api.gallery.streamdata.io
- type: x-twitter
  url: https://twitter.com/ChainGenie
- type: x-website
  url: http://api.chaingenie.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---