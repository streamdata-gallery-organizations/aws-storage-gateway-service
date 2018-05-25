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
x-alexaRank: ""
tags: AWS Storage Gateway Service
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Storage Gateway Service API Activate Gateway
  x-api-slug: aws-storage-gateway-service-api
  description: Activates the gateway you previously deployed on your host.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ActivateGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionactivategateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionactivategateway-get-openapi.md
- name: AWS Storage Gateway Service API Add Cache
  x-api-slug: aws-storage-gateway-service-api
  description: Configures one or more gateway local disks as cache for a cached-volume
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=AddCache
  tags: Cache
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddcache-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddcache-get-openapi.md
- name: AWS Storage Gateway Service API Add Tags To Resource
  x-api-slug: aws-storage-gateway-service-api
  description: Adds one or more tags to the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=AddTagsToResource
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddtagstoresource-get-openapi.md
- name: AWS Storage Gateway Service API Add Upload Buffer
  x-api-slug: aws-storage-gateway-service-api
  description: Configures one or more gateway local disks as upload buffer for a specified
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=AddUploadBuffer
  tags: 'Upload Buffer '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionadduploadbuffer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionadduploadbuffer-get-openapi.md
- name: AWS Storage Gateway Service API Add Working Storage
  x-api-slug: aws-storage-gateway-service-api
  description: Configures one or more gateway local disks as working storage for a
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=AddWorkingStorage
  tags: Working Storage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionaddworkingstorage-get-openapi.md
- name: AWS Storage Gateway Service API Cancel Archival
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Cancels archiving of a virtual tape to the virtual tape shelf (VTS) after the
             archiving process is initiated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CancelArchival
  tags: Archival
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelarchival-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelarchival-get-openapi.md
- name: AWS Storage Gateway Service API Cancel Retrieval
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Cancels retrieval of a virtual tape from the virtual tape shelf (VTS) to a gateway
             after the retrieval process is initiated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CancelRetrieval
  tags: Retrieval
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelretrieval-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncancelretrieval-get-openapi.md
- name: AWS Storage Gateway Service API Create Cached SCSI Volume
  x-api-slug: aws-storage-gateway-service-api
  description: Creates a cached volume on a specified cached gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CreateCachediSCSIVolume
  tags: 'Cached SCSI Volume '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatecachediscsivolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatecachediscsivolume-get-openapi.md
- name: AWS Storage Gateway Service API Create NFS File Share
  x-api-slug: aws-storage-gateway-service-api
  description: Creates a file share on an existing file gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CreateNFSFileShare
  tags: 'NFS File Share '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatenfsfileshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatenfsfileshare-get-openapi.md
- name: AWS Storage Gateway Service API Create Snapshot
  x-api-slug: aws-storage-gateway-service-api
  description: Initiates a snapshot of a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CreateSnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatesnapshot-get-openapi.md
- name: AWS Storage Gateway Service API Create Snapshot From Volume Recovery Point
  x-api-slug: aws-storage-gateway-service-api
  description: Initiates a snapshot of a gateway from a volume recovery point.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CreateSnapshotFromVolumeRecoveryPoint
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatesnapshotfromvolumerecoverypoint-get-openapi.md
- name: AWS Storage Gateway Service API Create Stored SCSI Volume
  x-api-slug: aws-storage-gateway-service-api
  description: Creates a volume on a specified gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CreateStorediSCSIVolume
  tags: 'Stored SCSI Volume '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatestorediscsivolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatestorediscsivolume-get-openapi.md
- name: AWS Storage Gateway Service API Create Tapes
  x-api-slug: aws-storage-gateway-service-api
  description: Creates one or more virtual tapes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CreateTapes
  tags: Tapes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatetapes-get-openapi.md
- name: AWS Storage Gateway Service API Create Tape With Barcode
  x-api-slug: aws-storage-gateway-service-api
  description: Creates a virtual tape by using your own barcode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=CreateTapeWithBarcode
  tags: 'Tape With Barcode '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actioncreatetapewithbarcode-get-openapi.md
- name: AWS Storage Gateway Service API Delete Bandwidth Rate Limit
  x-api-slug: aws-storage-gateway-service-api
  description: Deletes the bandwidth rate limits of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteBandwidthRateLimit
  tags: 'Bandwidth Rate Limit '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletebandwidthratelimit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletebandwidthratelimit-get-openapi.md
