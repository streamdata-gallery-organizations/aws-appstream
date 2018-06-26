---
swagger: "2.0"
x-collection-name: AWS AppStream
x-complete: 0
info:
  title: AWS AppStream 2.0 API Describe Stacks
  description: |-
    If stack names are not provided, this operation describes the specified stacks;
                otherwise, all stacks in the account are described.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AssociateFleet:
    get:
      summary: Associate Fleet
      description: Associate a fleet to a stack.
      operationId: AssociateFleet
      x-api-path-slug: actionassociatefleet-get
      parameters:
      - in: query
        name: FleetName
        description: The name of the fleet to associate
        type: string
      - in: query
        name: StackName
        description: The name of the stack to which the fleet is associated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Fleet
  /?Action=CreateFleet:
    get:
      summary: Create Fleet
      description: Creates a new fleet.
      operationId: CreateFleet
      x-api-path-slug: actioncreatefleet-get
      parameters:
      - in: query
        name: ComputeCapacity
        description: The parameters for the capacity allocated to the fleet
        type: string
      - in: query
        name: Description
        description: The description of the fleet
        type: string
      - in: query
        name: DisconnectTimeoutInSeconds
        description: The time after disconnection when a session is considered to
          have ended
        type: string
      - in: query
        name: DisplayName
        description: The display name of the fleet
        type: string
      - in: query
        name: ImageName
        description: Unique name of the image used by the fleet
        type: string
      - in: query
        name: InstanceType
        description: The instance type of compute resources for the fleet
        type: string
      - in: query
        name: MaxUserDurationInSeconds
        description: The maximum time up to which a streaming session can run
        type: string
      - in: query
        name: Name
        description: A unique identifier for the fleet
        type: string
      - in: query
        name: VpcConfig
        description: The VPC configuration for the fleet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Fleet
  /?Action=CreateStack:
    get:
      summary: Create Stack
      description: Create a new stack.
      operationId: CreateStack
      x-api-path-slug: actioncreatestack-get
      parameters:
      - in: query
        name: Description
        description: The description displayed to end users on the AppStream 2
        type: string
      - in: query
        name: DisplayName
        description: The name displayed to end users on the AppStream 2
        type: string
      - in: query
        name: Name
        description: The unique identifier for this stack
        type: string
      responses:
        200:
          description: OK
      tags:
      - Fleet
  /?Action=CreateStreamingURL:
    get:
      summary: Create Streaming URL
      description: Creates a URL to start an AppStream 2.
      operationId: CreateStreamingURL
      x-api-path-slug: actioncreatestreamingurl-get
      parameters:
      - in: query
        name: ApplicationId
        description: The ID of the application that must be launched after the session
          starts
        type: string
      - in: query
        name: FleetName
        description: The fleet for which the URL is generated
        type: string
      - in: query
        name: SessionContext
        description: The sessionContext of the streaming URL
        type: string
      - in: query
        name: StackName
        description: The stack for which the URL is generated
        type: string
      - in: query
        name: UserId
        description: A unique user ID for whom the URL is generated
        type: string
      - in: query
        name: Validity
        description: The validity duration of the URL in seconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - URL
  /?Action=DeleteFleet:
    get:
      summary: Delete Fleet
      description: Deletes a fleet.
      operationId: DeleteFleet
      x-api-path-slug: actiondeletefleet-get
      parameters:
      - in: query
        name: Name
        description: The name of the fleet to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Fleet
  /?Action=DeleteStack:
    get:
      summary: Delete Stack
      description: Deletes the stack.
      operationId: DeleteStack
      x-api-path-slug: actiondeletestack-get
      parameters:
      - in: query
        name: Name
        description: The name of the stack to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stack
  /?Action=DescribeFleets:
    get:
      summary: Describe Fleets
      description: |-
        If fleet names are provided, this operation describes the specified fleets;
                    otherwise, all the fleets in the account are described.
      operationId: DescribeFleets
      x-api-path-slug: actiondescribefleets-get
      parameters:
      - in: query
        name: Names
        description: The fleet names to describe
        type: string
      - in: query
        name: NextToken
        description: The pagination token to use to retrieve the next page of results
          for this operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Fleet
  /?Action=DescribeImages:
    get:
      summary: Describe Images
      description: Describes the images.
      operationId: DescribeImages
      x-api-path-slug: actiondescribeimages-get
      parameters:
      - in: query
        name: Names
        description: A specific list of images to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Images
  /?Action=DescribeSessions:
    get:
      summary: Describe Sessions
      description: Describes the streaming sessions for a stack and a fleet.
      operationId: DescribeSessions
      x-api-path-slug: actiondescribesessions-get
      parameters:
      - in: query
        name: FleetName
        description: The name of the fleet for which to list sessions
        type: string
      - in: query
        name: Limit
        description: The size of each page of results
        type: string
      - in: query
        name: NextToken
        description: The pagination token to use to retrieve the next page of results
          for this operation
        type: string
      - in: query
        name: StackName
        description: The name of the stack for which to list sessions
        type: string
      - in: query
        name: UserId
        description: The user for whom to list sessions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sessions
  /?Action=DescribeStacks:
    get:
      summary: Describe Stacks
      description: |-
        If stack names are not provided, this operation describes the specified stacks;
                    otherwise, all stacks in the account are described.
      operationId: DescribeStacks
      x-api-path-slug: actiondescribestacks-get
      parameters:
      - in: query
        name: Names
        description: The stack names to describe
        type: string
      - in: query
        name: NextToken
        description: The pagination token to use to retrieve the next page of results
          for this operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---