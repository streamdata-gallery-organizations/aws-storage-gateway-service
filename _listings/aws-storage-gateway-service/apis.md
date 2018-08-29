---
name: AWS Storage Gateway Service
x-slug: aws-storage-gateway-service
description: The AWS Storage Gateway service seamlessly enables hybrid storage between
  on-premises storage environments andthe AWS Cloud. It combines a multi-protocol
  storage appliance with highly efficient network connectivity toAmazon cloud storageservices,
  delivering local performance with virtually unlimited scale. Customers use it in
  remote offices and datacenters for hybrid cloud workloads, backup and restore, archive,
  disaster recovery, and tiered storage.The Storage Gateway virtual appliance connects
  seamlessly to your local infrastructure as a file server, as a volume, or as a virtual
  tape library (VTL). This seamless connection makes it simple for organizations to
  augment existing on-premises storage investments with the high scalability, extreme
  durability and low cost of cloud storage.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Storage Gateway Service
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Storage Gateway Service API - Activate Gateway
  x-api-slug: actionactivategateway-get
  description: Activates the gateway you previously deployed on your host.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionactivategateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionactivategateway-get-openapi.md
- name: AWS Storage Gateway Service API - Add Cache
  x-api-slug: actionaddcache-get
  description: Configures one or more gateway local disks as cache for a cached-volume
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddcache-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddcache-get-openapi.md
- name: AWS Storage Gateway Service API - Add Tags To Resource
  x-api-slug: actionaddtagstoresource-get
  description: Adds one or more tags to the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddtagstoresource-get-openapi.md
- name: AWS Storage Gateway Service API - Add Upload Buffer
  x-api-slug: actionadduploadbuffer-get
  description: Configures one or more gateway local disks as upload buffer for a specified
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionadduploadbuffer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionadduploadbuffer-get-openapi.md
- name: AWS Storage Gateway Service API - Add Working Storage
  x-api-slug: actionaddworkingstorage-get
  description: Configures one or more gateway local disks as working storage for a
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddworkingstorage-get-openapi.md
- name: AWS Storage Gateway Service API - Cancel Archival
  x-api-slug: actioncancelarchival-get
  description: |-
    Cancels archiving of a virtual tape to the virtual tape shelf (VTS) after the
             archiving process is initiated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelarchival-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelarchival-get-openapi.md
- name: AWS Storage Gateway Service API - Cancel Retrieval
  x-api-slug: actioncancelretrieval-get
  description: |-
    Cancels retrieval of a virtual tape from the virtual tape shelf (VTS) to a gateway
             after the retrieval process is initiated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelretrieval-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelretrieval-get-openapi.md
- name: AWS Storage Gateway Service API - Create Cached SCSI Volume
  x-api-slug: actioncreatecachediscsivolume-get
  description: Creates a cached volume on a specified cached gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatecachediscsivolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatecachediscsivolume-get-openapi.md
- name: AWS Storage Gateway Service API - Create NFS File Share
  x-api-slug: actioncreatenfsfileshare-get
  description: Creates a file share on an existing file gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatenfsfileshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatenfsfileshare-get-openapi.md
- name: AWS Storage Gateway Service API - Create Snapshot
  x-api-slug: actioncreatesnapshot-get
  description: Initiates a snapshot of a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatesnapshot-get-openapi.md
- name: AWS Storage Gateway Service API - Create Snapshot From Volume Recovery Point
  x-api-slug: actioncreatesnapshotfromvolumerecoverypoint-get
  description: Initiates a snapshot of a gateway from a volume recovery point.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatesnapshotfromvolumerecoverypoint-get-openapi.md
- name: AWS Storage Gateway Service API - Create Stored SCSI Volume
  x-api-slug: actioncreatestorediscsivolume-get
  description: Creates a volume on a specified gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatestorediscsivolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatestorediscsivolume-get-openapi.md
- name: AWS Storage Gateway Service API - Create Tapes
  x-api-slug: actioncreatetapes-get
  description: Creates one or more virtual tapes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatetapes-get-openapi.md
- name: AWS Storage Gateway Service API - Create Tape With Barcode
  x-api-slug: actioncreatetapewithbarcode-get
  description: Creates a virtual tape by using your own barcode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatetapewithbarcode-get-openapi.md
- name: AWS Storage Gateway Service API - Delete Bandwidth Rate Limit
  x-api-slug: actiondeletebandwidthratelimit-get
  description: Deletes the bandwidth rate limits of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletebandwidthratelimit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletebandwidthratelimit-get-openapi.md
- name: AWS Storage Gateway Service API - Delete Chap Credentials
  x-api-slug: actiondeletechapcredentials-get
  description: |-
    Deletes Challenge-Handshake Authentication Protocol (CHAP) credentials for a
             specified iSCSI target and initiator pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletechapcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletechapcredentials-get-openapi.md
- name: AWS Storage Gateway Service API - Delete File Share
  x-api-slug: actiondeletefileshare-get
  description: Deletes a file share from a file gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletefileshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletefileshare-get-openapi.md