- name: AWS Storage Gateway Service API Delete Chap Credentials
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Deletes Challenge-Handshake Authentication Protocol (CHAP) credentials for a
             specified iSCSI target and initiator pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteChapCredentials
  tags: 'Chap Credentials '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletechapcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletechapcredentials-get-openapi.md
- name: AWS Storage Gateway Service API Delete File Share
  x-api-slug: aws-storage-gateway-service-api
  description: Deletes a file share from a file gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteFileShare
  tags: 'File Share '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletefileshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletefileshare-get-openapi.md
- name: AWS Storage Gateway Service API Delete Gateway
  x-api-slug: aws-storage-gateway-service-api
  description: Deletes a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletegateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletegateway-get-openapi.md
- name: AWS Storage Gateway Service API Delete Snapshot Schedule
  x-api-slug: aws-storage-gateway-service-api
  description: Deletes a snapshot of a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteSnapshotSchedule
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletesnapshotschedule-get-openapi.md
- name: AWS Storage Gateway Service API Delete Tape
  x-api-slug: aws-storage-gateway-service-api
  description: Deletes the specified virtual tape.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteTape
  tags: Tapes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletetape-get-openapi.md
- name: AWS Storage Gateway Service API Delete Tape Archive
  x-api-slug: aws-storage-gateway-service-api
  description: Deletes the specified virtual tape from the virtual tape shelf (VTS).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteTapeArchive
  tags: Tapes,Archives
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletetapearchive-get-openapi.md
- name: AWS Storage Gateway Service API Delete Volume
  x-api-slug: aws-storage-gateway-service-api
  description: Deletes the specified gateway volume that you previously created using
    the.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DeleteVolume
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondeletevolume-get-openapi.md
- name: AWS Storage Gateway Service API Describe Bandwidth Rate Limit
  x-api-slug: aws-storage-gateway-service-api
  description: Returns the bandwidth rate limits of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeBandwidthRateLimit
  tags: 'Bandwidth Rate Limit '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribebandwidthratelimit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribebandwidthratelimit-get-openapi.md
- name: AWS Storage Gateway Service API Describe Cache
  x-api-slug: aws-storage-gateway-service-api
  description: Returns information about the cache of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeCache
  tags: Cache
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribecache-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribecache-get-openapi.md
- name: AWS Storage Gateway Service API Describe Cached SCSI Volumes
  x-api-slug: aws-storage-gateway-service-api
  description: Returns a description of the gateway volumes specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeCachediSCSIVolumes
  tags: 'Cached SCSI Volumes '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribecachediscsivolumes-get-openapi.md
- name: AWS Storage Gateway Service API Describe Chap Credentials
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Returns an array of Challenge-Handshake Authentication Protocol (CHAP) credentials
             information for a specified iSCSI target, one for each target-initiator pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeChapCredentials
  tags: 'Chap Credentials '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribechapcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribechapcredentials-get-openapi.md
- name: AWS Storage Gateway Service API Describe Gateway Information
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Returns metadata about a gateway such as its name, network interfaces, configured
             time zone, and the state (whether the gateway is running or not).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeGatewayInformation
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribegatewayinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribegatewayinformation-get-openapi.md
- name: AWS Storage Gateway Service API Describe Maintenance Start Time
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Returns your gateway's weekly maintenance start time including the day and time of
             the week.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeMaintenanceStartTime
  tags: Maintenance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribemaintenancestarttime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribemaintenancestarttime-get-openapi.md
- name: AWS Storage Gateway Service API Describe NFS File Shares
  x-api-slug: aws-storage-gateway-service-api
  description: Gets a description for one or more file shares from a file gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeNFSFileShares
  tags: 'NFS File Shares '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribenfsfileshares-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribenfsfileshares-get-openapi.md
- name: AWS Storage Gateway Service API Describe Snapshot Schedule
  x-api-slug: aws-storage-gateway-service-api
  description: Describes the snapshot schedule for the specified gateway volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeSnapshotSchedule
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribesnapshotschedule-get-openapi.md
- name: AWS Storage Gateway Service API Describe Stored SCSI Volumes
  x-api-slug: aws-storage-gateway-service-api
  description: Returns the description of the gateway volumes specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeStorediSCSIVolumes
  tags: 'Stored SCSI Volumes '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribestorediscsivolumes-get-openapi.md
- name: AWS Storage Gateway Service API Describe Tape Archives
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Returns a description of specified virtual tapes in the virtual tape shelf
             (VTS).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeTapeArchives
  tags: 'Tape Archives '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribetapearchives-get-openapi.md
