---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Describe Vpc Classic Link
  version: 1.0.0
  description: Describes the ClassicLink status of one or more VPCs.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAccountAttributes:
    get:
      summary: Describe Account Attributes
      description: Describes attributes of your AWS account.
      operationId: describeaccountattributes
      x-api-path-slug: actiondescribeaccountattributes-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensureidempotency
          of the request
        type: string
      - in: query
        name: Description
        description: A description for the new AMI in the destination region
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Encrypted
        description: Specifies whether the destination snapshots of the copied image
          should be encrypted
        type: string
      - in: query
        name: KmsKeyId
        description: The full ARN of the AWS Key Management Service (AWS KMS) CMK
          to use when encrypting the snapshots of an image during a copy operation
        type: string
      - in: query
        name: Name
        description: The name of the new AMI in the destination region
        type: string
      - in: query
        name: SourceImageId
        description: The ID of the AMI to copy
        type: string
      - in: query
        name: SourceRegion
        description: The name of the region that contains the AMI to copy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account
  /?Action=DescribeAddresses:
    get:
      summary: Describe Addresses
      description: Describes one or more of your Elastic IP addresses.
      operationId: describeaddresses
      x-api-path-slug: actiondescribeaddresses-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: PublicIp.N
        description: One or more Elastic IP addresses
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP ADdress
  /?Action=DescribeAvailabilityZones:
    get:
      summary: Describe Availability Zones
      description: Describes one or more of the Availability Zones that are available
        to you.
      operationId: describeavailabilityzones
      x-api-path-slug: actiondescribeavailabilityzones-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: RegionName.N
        description: The names of one or more regions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Availability Zones
  /?Action=DescribeBundleTasks:
    get:
      summary: Describe Bundle Tasks
      description: Describes one or more of your bundling tasks.
      operationId: describebundletasks
      x-api-path-slug: actiondescribebundletasks-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of an EC2-Classic instance to link to the ClassicLink-enabled
          VPC
        type: string
      - in: query
        name: SecurityGroupId.N
        description: The ID of one or more of the VPCs security groups
        type: string
      - in: query
        name: VpcId
        description: The ID of a ClassicLink-enabled VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bundle Task
  /?Action=DescribeClassicLinkInstances:
    get:
      summary: Describe Classic Link Instances
      description: Describes one or more of your linked EC2-Classic instances.
      operationId: describeclassiclinkinstances
      x-api-path-slug: actiondescribeclassiclinkinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcId.N
        description: One or more VPCs for which you want to describe the ClassicLink
          status
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=DescribeConversionTasks:
    get:
      summary: Describe Conversion Tasks
      description: Describes one or more of your conversion tasks.
      operationId: describeconversiontasks
      x-api-path-slug: actiondescribeconversiontasks-get
      responses:
        200:
          description: OK
      tags:
      - Version Tasks
  /?Action=DescribeCustomerGateways:
    get:
      summary: Describe Customer Gateways
      description: Describes one or more of your VPN customer gateways.
      operationId: describecustomergateways
      x-api-path-slug: actiondescribecustomergateways-get
      parameters:
      - in: query
        name: AutoPlacement
        description: This is enabled by default
        type: string
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the Dedicated Hosts
        type: string
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure idempotency
          of the request
        type: string
      - in: query
        name: InstanceType
        description: Specify the instance type that you want your Dedicated Hosts
          to be configured for
        type: string
      - in: query
        name: Quantity
        description: The number of Dedicated Hosts you want to allocate to your account
          with these            parameters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Customer Gateways
  /?Action=DescribeDhcpOptions:
    get:
      summary: Describe Dhcp Options
      description: Describes one or more of your DHCP options sets.
      operationId: describedhcpoptions
      x-api-path-slug: actiondescribedhcpoptions-get
      parameters:
      - in: query
        name: Device
        description: The device name to expose to the instance (for example, /dev/sdh
          or        xvdh)
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: VolumeId
        description: The ID of the EBS volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - DHCP
  /?Action=DescribeEgressOnlyInternetGateways:
    get:
      summary: Describe Egress Only Internet Gateways
      description: Describes one or more of your egress-only Internet gateways.
      operationId: describeegressonlyinternetgateways
      x-api-path-slug: actiondescribeegressonlyinternetgateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InternetGatewayId.N
        description: One or more Internet gateway IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=DescribeExportTasks:
    get:
      summary: Describe Export Tasks
      description: Describes one or more of your export tasks.
      operationId: describeexporttasks
      x-api-path-slug: actiondescribeexporttasks-get
      parameters:
      - in: query
        name: AmazonProvidedIpv6CidrBlock
        description: Requests an Amazon-provided IPv6 CIDR block with a /56 prefix
          length for the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Export Takss
  /?Action=DescribeFlowLogs:
    get:
      summary: Describe Flow Logs
      description: Describes one or more flow logs.
      operationId: describeflowlogs
      x-api-path-slug: actiondescribeflowlogs-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: PolicyDocument
        description: A policy to attach to the endpoint that controls access to the
          service
        type: string
      - in: query
        name: RouteTableId.N
        description: One or more route table IDs
        type: string
      - in: query
        name: ServiceName
        description: The AWS service name, in the form com
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC in which the endpoint will be used
        type: string
      responses:
        200:
          description: OK
      tags:
      - Flow Logs
  /?Action=DescribeHostReservationOfferings:
    get:
      summary: Describe Host Reservation Offerings
      description: Describes the Dedicated Host Reservations that are available to
        purchase.
      operationId: describehostreservationofferings
      x-api-path-slug: actiondescribehostreservationofferings-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: HostReservationIdSet.N
        description: One or more host reservation IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=DescribeHostReservations:
    get:
      summary: Describe Host Reservations
      description: |-
        Describes Dedicated Host Reservations which are associated with Dedicated Hosts in
                    your account.
      operationId: describehostreservations
      x-api-path-slug: actiondescribehostreservations-get
      parameters:
      - in: query
        name: HostIdSet.N
        description: The ID/s of the Dedicated Host/s that the reservation will be
          associated            with
        type: string
      - in: query
        name: OfferingId
        description: The offering ID of the reservation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=DescribeHosts:
    get:
      summary: Describe Hosts
      description: Describes one or more of your Dedicated Hosts.
      operationId: describehosts
      x-api-path-slug: actiondescribehosts-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxDuration
        description: This is the maximum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: MinDuration
        description: This is the minimum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: OfferingId
        description: The ID of the reservation offering
        type: string
      responses:
        200:
          description: OK
      tags:
      - Hosts
  /?Action=DescribeIdentityIdFormat:
    get:
      summary: Describe Identity Id Format
      description: |-
        Describes the ID format settings for resources for the specified IAM user, IAM role, or root
              user.
      operationId: describeidentityidformat
      x-api-path-slug: actiondescribeidentityidformat-get
      parameters:
      - in: query
        name: Resource
        description: 'The type of resource: instance | reservation |        snapshot
          | volume'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Format
  /?Action=DescribeIdFormat:
    get:
      summary: Describe Id Format
      description: Describes the ID format settings for your resources on a per-region
        basis, for example, to view which resource types are enabled for longer IDs.
      operationId: describeidformat
      x-api-path-slug: actiondescribeidformat-get
      parameters:
      - in: query
        name: PrincipalArn
        description: The ARN of the principal, which can be an IAM user, IAM role,
          or the root user
        type: string
      - in: query
        name: Resource
        description: 'The type of resource: instance | reservation |        snapshot
          | volume'
        type: string
      - in: query
        name: UseLongIds
        description: Indicates whether the resource should use longer IDs (17-character
          IDs)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Format
  /?Action=DescribeImageAttribute:
    get:
      summary: Describe Image Attribute
      description: Describes the specified attribute of the specified AMI.
      operationId: describeimageattribute
      x-api-path-slug: actiondescribeimageattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ExecutableBy.N
        description: Scopes the images by users with explicit launch permissions
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ImageId.N
        description: One or more image IDs
        type: string
      - in: query
        name: Owner.N
        description: Filters the images by the owner
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=DescribeImages:
    get:
      summary: Describe Images
      description: Describes one or more of the images (AMIs, AKIs, and ARIs) available
        to you.
      operationId: describeimages
      x-api-path-slug: actiondescribeimages-get
      parameters:
      - in: query
        name: Attribute
        description: The name of the attribute to modify
        type: string
      - in: query
        name: Description
        description: A description for the AMI
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ImageId
        description: The ID of the AMI
        type: string
      - in: query
        name: LaunchPermission
        description: A launch permission modification
        type: string
      - in: query
        name: OperationType
        description: The operation type
        type: string
      - in: query
        name: ProductCode.N
        description: One or more product codes
        type: string
      - in: query
        name: UserGroup.N
        description: One or more user groups
        type: string
      - in: query
        name: UserId.N
        description: One or more AWS account IDs
        type: string
      - in: query
        name: Value
        description: The value of the attribute being modified
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=DescribeImportImageTasks:
    get:
      summary: Describe Import Image Tasks
      description: Displays details about an import virtual machine or import snapshot
        tasks that are already created.
      operationId: describeimportimagetasks
      x-api-path-slug: actiondescribeimportimagetasks-get
      responses:
        200:
          description: OK
      tags:
      - Import Image Tasks
  /?Action=DescribeImportSnapshotTasks:
    get:
      summary: Describe Import Snapshot Tasks
      description: Describes your import snapshot tasks.
      operationId: describeimportsnapshottasks
      x-api-path-slug: actiondescribeimportsnapshottasks-get
      parameters:
      - in: query
        name: Description
        description: A description for the instance being imported
        type: string
      - in: query
        name: DiskImage.N
        description: The disk image
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,      and provides an error response
        type: string
      - in: query
        name: LaunchSpecification
        description: The launch specification
        type: string
      - in: query
        name: Platform
        description: The instance operating system
        type: string
      responses:
        200:
          description: OK
      tags:
      - Import Snapshot Takss
  /?Action=DescribeInstanceAttribute:
    get:
      summary: Describe Instance Attribute
      description: Describes the specified attribute of the specified instance.
      operationId: describeinstanceattribute
      x-api-path-slug: actiondescribeinstanceattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InstanceId.N
        description: One or more instance IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token to request the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=DescribeInstances:
    get:
      summary: Describe Instances
      description: Describes one or more of your instances.
      operationId: describeinstances
      x-api-path-slug: actiondescribeinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: IncludeAllInstances
        description: When true, includes the health status for all instances
        type: string
      - in: query
        name: InstanceId.N
        description: One or more instance IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=DescribeInstanceStatus:
    get:
      summary: Describe Instance Status
      description: Describes the status of one or more instances.
      operationId: describeinstancestatus
      x-api-path-slug: actiondescribeinstancestatus-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance Status
  /?Action=DescribeInternetGateways:
    get:
      summary: Describe Internet Gateways
      description: Describes one or more of your Internet gateways.
      operationId: describeinternetgateways
      x-api-path-slug: actiondescribeinternetgateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InternetGatewayId
        description: The ID of the Internet gateway
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateways
  /?Action=DescribeKeyPairs:
    get:
      summary: Describe Key Pairs
      description: Describes one or more of your key pairs.
      operationId: describekeypairs
      x-api-path-slug: actiondescribekeypairs-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: KeyName
        description: A unique name for the key pair
        type: string
      - in: query
        name: PublicKeyMaterial
        description: The public key
        type: string
      responses:
        200:
          description: OK
      tags:
      - Key Paris
  /?Action=DescribeMovingAddresses:
    get:
      summary: Describe Moving Addresses
      description: Describes your Elastic IP addresses that are being moved to the
        EC2-VPC platform, or that are being restored to the EC2-Classic platform.
      operationId: describemovingaddresses
      x-api-path-slug: actiondescribemovingaddresses-get
      parameters:
      - in: query
        name: AssociationId
        description: '[EC2-VPC] The association ID'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: PublicIp
        description: '[EC2-Classic] The Elastic IP address'
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=DescribeNatGateways:
    get:
      summary: Describe Nat Gateways
      description: Describes one or more of the your NAT gateways.
      operationId: describenatgateways
      x-api-path-slug: actiondescribenatgateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - NAT Gateways
  /?Action=DescribeNetworkAcls:
    get:
      summary: Describe Network Acls
      description: Describes one or more of your network ACLs.
      operationId: describenetworkacls
      x-api-path-slug: actiondescribenetworkacls-get
      parameters:
      - in: query
        name: AssociationId
        description: The ID of the current association between the original network
          ACL and the subnet
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: NetworkAclId
        description: The ID of the new network ACL to associate with the subnet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network ACL
  /?Action=DescribeNetworkInterfaceAttribute:
    get:
      summary: Describe Network Interface Attribute
      description: Describes a network interface attribute.
      operationId: describenetworkinterfaceattribute
      x-api-path-slug: actiondescribenetworkinterfaceattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: NetworkInterfaceId.N
        description: One or more network interface IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=DescribeNetworkInterfaces:
    get:
      summary: Describe Network Interfaces
      description: Describes one or more of your network interfaces.
      operationId: describenetworkinterfaces
      x-api-path-slug: actiondescribenetworkinterfaces-get
      parameters:
      - in: query
        name: AttachmentId
        description: The ID of the attachment
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Force
        description: Specifies whether to force a detachment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=DescribePlacementGroups:
    get:
      summary: Describe Placement Groups
      description: Describes one or more of your placement groups.
      operationId: describeplacementgroups
      x-api-path-slug: actiondescribeplacementgroups-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ZoneName.N
        description: The names of one or more Availability Zones
        type: string
      responses:
        200:
          description: OK
      tags:
      - Placement Groups
  /?Action=DescribePrefixLists:
    get:
      summary: Describe Prefix Lists
      description: Describes available AWS services in a prefix list format, which
        includes the prefix list name and prefix list ID of the service and the IP
        address range for the service.
      operationId: describeprefixlists
      x-api-path-slug: actiondescribeprefixlists-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcEndpointId.N
        description: One or more endpoint IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Prefix List
  /?Action=DescribeRegions:
    get:
      summary: Describe Regions
      description: Describes one or more regions that are currently available to you.
      operationId: describeregions
      x-api-path-slug: actiondescriberegions-get
      responses:
        200:
          description: OK
      tags:
      - Regions
  /?Action=DescribeReservedInstances:
    get:
      summary: Describe Reserved Instances
      description: Describes one or more of the Reserved Instances that you purchased.
      operationId: describereservedinstances
      x-api-path-slug: actiondescribereservedinstances-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ReservedInstancesId
        description: One or more Reserved Instance IDs
        type: string
      - in: query
        name: ReservedInstancesListingId
        description: One or more Reserved Instance listing IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeReservedInstancesListings:
    get:
      summary: Describe Reserved Instances Listings
      description: Describes your account's Reserved Instance listings in the Reserved
        Instance Marketplace.
      operationId: describereservedinstanceslistings
      x-api-path-slug: actiondescribereservedinstanceslistings-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      - in: query
        name: ReservedInstancesModificationId.N
        description: IDs for the submitted modification request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeReservedInstancesModifications:
    get:
      summary: Describe Reserved Instances Modifications
      description: Describes the modifications made to your Reserved Instances.
      operationId: describereservedinstancesmodifications
      x-api-path-slug: actiondescribereservedinstancesmodifications-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone in which the Reserved Instance can be used
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: IncludeMarketplace
        description: Include Reserved Instance Marketplace offerings in the response
        type: string
      - in: query
        name: InstanceTenancy
        description: The tenancy of the instances covered by the reservation
        type: string
      - in: query
        name: InstanceType
        description: The instance type that the reservation will cover (for example,
          m1
        type: string
      - in: query
        name: MaxDuration
        description: The maximum duration (in seconds) to filter when searching for
          offerings
        type: string
      - in: query
        name: MaxInstanceCount
        description: The maximum number of instances to filter when searching for
          offerings
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: MinDuration
        description: The minimum duration (in seconds) to filter when searching for
          offerings
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      - in: query
        name: OfferingClass
        description: The offering class of the Reserved Instance
        type: string
      - in: query
        name: OfferingType
        description: The Reserved Instance offering type
        type: string
      - in: query
        name: ProductDescription
        description: The Reserved Instance product platform description
        type: string
      - in: query
        name: ReservedInstancesOfferingId.N
        description: One or more Reserved Instances offering IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeReservedInstancesOfferings:
    get:
      summary: Describe Reserved Instances Offerings
      description: Describes Reserved Instance offerings that are available for purchase.
      operationId: describereservedinstancesofferings
      x-api-path-slug: actiondescribereservedinstancesofferings-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: ReservedInstanceId.N
        description: The IDs of the Convertible Reserved Instances to exchange
        type: string
      - in: query
        name: TargetConfiguration.N
        description: The configuration requirements of the Convertible Reserved Instances
          to exchange for your current      Convertible Reserved Instances
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeRouteTables:
    get:
      summary: Describe Route Tables
      description: Describes one or more of your route tables.
      operationId: describeroutetables
      x-api-path-slug: actiondescriberoutetables-get
      parameters:
      - in: query
        name: GatewayId
        description: The ID of the virtual private gateway
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Tables
  /?Action=DescribeScheduledInstanceAvailability:
    get:
      summary: Describe Scheduled Instance Availability
      description: Finds available schedules that meet the specified criteria.
      operationId: describescheduledinstanceavailability
      x-api-path-slug: actiondescribescheduledinstanceavailability-get
      responses:
        200:
          description: OK
      tags:
      - Server Instance Availability
  /?Action=DescribeScheduledInstances:
    get:
      summary: Describe Scheduled Instances
      description: Describes one or more of your Scheduled Instances.
      operationId: describescheduledinstances
      x-api-path-slug: actiondescribescheduledinstances-get
      responses:
        200:
          description: OK
      tags:
      - Scheduled Server Instances
  /?Action=DescribeSecurityGroupReferences (EC2-VPC only):
    get:
      summary: Describe Security Group References ( E C2- V P C only)
      description: '[EC2-VPC only] Describes the VPCs on the other side of a VPC peering
        connection that are referencing the security groups you''ve specified in this
        request.'
      operationId: describesecuritygroupreferences-ec2vpc-only
      x-api-path-slug: actiondescribesecuritygroupreferences-ec2vpc-only-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: GroupId.N
        description: One or more security group IDs
        type: string
      - in: query
        name: GroupName.N
        description: '[EC2-Classic and default VPC only] One or more security group
          names'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=DescribeSecurityGroups:
    get:
      summary: Describe Security Groups
      description: Describes one or more of your security groups.
      operationId: describesecuritygroups
      x-api-path-slug: actiondescribesecuritygroups-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request, and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=DescribeSnapshotAttribute:
    get:
      summary: Describe Snapshot Attribute
      description: Describes the specified attribute of the specified snapshot.
      operationId: describesnapshotattribute
      x-api-path-slug: actiondescribesnapshotattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of snapshot results returned by DescribeSnapshots
          in      paginated output
        type: string
      - in: query
        name: NextToken
        description: The NextToken value returned from a previous paginated        DescribeSnapshots
          request where MaxResults was used and the      results exceeded the value
          of that parameter
        type: string
      - in: query
        name: Owner.N
        description: Returns the snapshots owned by the specified owner
        type: string
      - in: query
        name: RestorableBy.N
        description: One or more AWS accounts IDs that can create volumes from the
          snapshot
        type: string
      - in: query
        name: SnapshotId.N
        description: One or more snapshot IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive Snapshot
  /?Action=DescribeSnapshots:
    get:
      summary: Describe Snapshots
      description: Describes one or more of the EBS snapshots available to you.
      operationId: describesnapshots
      x-api-path-slug: actiondescribesnapshots-get
      parameters:
      - in: query
        name: Attribute
        description: The instance attribute
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: VolumeId
        description: The ID of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive Snapshot
  /?Action=DescribeSpotDatafeedSubscription:
    get:
      summary: Describe Spot Datafeed Subscription
      description: Describes the data feed for Spot instances.
      operationId: describespotdatafeedsubscription
      x-api-path-slug: actiondescribespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: SpotInstanceRequestId.N
        description: One or more Spot instance request IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Data Feed
  /?Action=DescribeSpotFleetInstances:
    get:
      summary: Describe Spot Fleet Instances
      description: Describes the running instances for the specified Spot fleet.
      operationId: describespotfleetinstances
      x-api-path-slug: actiondescribespotfleetinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: EventType
        description: The type of events to describe
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: SpotFleetRequestId
        description: The ID of the Spot fleet request
        type: string
      - in: query
        name: StartTime
        description: The starting date and time for the events, in UTC format (for
          example, YYYY-MM-DDTHH:MM:SSZ)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Fleet Instance
  /?Action=DescribeSpotFleetRequestHistory:
    get:
      summary: Describe Spot Fleet Request History
      description: Describes the events for the specified Spot fleet request during
        the specified time.
      operationId: describespotfleetrequesthistory
      x-api-path-slug: actiondescribespotfleetrequesthistory-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: SpotFleetRequestId.N
        description: The IDs of the Spot fleet requests
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Fleet Request History
  /?Action=DescribeSpotFleetRequests:
    get:
      summary: Describe Spot Fleet Requests
      description: Describes your Spot fleet requests.
      operationId: describespotfleetrequests
      x-api-path-slug: actiondescribespotfleetrequests-get
      responses:
        200:
          description: OK
      tags:
      - Sport Fleet Requests
  /?Action=DescribeSpotInstanceRequests:
    get:
      summary: Describe Spot Instance Requests
      description: Describes the Spot instance requests that belong to your account.
      operationId: describespotinstancerequests
      x-api-path-slug: actiondescribespotinstancerequests-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: Filters the results by the specified Availability Zone
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EndTime
        description: The date and time, up to the current date, from which to stop
          retrieving the price history data,        in UTC format (for example, YYYY-MM-DDTHH:MM:SSZ)
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InstanceType.N
        description: Filters the results by the specified instance types
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: ProductDescription.N
        description: Filters the results by the specified basic product descriptions
        type: string
      - in: query
        name: StartTime
        description: The date and time, up to the past 90 days, from which to start
          retrieving the price history data,        in UTC format (for example, YYYY-MM-DDTHH:MM:SSZ)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Instance Requests
  /?Action=DescribeSpotPriceHistory:
    get:
      summary: Describe Spot Price History
      description: Describes the Spot price history.
      operationId: describespotpricehistory
      x-api-path-slug: actiondescribespotpricehistory-get
      parameters:
      - in: query
        name: AvailabilityZoneGroup
        description: The user-specified name for a logical grouping of bids
        type: string
      - in: query
        name: BlockDurationMinutes
        description: The required duration for the Spot instances (also known as Spot
          blocks), in minutes
        type: string
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier that you provide to ensure
          the idempotency of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceCount
        description: The maximum number of Spot instances to launch
        type: string
      - in: query
        name: LaunchGroup
        description: The instance launch group
        type: string
      - in: query
        name: LaunchSpecification
        description: Describes the launch specification for an instance
        type: string
      - in: query
        name: SpotPrice
        description: The maximum hourly price (bid) for any Spot instance launched
          to fulfill the request
        type: string
      - in: query
        name: Type
        description: The Spot instance request type
        type: string
      - in: query
        name: ValidFrom
        description: The start date of the request
        type: string
      - in: query
        name: ValidUntil
        description: The end date of the request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Price History
  /?Action=DescribeStaleSecurityGroups (EC2-VPC only):
    get:
      summary: Describe Stale Security Groups ( E C2- V P C only)
      description: '[EC2-VPC only] Describes the stale security group rules for security
        groups in a specified VPC.'
      operationId: describestalesecuritygroups-ec2vpc-only
      x-api-path-slug: actiondescribestalesecuritygroups-ec2vpc-only-get
      parameters:
      - in: query
        name: CidrIp
        description: The CIDR IP address range
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: FromPort
        description: The start of port range for the TCP and UDP protocols, or an
          ICMP type number
        type: string
      - in: query
        name: GroupId
        description: The ID of the security group
        type: string
      - in: query
        name: IpPermissions.N
        description: A set of IP permissions
        type: string
      - in: query
        name: IpProtocol
        description: The IP protocol name or number
        type: string
      - in: query
        name: SourceSecurityGroupName
        description: The name of a destination security group
        type: string
      - in: query
        name: SourceSecurityGroupOwnerId
        description: The AWS account number for a destination security group
        type: string
      - in: query
        name: ToPort
        description: The end of port range for the TCP and UDP protocols, or an ICMP
          type number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
  /?Action=DescribeSubnets:
    get:
      summary: Describe Subnets
      description: Describes one or more of your subnets.
      operationId: describesubnets
      x-api-path-slug: actiondescribesubnets-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID for the CIDR block
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnets
  /?Action=DescribeTags:
    get:
      summary: Describe Tags
      description: Describes one or more of the tags for your EC2 resources.
      operationId: describetags
      x-api-path-slug: actiondescribetags-get
      parameters:
      - in: query
        name: ConversionTaskId
        description: The ID of the conversion task
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,      and provides an error response
        type: string
      - in: query
        name: ReasonMessage
        description: The reason for canceling the conversion task
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DescribeVolumeAttribute:
    get:
      summary: Describe Volume Attribute
      description: Describes the specified attribute of the specified volume.
      operationId: describevolumeattribute
      x-api-path-slug: actiondescribevolumeattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of volume results returned by DescribeVolumes
          in paginated      output
        type: string
      - in: query
        name: NextToken
        description: The NextToken value returned from a previous paginated        DescribeVolumes
          request where MaxResults was used and the results      exceeded the value
          of that parameter
        type: string
      - in: query
        name: VolumeId.N
        description: One or more volume IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volumes
  /?Action=DescribeVolumes:
    get:
      summary: Describe Volumes
      description: Describes the specified EBS volumes.
      operationId: describevolumes
      x-api-path-slug: actiondescribevolumes-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of volume results returned by DescribeVolumeStatus
          in      paginated output
        type: string
      - in: query
        name: NextToken
        description: The NextToken value to include in a future DescribeVolumeStatus      request
        type: string
      - in: query
        name: VolumeId.N
        description: One or more volume IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volumes
  /?Action=DescribeVolumeStatus:
    get:
      summary: Describe Volume Status
      description: Describes the status of the specified volumes.
      operationId: describevolumestatus
      x-api-path-slug: actiondescribevolumestatus-get
      parameters:
      - in: query
        name: Device
        description: The device name
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Force
        description: Forces detachment if the previous detachment attempt did not
          occur cleanly (for example,      logging into an instance, unmounting the
          volume, and detaching normally)
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: VolumeId
        description: The ID of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volume Status
  /?Action=DescribeVpcAttribute:
    get:
      summary: Describe Vpc Attribute
      description: Describes the specified attribute of the specified VPC.
      operationId: describevpcattribute
      x-api-path-slug: actiondescribevpcattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcId.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpcClassicLink:
    get:
      summary: Describe Vpc Classic Link
      description: Describes the ClassicLink status of one or more VPCs.
      operationId: describevpcclassiclink
      x-api-path-slug: actiondescribevpcclassiclink-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcIds.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpcClassicLinkDnsSupport:
    get:
      summary: Describe Vpc Classic Link Dns Support
      description: Describes the ClassicLink DNS support status of one or more VPCs.
      operationId: describevpcclassiclinkdnssupport
      x-api-path-slug: actiondescribevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to unlink from the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC to which the instance is linked
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC DNS
  /?Action=DescribeVpcEndpoints:
    get:
      summary: Describe Vpc Endpoints
      description: Describes one or more of your VPC endpoints.
      operationId: describevpcendpoints
      x-api-path-slug: actiondescribevpcendpoints-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoints
  /?Action=DescribeVpcEndpointServices:
    get:
      summary: Describe Vpc Endpoint Services
      description: Describes all supported AWS services that can be specified when
        creating a VPC endpoint.
      operationId: describevpcendpointservices
      x-api-path-slug: actiondescribevpcendpointservices-get
      parameters:
      - in: query
        name: AddRouteTableId.N
        description: One or more route tables IDs to associate with the endpoint
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: PolicyDocument
        description: A policy document to attach to the endpoint
        type: string
      - in: query
        name: RemoveRouteTableId.N
        description: One or more route table IDs to disassociate from the endpoint
        type: string
      - in: query
        name: ResetPolicy
        description: Specify true to reset the policy document to the default policy
        type: string
      - in: query
        name: VpcEndpointId
        description: The ID of the endpoint
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoint Services
  /?Action=DescribeVpcPeeringConnections:
    get:
      summary: Describe Vpc Peering Connections
      description: Describes one or more of your VPC peering connections.
      operationId: describevpcpeeringconnections
      x-api-path-slug: actiondescribevpcpeeringconnections-get
      parameters:
      - in: query
        name: AccepterPeeringConnectionOptions
        description: The VPC peering connection options for the accepter VPC
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: RequesterPeeringConnectionOptions
        description: The VPC peering connection options for the requester VPC
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connections
  /?Action=DescribeVpcs:
    get:
      summary: Describe Vpcs
      description: Describes one or more of your VPCs.
      operationId: describevpcs
      x-api-path-slug: actiondescribevpcs-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID for the CIDR block
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpnConnections:
    get:
      summary: Describe Vpn Connections
      description: Describes one or more of your VPN connections.
      operationId: describevpnconnections
      x-api-path-slug: actiondescribevpnconnections-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Connections
  /?Action=DescribeVpnGateways:
    get:
      summary: Describe Vpn Gateways
      description: Describes one or more of your virtual private gateways.
      operationId: describevpngateways
      x-api-path-slug: actiondescribevpngateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateways
  /?Action=ImportSnapshot:
    get:
      summary: Import Snapshot
      description: Describes your import snapshot tasks.
      operationId: importsnapshot
      x-api-path-slug: actionimportsnapshot-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the resulting EBS volume
        type: string
      - in: query
        name: Description
        description: A description of the volume
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,      and provides an error response
        type: string
      - in: query
        name: Image
        description: The disk image
        type: string
      - in: query
        name: Volume
        description: The volume size
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshot
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