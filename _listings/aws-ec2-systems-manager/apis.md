---
name: AWS EC2 Systems Manager
x-slug: aws-ec2-systems-manager
description: Amazon EC2 Systems Manager is a management service that helps you automatically
  collect software inventory, apply OS patches, create system images, and configure
  Windows and Linux operating systems. These capabilities help you define and track
  system configurations, prevent drift, and maintain software compliance of your EC2
  and on-premises configurations. By providing a management approach that is designed
  for the scale and agility of the cloud but extends into your on-premises data center,
  EC2 Systems Manager makes it easier for you to seamlessly bridge your existing infrastructure
  with AWS.EC2 Systems Manager is easy to use. Simply access EC2 Systems Manager from
  the EC2 Management Console, select the instances you want to manage, and define
  the management tasks you want to perform. EC2 Systems Manager is available now at
  no cost to manage both your EC2 and on-premises resources.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Descriptions
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Activations
  x-api-slug: actiondescribeactivations-get
  description: |-
    Details about the activation, including: the date and time the activation was created,
       the expiration date, the IAM role assigned to the instances in the activation, and the number of
       instances activated by this registration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeactivations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Available Patches
  x-api-slug: actiondescribeavailablepatches-get
  description: Lists all patches that could possibly be included in a patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeavailablepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Effective Patches For Patch Baseline
  x-api-slug: actiondescribeeffectivepatchesforpatchbaseline-get
  description: Retrieves the current effective patches (the patch and the approval
    state) for the specified patch baseline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeeffectivepatchesforpatchbaseline-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Patches
  x-api-slug: actiondescribeinstancepatches-get
  description: Retrieves information about the patches on the specified instance and
    their state relative to the patch baseline being used for the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstancepatches-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Window Execution Task Invocations
  x-api-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
  description: |-
    Retrieves the individual task executions (one per target) for a particular task executed
       as part of a Maintenance Window execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindowexecutiontaskinvocations-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Maintenance Windows
  x-api-slug: actiondescribemaintenancewindows-get
  description: Retrieves the Maintenance Windows in an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribemaintenancewindows-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Patch Group State
  x-api-slug: actiondescribepatchgroupstate-get
  description: Returns high-level aggregated patch compliance state for a patch group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribepatchgroupstate-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Association
  x-api-slug: actiondescribeassociation-get
  description: Describes the associations for the specified SSM document or instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeassociation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document
  x-api-slug: actiondescribedocument-get
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Document Permission
  x-api-slug: actiondescribedocumentpermission-get
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
- name: AWS EC2 Systems Manager API - Describe Instance Information
  x-api-slug: actiondescribeinstanceinformation-get
  description: Describes one or more of your instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, Orchestration, API
    Service Provider, API Service Provider, API Provider, Deployments, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-ec2-systems-manager/actiondescribeinstanceinformation-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.ec2.container.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.systems.manager.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/ssm/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/systems-manager/faqs/
- type: x-getting-started
  url: http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/systems-manager.html
- type: x-website
  url: https://aws.amazon.com/ec2/systems-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---