- name: AWS Storage Gateway Service API Describe Tape Recovery Points
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Returns a list of virtual tape recovery points that are available for the specified
             gateway-VTL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeTapeRecoveryPoints
  tags: 'Tape Recovery Points '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribetaperecoverypoints-get-openapi.md
- name: AWS Storage Gateway Service API Describe Tapes
  x-api-slug: aws-storage-gateway-service-api
  description: Returns a description of the specified Amazon Resource Name (ARN) of
    virtual tapes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeTapes
  tags: Tapes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribetapes-get-openapi.md
- name: AWS Storage Gateway Service API Describe Upload Buffer
  x-api-slug: aws-storage-gateway-service-api
  description: Returns information about the upload buffer of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeUploadBuffer
  tags: 'Upload Buffer '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribeuploadbuffer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribeuploadbuffer-get-openapi.md
- name: AWS Storage Gateway Service API Describe VTL Devices
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Returns a description of virtual tape library (VTL) devices for the specified
             gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeVTLDevices
  tags: 'VTL Devices '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribevtldevices-get-openapi.md
- name: AWS Storage Gateway Service API Describe Working Storage
  x-api-slug: aws-storage-gateway-service-api
  description: Returns information about the working storage of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DescribeWorkingStorage
  tags: 'Working Storage '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondescribeworkingstorage-get-openapi.md
- name: AWS Storage Gateway Service API Disable Gateway
  x-api-slug: aws-storage-gateway-service-api
  description: Disables a gateway when the gateway is no longer functioning.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=DisableGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondisablegateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actiondisablegateway-get-openapi.md
- name: AWS Storage Gateway Service API List File Shares
  x-api-slug: aws-storage-gateway-service-api
  description: Gets a list of the file shares for a specific file gateway, or the
    list of file shares that belong to the calling user account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListFileShares
  tags: 'File Shares '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistfileshares-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistfileshares-get-openapi.md
- name: AWS Storage Gateway Service API List Gateways
  x-api-slug: aws-storage-gateway-service-api
  description: Lists gateways owned by an AWS account in a region specified in the
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListGateways
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistgateways-get-openapi.md
- name: AWS Storage Gateway Service API List Local Disks
  x-api-slug: aws-storage-gateway-service-api
  description: Returns a list of the gateway's local disks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListLocalDisks
  tags: 'Local Disks '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistlocaldisks-get-openapi.md
- name: AWS Storage Gateway Service API List Tags For Resource
  x-api-slug: aws-storage-gateway-service-api
  description: Lists the tags that have been added to the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListTagsForResource
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlisttagsforresource-get-openapi.md
- name: AWS Storage Gateway Service API List Tapes
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Lists virtual tapes in your virtual tape library (VTL) and your virtual tape shelf
             (VTS).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListTapes
  tags: Tapes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlisttapes-get-openapi.md
- name: AWS Storage Gateway Service API List Volume Initiators
  x-api-slug: aws-storage-gateway-service-api
  description: Lists iSCSI initiators that are connected to a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListVolumeInitiators
  tags: 'Volume Initiators '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumeinitiators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumeinitiators-get-openapi.md
- name: AWS Storage Gateway Service API List Volume Recovery Points
  x-api-slug: aws-storage-gateway-service-api
  description: Lists the recovery points for a specified gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListVolumeRecoveryPoints
  tags: Volume Recovery
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumerecoverypoints-get-openapi.md
- name: AWS Storage Gateway Service API List Volumes
  x-api-slug: aws-storage-gateway-service-api
  description: Lists the iSCSI stored volumes of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ListVolumes
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionlistvolumes-get-openapi.md
- name: AWS Storage Gateway Service API Remove Tags From Resource
  x-api-slug: aws-storage-gateway-service-api
  description: Removes one or more tags from the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=RemoveTagsFromResource
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionremovetagsfromresource-get-openapi.md
- name: AWS Storage Gateway Service API Reset Cache
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Resets all cache disks that have encountered a error and makes the disks available
             for reconfiguration as cache storage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ResetCache
  tags: Cache
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionresetcache-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionresetcache-get-openapi.md
- name: AWS Storage Gateway Service API Retrieve Tape Archive
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Retrieves an archived virtual tape from the virtual tape shelf (VTS) to a
             gateway-VTL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=RetrieveTapeArchive
  tags: Tapes,Archives
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionretrievetapearchive-get-openapi.md
- name: AWS Storage Gateway Service API Retrieve Tape Recovery Point
  x-api-slug: aws-storage-gateway-service-api
  description: Retrieves the recovery point for the specified virtual tape.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=RetrieveTapeRecoveryPoint
  tags: Tape Recovery
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionretrievetaperecoverypoint-get-openapi.md
- name: AWS Storage Gateway Service API Set Local Console Password
  x-api-slug: aws-storage-gateway-service-api
  description: Sets the password for your VM local console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=SetLocalConsolePassword
  tags: 'Local Console Password '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionsetlocalconsolepassword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionsetlocalconsolepassword-get-openapi.md