- name: AWS Storage Gateway Service API - Delete Gateway
  x-api-slug: actiondeletegateway-get
  description: Deletes a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletegateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletegateway-get-openapi.md
- name: AWS Storage Gateway Service API - Delete Snapshot Schedule
  x-api-slug: actiondeletesnapshotschedule-get
  description: Deletes a snapshot of a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletesnapshotschedule-get-openapi.md
- name: AWS Storage Gateway Service API - Delete Tape
  x-api-slug: actiondeletetape-get
  description: Deletes the specified virtual tape.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletetape-get-openapi.md
- name: AWS Storage Gateway Service API - Delete Tape Archive
  x-api-slug: actiondeletetapearchive-get
  description: Deletes the specified virtual tape from the virtual tape shelf (VTS).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletetapearchive-get-openapi.md
- name: AWS Storage Gateway Service API - Delete Volume
  x-api-slug: actiondeletevolume-get
  description: Deletes the specified gateway volume that you previously created using
    the.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletevolume-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Bandwidth Rate Limit
  x-api-slug: actiondescribebandwidthratelimit-get
  description: Returns the bandwidth rate limits of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribebandwidthratelimit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribebandwidthratelimit-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Cache
  x-api-slug: actiondescribecache-get
  description: Returns information about the cache of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribecache-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribecache-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Cached SCSI Volumes
  x-api-slug: actiondescribecachediscsivolumes-get
  description: Returns a description of the gateway volumes specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribecachediscsivolumes-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Chap Credentials
  x-api-slug: actiondescribechapcredentials-get
  description: |-
    Returns an array of Challenge-Handshake Authentication Protocol (CHAP) credentials
             information for a specified iSCSI target, one for each target-initiator pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribechapcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribechapcredentials-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Gateway Information
  x-api-slug: actiondescribegatewayinformation-get
  description: |-
    Returns metadata about a gateway such as its name, network interfaces, configured
             time zone, and the state (whether the gateway is running or not).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribegatewayinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribegatewayinformation-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Maintenance Start Time
  x-api-slug: actiondescribemaintenancestarttime-get
  description: |-
    Returns your gateway's weekly maintenance start time including the day and time of
             the week.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribemaintenancestarttime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribemaintenancestarttime-get-openapi.md
- name: AWS Storage Gateway Service API - Describe NFS File Shares
  x-api-slug: actiondescribenfsfileshares-get
  description: Gets a description for one or more file shares from a file gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribenfsfileshares-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribenfsfileshares-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Snapshot Schedule
  x-api-slug: actiondescribesnapshotschedule-get
  description: Describes the snapshot schedule for the specified gateway volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribesnapshotschedule-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Stored SCSI Volumes
  x-api-slug: actiondescribestorediscsivolumes-get
  description: Returns the description of the gateway volumes specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribestorediscsivolumes-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Tape Archives
  x-api-slug: actiondescribetapearchives-get
  description: |-
    Returns a description of specified virtual tapes in the virtual tape shelf
             (VTS).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribetapearchives-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Tape Recovery Points
  x-api-slug: actiondescribetaperecoverypoints-get
  description: |-
    Returns a list of virtual tape recovery points that are available for the specified
             gateway-VTL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribetaperecoverypoints-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Tapes
  x-api-slug: actiondescribetapes-get
  description: Returns a description of the specified Amazon Resource Name (ARN) of
    virtual tapes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribetapes-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Upload Buffer
  x-api-slug: actiondescribeuploadbuffer-get
  description: Returns information about the upload buffer of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribeuploadbuffer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribeuploadbuffer-get-openapi.md
- name: AWS Storage Gateway Service API - Describe VTL Devices
  x-api-slug: actiondescribevtldevices-get
  description: |-
    Returns a description of virtual tape library (VTL) devices for the specified
             gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribevtldevices-get-openapi.md
- name: AWS Storage Gateway Service API - Describe Working Storage
  x-api-slug: actiondescribeworkingstorage-get
  description: Returns information about the working storage of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribeworkingstorage-get-openapi.md
- name: AWS Storage Gateway Service API - Disable Gateway
  x-api-slug: actiondisablegateway-get
  description: Disables a gateway when the gateway is no longer functioning.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondisablegateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondisablegateway-get-openapi.md
- name: AWS Storage Gateway Service API - List File Shares
  x-api-slug: actionlistfileshares-get
  description: Gets a list of the file shares for a specific file gateway, or the
    list of file shares that belong to the calling user account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistfileshares-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistfileshares-get-openapi.md
- name: AWS Storage Gateway Service API - List Gateways
  x-api-slug: actionlistgateways-get
  description: Lists gateways owned by an AWS account in a region specified in the
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistgateways-get-openapi.md
- name: AWS Storage Gateway Service API - List Local Disks
  x-api-slug: actionlistlocaldisks-get
  description: Returns a list of the gateway's local disks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistlocaldisks-get-openapi.md
- name: AWS Storage Gateway Service API - List Tags For Resource
  x-api-slug: actionlisttagsforresource-get
  description: Lists the tags that have been added to the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlisttagsforresource-get-openapi.md
