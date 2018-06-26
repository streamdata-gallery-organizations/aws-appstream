---
name: AWS AppStream
x-slug: aws-appstream
description: Amazon AppStream is a fully managed, secure application streaming service
  that allows you to stream desktop applications from AWS to any device running a
  web browser, without rewriting them. Amazon AppStream 2.0 provides users instant-on
  access to the applications they need, and a responsive, fluid user experience on
  the device of their choice.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS AppStream
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/apis.md
specificationVersion: "0.14"
apis:
- name: AWS AppStream 2.0 API Associate Fleet
  x-api-slug: aws-appstream-2-0-api
  description: Associate a fleet to a stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=AssociateFleet
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionassociatefleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionassociatefleet-get-openapi.md
- name: AWS AppStream 2.0 API Create Fleet
  x-api-slug: aws-appstream-2-0-api
  description: Creates a new fleet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=CreateFleet
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actioncreatefleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actioncreatefleet-get-openapi.md
- name: AWS AppStream 2.0 API Create Stack
  x-api-slug: aws-appstream-2-0-api
  description: Create a new stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=CreateStack
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actioncreatestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actioncreatestack-get-openapi.md
- name: AWS AppStream 2.0 API Create Streaming URL
  x-api-slug: aws-appstream-2-0-api
  description: Creates a URL to start an AppStream 2.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=CreateStreamingURL
  tags: URL
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actioncreatestreamingurl-get-openapi.md
- name: AWS AppStream 2.0 API Delete Fleet
  x-api-slug: aws-appstream-2-0-api
  description: Deletes a fleet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DeleteFleet
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondeletefleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondeletefleet-get-openapi.md
- name: AWS AppStream 2.0 API Delete Stack
  x-api-slug: aws-appstream-2-0-api
  description: Deletes the stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DeleteStack
  tags: Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondeletestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondeletestack-get-openapi.md
- name: AWS AppStream 2.0 API Describe Fleets
  x-api-slug: aws-appstream-2-0-api
  description: |-
    If fleet names are provided, this operation describes the specified fleets;
                otherwise, all the fleets in the account are described.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DescribeFleets
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondescribefleets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondescribefleets-get-openapi.md
- name: AWS AppStream 2.0 API Describe Images
  x-api-slug: aws-appstream-2-0-api
  description: Describes the images.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DescribeImages
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondescribeimages-get-openapi.md
- name: AWS AppStream 2.0 API Describe Sessions
  x-api-slug: aws-appstream-2-0-api
  description: Describes the streaming sessions for a stack and a fleet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DescribeSessions
  tags: Sessions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondescribesessions-get-openapi.md
- name: AWS AppStream 2.0 API Describe Stacks
  x-api-slug: aws-appstream-2-0-api
  description: |-
    If stack names are not provided, this operation describes the specified stacks;
                otherwise, all stacks in the account are described.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DescribeStacks
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondescribestacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondescribestacks-get-openapi.md
- name: AWS AppStream 2.0 API Disassociate Fleet
  x-api-slug: aws-appstream-2-0-api
  description: Disassociates a fleet from a stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DisassociateFleet
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondisassociatefleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actiondisassociatefleet-get-openapi.md
- name: AWS AppStream 2.0 API Expire Session
  x-api-slug: aws-appstream-2-0-api
  description: This operation immediately stops a streaming session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=ExpireSession
  tags: Session
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionexpiresession-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionexpiresession-get-openapi.md
- name: AWS AppStream 2.0 API List Associated Fleets
  x-api-slug: aws-appstream-2-0-api
  description: Lists all fleets associated with the stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=ListAssociatedFleets
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionlistassociatedfleets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionlistassociatedfleets-get-openapi.md
- name: AWS AppStream 2.0 API List Associated Stacks
  x-api-slug: aws-appstream-2-0-api
  description: Lists all stacks to which the specified fleet is associated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=ListAssociatedStacks
  tags: Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionlistassociatedstacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionlistassociatedstacks-get-openapi.md
- name: AWS AppStream 2.0 API Start Fleet
  x-api-slug: aws-appstream-2-0-api
  description: Starts a fleet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=StartFleet
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionstartfleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionstartfleet-get-openapi.md
- name: AWS AppStream 2.0 API Stop Fleet
  x-api-slug: aws-appstream-2-0-api
  description: Stops a fleet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=StopFleet
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionstopfleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionstopfleet-get-openapi.md
- name: AWS AppStream 2.0 API Update Fleet
  x-api-slug: aws-appstream-2-0-api
  description: Updates an existing fleet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=UpdateFleet
  tags: Fleet
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionupdatefleet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionupdatefleet-get-openapi.md
- name: AWS AppStream 2.0 API Update Stack
  x-api-slug: aws-appstream-2-0-api
  description: Updates the specified fields in the stack with the specified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=UpdateStack
  tags: Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionupdatestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/actionupdatestack-get-openapi.md
- name: AWS AppStream 2.0 API
  x-api-slug: aws-appstream-2-0-api
  description: Amazon AppStream 2.0 is a fully managed, secure application streaming
    service that allows you to stream desktop applications from AWS to any device
    running a web browser, without rewriting them. Amazon AppStream 2.0 provides users
    instant-on access to the applications they need, and a responsive, fluid user
    experience on the device of their choice.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: :///
  tags: AWS AppStream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-appstream/master/_listings/aws-appstream/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/appstream2/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/appstream2/faqs/
- type: x-forum
  url: https://aws.amazon.com/appstream2/resources/#forum
- type: x-getting-started
  url: https://aws.amazon.com/appstream2/resources/#getting_starte
- type: x-pricing
  url: https://aws.amazon.com/appstream2/pricing/
- type: x-website
  url: https://aws.amazon.com/appstream2/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---