- name: AWS Storage Gateway Service API Shutdown Gateway
  x-api-slug: aws-storage-gateway-service-api
  description: Shuts down a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=ShutdownGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionshutdowngateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionshutdowngateway-get-openapi.md
- name: AWS Storage Gateway Service API Start Gateway
  x-api-slug: aws-storage-gateway-service-api
  description: Starts a gateway that you previously shut down (see.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=StartGateway
  tags: Gateway
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionstartgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionstartgateway-get-openapi.md
- name: AWS Storage Gateway Service API Update Bandwidth Rate Limit
  x-api-slug: aws-storage-gateway-service-api
  description: Updates the bandwidth rate limits of a gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateBandwidthRateLimit
  tags: 'Bandwidth Rate Limit '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatebandwidthratelimit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatebandwidthratelimit-get-openapi.md
- name: AWS Storage Gateway Service API Update Chap Credentials
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Updates the Challenge-Handshake Authentication Protocol (CHAP) credentials for a
             specified iSCSI target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateChapCredentials
  tags: Chap Credentials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatechapcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatechapcredentials-get-openapi.md
- name: AWS Storage Gateway Service API Update Gateway Information
  x-api-slug: aws-storage-gateway-service-api
  description: Updates a gateway's metadata, which includes the gateway's name and
    time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateGatewayInformation
  tags: 'Gateway '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewayinformation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewayinformation-get-openapi.md
- name: AWS Storage Gateway Service API Update Gateway Software Now
  x-api-slug: aws-storage-gateway-service-api
  description: Updates the gateway virtual machine (VM) software.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateGatewaySoftwareNow
  tags: 'Gateway '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewaysoftwarenow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdategatewaysoftwarenow-get-openapi.md
- name: AWS Storage Gateway Service API Update Maintenance Start Time
  x-api-slug: aws-storage-gateway-service-api
  description: |-
    Updates a gateway's weekly maintenance start time information, including day and time
             of the week.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateMaintenanceStartTime
  tags: Maintenance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatemaintenancestarttime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatemaintenancestarttime-get-openapi.md
- name: AWS Storage Gateway Service API Update NFS File Share
  x-api-slug: aws-storage-gateway-service-api
  description: Updates a file share.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateNFSFileShare
  tags: 'NFS File Share '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatenfsfileshare-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatenfsfileshare-get-openapi.md
- name: AWS Storage Gateway Service API Update Snapshot Schedule
  x-api-slug: aws-storage-gateway-service-api
  description: Updates a snapshot schedule configured for a gateway volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateSnapshotSchedule
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatesnapshotschedule-get-openapi.md
- name: AWS Storage Gateway Service API Update VTL Device Type
  x-api-slug: aws-storage-gateway-service-api
  description: Updates the type of medium changer in a gateway-VTL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: ://///?Action=UpdateVTLDeviceType
  tags: 'VTL Device Type '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatevtldevicetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/actionupdatevtldevicetype-get-openapi.md
- name: AWS Storage Gateway Service API
  x-api-slug: aws-storage-gateway-service-api
  description: The AWS Storage Gateway service seamlessly enables hybrid storage between
    on-premises storage environments andthe AWS Cloud. It combines a multi-protocol
    storage appliance with highly efficient network connectivity toAmazon cloud storageservices,
    delivering local performance with virtually unlimited scale. Customers use it
    in remote offices and datacenters for hybrid cloud workloads, backup and restore,
    archive, disaster recovery, and tiered storage.The Storage Gateway virtual appliance
    connects seamlessly to your local infrastructure as a file server, as a volume,
    or as a virtual tape library (VTL). This seamless connection makes it simple for
    organizations to augment existing on-premises storage investments with the high
    scalability, extreme durability and low cost of cloud storage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: AWS Storage Gateway Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-storage-gateway-service/master/_listings/aws-storage-gateway-service/openapi.md
x-common:
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