- name: AWS Storage Gateway Service API - List Tapes
  x-api-slug: actionlisttapes-get
  description: |-
    Lists virtual tapes in your virtual tape library (VTL) and your virtual tape shelf
             (VTS).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlisttapes-get-openapi.md
- name: AWS Storage Gateway Service API - List Volume Initiators
  x-api-slug: actionlistvolumeinitiators-get
  description: Lists iSCSI initiators that are connected to a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumeinitiators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumeinitiators-get-openapi.md
- name: AWS Storage Gateway Service API - List Volume Recovery Points
  x-api-slug: actionlistvolumerecoverypoints-get
  description: Lists the recovery points for a specified gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumerecoverypoints-get-openapi.md
- name: AWS Storage Gateway Service API - List Volumes
  x-api-slug: actionlistvolumes-get
  description: Lists the iSCSI stored volumes of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumes-get-openapi.md
- name: AWS Storage Gateway Service API - Remove Tags From Resource
  x-api-slug: actionremovetagsfromresource-get
  description: Removes one or more tags from the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionremovetagsfromresource-get-openapi.md
- name: AWS Storage Gateway Service API - Reset Cache
  x-api-slug: actionresetcache-get
  description: |-
    Resets all cache disks that have encountered a error and makes the disks available
             for reconfiguration as cache storage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionresetcache-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionresetcache-get-openapi.md
- name: AWS Storage Gateway Service API - Retrieve Tape Archive
  x-api-slug: actionretrievetapearchive-get
  description: |-
    Retrieves an archived virtual tape from the virtual tape shelf (VTS) to a
             gateway-VTL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionretrievetapearchive-get-openapi.md
- name: AWS Storage Gateway Service API - Retrieve Tape Recovery Point
  x-api-slug: actionretrievetaperecoverypoint-get
  description: Retrieves the recovery point for the specified virtual tape.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionretrievetaperecoverypoint-get-openapi.md
- name: AWS Storage Gateway Service API - Set Local Console Password
  x-api-slug: actionsetlocalconsolepassword-get
  description: Sets the password for your VM local console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionsetlocalconsolepassword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionsetlocalconsolepassword-get-openapi.md
- name: AWS Storage Gateway Service API - Shutdown Gateway
  x-api-slug: actionshutdowngateway-get
  description: Shuts down a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionshutdowngateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionshutdowngateway-get-openapi.md
- name: AWS Storage Gateway Service API - Start Gateway
  x-api-slug: actionstartgateway-get
  description: Starts a gateway that you previously shut down (see.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionstartgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionstartgateway-get-openapi.md
- name: AWS Storage Gateway Service API - Update Bandwidth Rate Limit
  x-api-slug: actionupdatebandwidthratelimit-get
  description: Updates the bandwidth rate limits of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatebandwidthratelimit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatebandwidthratelimit-get-openapi.md
- name: AWS Storage Gateway Service API - Update Chap Credentials
  x-api-slug: actionupdatechapcredentials-get
  description: |-
    Updates the Challenge-Handshake Authentication Protocol (CHAP) credentials for a
             specified iSCSI target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatechapcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatechapcredentials-get-openapi.md
- name: AWS Storage Gateway Service API - Update Gateway Information
  x-api-slug: actionupdategatewayinformation-get
  description: Updates a gateway's metadata, which includes the gateway's name and
    time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewayinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewayinformation-get-openapi.md
- name: AWS Storage Gateway Service API - Update Gateway Software Now
  x-api-slug: actionupdategatewaysoftwarenow-get
  description: Updates the gateway virtual machine (VM) software.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewaysoftwarenow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewaysoftwarenow-get-openapi.md
- name: AWS Storage Gateway Service API - Update Maintenance Start Time
  x-api-slug: actionupdatemaintenancestarttime-get
  description: |-
    Updates a gateway's weekly maintenance start time information, including day and time
             of the week.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatemaintenancestarttime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatemaintenancestarttime-get-openapi.md
- name: AWS Storage Gateway Service API - Update NFS File Share
  x-api-slug: actionupdatenfsfileshare-get
  description: Updates a file share.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatenfsfileshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatenfsfileshare-get-openapi.md
- name: AWS Storage Gateway Service API - Update Snapshot Schedule
  x-api-slug: actionupdatesnapshotschedule-get
  description: Updates a snapshot schedule configured for a gateway volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatesnapshotschedule-get-openapi.md
- name: AWS Storage Gateway Service API - Update VTL Device Type
  x-api-slug: actionupdatevtldevicetype-get
  description: Updates the type of medium changer in a gateway-VTL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatevtldevicetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatevtldevicetype-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.step.functions.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.storage.gateway.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/storagegateway/latest/APIReference
- type: x-faq
  url: https://aws.amazon.com/storagegateway/faqs/
- type: x-pricing
  url: https://aws.amazon.com/storagegateway/pricing/
- type: x-website
  url: https://aws.amazon.com/storagegateway/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---