---
swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 0
info:
  title: AWS Storage Gateway Service API Describe Bandwidth Rate Limit
  version: 1.0.0
  description: Returns the bandwidth rate limits of a gateway.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ActivateGateway:
    get:
      summary: Activate Gateway
      description: Activates the gateway you previously deployed on your host.
      operationId: activateGateway
      x-api-path-slug: actionactivategateway-get
      parameters:
      - in: query
        name: ActivationKey
        description: Your gateway activation key
        type: string
      - in: query
        name: GatewayName
        description: The name you configured for your gateway
        type: string
      - in: query
        name: GatewayRegion
        description: A value that indicates the region where you want to store the
          snapshot backups
        type: string
      - in: query
        name: GatewayTimezone
        description: A value that indicates the time zone you want to set for the
          gateway
        type: string
      - in: query
        name: GatewayType
        description: A value that defines the type of gateway to activate
        type: string
      - in: query
        name: MediumChangerType
        description: The value that indicates the type of medium changer to use for
          gateway-VTL
        type: string
      - in: query
        name: TapeDriveType
        description: The value that indicates the type of tape drive to use for gateway-VTL
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gateway
  /?Action=AddCache:
    get:
      summary: Add Cache
      description: Configures one or more gateway local disks as cache for a cached-volume
        gateway.
      operationId: addCache
      x-api-path-slug: actionaddcache-get
      parameters:
      - in: query
        name: DiskIds
        description: 'Type: array of Strings'
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache
  /?Action=AddTagsToResource:
    get:
      summary: Add Tags To Resource
      description: Adds one or more tags to the specified resource.
      operationId: addTagsToResource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceARN
        description: The Amazon Resource Name (ARN) of the resource you want to add
          tags to
        type: string
      - in: query
        name: Tags
        description: The key-value pair that represents the tag you want to add to
          the resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=AddUploadBuffer:
    get:
      summary: Add Upload Buffer
      description: Configures one or more gateway local disks as upload buffer for
        a specified gateway.
      operationId: addUploadBuffer
      x-api-path-slug: actionadduploadbuffer-get
      parameters:
      - in: query
        name: DiskIds
        description: 'Type: array of Strings'
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload Buffer
  /?Action=AddWorkingStorage:
    get:
      summary: Add Working Storage
      description: Configures one or more gateway local disks as working storage for
        a gateway.
      operationId: addWorkingStorage
      x-api-path-slug: actionaddworkingstorage-get
      parameters:
      - in: query
        name: DiskIds
        description: An array of strings that identify disks that are to be configured
          as working storage
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Working Storage
  /?Action=CancelArchival:
    get:
      summary: Cancel Archival
      description: |-
        Cancels archiving of a virtual tape to the virtual tape shelf (VTS) after the
                 archiving process is initiated.
      operationId: cancelArchival
      x-api-path-slug: actioncancelarchival-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: TapeARN
        description: The Amazon Resource Name (ARN) of the virtual tape you want to
          cancel archiving         for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Archival
  /?Action=CancelRetrieval:
    get:
      summary: Cancel Retrieval
      description: |-
        Cancels retrieval of a virtual tape from the virtual tape shelf (VTS) to a gateway
                 after the retrieval process is initiated.
      operationId: cancelRetrieval
      x-api-path-slug: actioncancelretrieval-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: TapeARN
        description: The Amazon Resource Name (ARN) of the virtual tape you want to
          cancel retrieval         for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Retrieval
  /?Action=CreateCachediSCSIVolume:
    get:
      summary: Create Cached SCSI Volume
      description: Creates a cached volume on a specified cached gateway.
      operationId: createCachediSCSIVolume
      x-api-path-slug: actioncreatecachediscsivolume-get
      parameters:
      - in: query
        name: ClientToken
        description: 'Type: String'
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: NetworkInterfaceId
        description: 'Type: String'
        type: string
      - in: query
        name: SnapshotId
        description: 'Type: String'
        type: string
      - in: query
        name: SourceVolumeARN
        description: The ARN for an existing volume
        type: string
      - in: query
        name: TargetName
        description: 'Type: String'
        type: string
      - in: query
        name: VolumeSizeInBytes
        description: 'Type: Long'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cached SCSI Volume
  /?Action=CreateNFSFileShare:
    get:
      summary: Create NFS File Share
      description: Creates a file share on an existing file gateway.
      operationId: createNFSFileShare
      x-api-path-slug: actioncreatenfsfileshare-get
      parameters:
      - in: query
        name: ClientToken
        description: A unique string value that you supply that is used by file gateway
          to ensure         idempotent file share creation
        type: string
      - in: query
        name: DefaultStorageClass
        description: The default storage class for objects put into an Amazon S3 bucket
          by file gateway
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the file gateway on which you
          want to create a file share
        type: string
      - in: query
        name: KMSEncrypted
        description: True to use Amazon S3 server side encryption with your own AWS
          KMS key, or false to         use a key managed by Amazon S3
        type: string
      - in: query
        name: KMSKey
        description: The KMS key used for Amazon S3 server side encryption
        type: string
      - in: query
        name: LocationARN
        description: The ARN of the backend storage used for storing file data
        type: string
      - in: query
        name: NFSFileShareDefaults
        description: File share default values
        type: string
      - in: query
        name: Role
        description: The ARN of the AWS Identity and Access Management (IAM) role
          that a file gateway         assumes when it accesses the underlying storage
        type: string
      responses:
        200:
          description: OK
      tags:
      - NFS File Share
  /?Action=CreateSnapshot:
    get:
      summary: Create Snapshot
      description: Initiates a snapshot of a volume.
      operationId: createSnapshot
      x-api-path-slug: actioncreatesnapshot-get
      parameters:
      - in: query
        name: SnapshotDescription
        description: Textual description of the snapshot that appears in the Amazon
          EC2 console, Elastic         Block Store snapshots panel in the Description
          field, and         in the AWS Storage Gateway snapshot Details pane,            Description
          field
        type: string
      - in: query
        name: VolumeARN
        description: The Amazon Resource Name (ARN) of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=CreateSnapshotFromVolumeRecoveryPoint:
    get:
      summary: Create Snapshot From Volume Recovery Point
      description: Initiates a snapshot of a gateway from a volume recovery point.
      operationId: createSnapshotFromVolumeRecoveryPoint
      x-api-path-slug: actioncreatesnapshotfromvolumerecoverypoint-get
      parameters:
      - in: query
        name: SnapshotDescription
        description: 'Type: String'
        type: string
      - in: query
        name: VolumeARN
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=CreateStorediSCSIVolume:
    get:
      summary: Create Stored SCSI Volume
      description: Creates a volume on a specified gateway.
      operationId: createStorediSCSIVolume
      x-api-path-slug: actioncreatestorediscsivolume-get
      parameters:
      - in: query
        name: DiskId
        description: The unique identifier for the gateway local disk that is configured
          as a stored         volume
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The network interface of the gateway on which to expose the iSCSI
          target
        type: string
      - in: query
        name: PreserveExistingData
        description: Specify this field as true if you want to preserve the data on
          the local disk
        type: string
      - in: query
        name: SnapshotId
        description: The snapshot ID (e
        type: string
      - in: query
        name: TargetName
        description: The name of the iSCSI target used by initiators to connect to
          the target and as a         suffix for the target ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stored SCSI Volume
  /?Action=CreateTapes:
    get:
      summary: Create Tapes
      description: Creates one or more virtual tapes.
      operationId: createTapes
      x-api-path-slug: actioncreatetapes-get
      parameters:
      - in: query
        name: ClientToken
        description: A unique identifier that you use to retry a request
        type: string
      - in: query
        name: GatewayARN
        description: The unique Amazon Resource Name (ARN) that represents the gateway
          to associate the         virtual tapes with
        type: string
      - in: query
        name: NumTapesToCreate
        description: The number of virtual tapes that you want to create
        type: string
      - in: query
        name: TapeBarcodePrefix
        description: A prefix that you append to the barcode of the virtual tape you
          are creating
        type: string
      - in: query
        name: TapeSizeInBytes
        description: The size, in bytes, of the virtual tapes that you want to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tapes
  /?Action=CreateTapeWithBarcode:
    get:
      summary: Create Tape With Barcode
      description: Creates a virtual tape by using your own barcode.
      operationId: createTapeWithBarcode
      x-api-path-slug: actioncreatetapewithbarcode-get
      parameters:
      - in: query
        name: GatewayARN
        description: The unique Amazon Resource Name (ARN) that represents the gateway
          to associate the         virtual tape with
        type: string
      - in: query
        name: TapeBarcode
        description: The barcode that you want to assign to the tape
        type: string
      - in: query
        name: TapeSizeInBytes
        description: The size, in bytes, of the virtual tape that you want to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tape With Barcode
  /?Action=DeleteBandwidthRateLimit:
    get:
      summary: Delete Bandwidth Rate Limit
      description: Deletes the bandwidth rate limits of a gateway.
      operationId: deleteBandwidthRateLimit
      x-api-path-slug: actiondeletebandwidthratelimit-get
      parameters:
      - in: query
        name: BandwidthType
        description: One of the BandwidthType values that indicates the gateway         bandwidth
          rate limit to delete
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bandwidth Rate Limit
  /?Action=DeleteChapCredentials:
    get:
      summary: Delete Chap Credentials
      description: |-
        Deletes Challenge-Handshake Authentication Protocol (CHAP) credentials for a
                 specified iSCSI target and initiator pair.
      operationId: deleteChapCredentials
      x-api-path-slug: actiondeletechapcredentials-get
      parameters:
      - in: query
        name: InitiatorName
        description: The iSCSI initiator that connects to the target
        type: string
      - in: query
        name: TargetARN
        description: The Amazon Resource Name (ARN) of the iSCSI volume target
        type: string
      responses:
        200:
          description: OK
      tags:
      - Chap Credentials
  /?Action=DeleteFileShare:
    get:
      summary: Delete File Share
      description: Deletes a file share from a file gateway.
      operationId: deleteFileShare
      x-api-path-slug: actiondeletefileshare-get
      parameters:
      - in: query
        name: FileShareARN
        description: The Amazon Resource Name (ARN) of the file share to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - File Share
  /?Action=DeleteGateway:
    get:
      summary: Delete Gateway
      description: Deletes a gateway.
      operationId: deleteGateway
      x-api-path-slug: actiondeletegateway-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gateway
  /?Action=DeleteSnapshotSchedule:
    get:
      summary: Delete Snapshot Schedule
      description: Deletes a snapshot of a volume.
      operationId: deleteSnapshotSchedule
      x-api-path-slug: actiondeletesnapshotschedule-get
      parameters:
      - in: query
        name: VolumeARN
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=DeleteTape:
    get:
      summary: Delete Tape
      description: Deletes the specified virtual tape.
      operationId: deleteTape
      x-api-path-slug: actiondeletetape-get
      parameters:
      - in: query
        name: GatewayARN
        description: The unique Amazon Resource Name (ARN) of the gateway that the
          virtual tape to delete         is associated with
        type: string
      - in: query
        name: TapeARN
        description: The Amazon Resource Name (ARN) of the virtual tape to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tapes
  /?Action=DeleteTapeArchive:
    get:
      summary: Delete Tape Archive
      description: Deletes the specified virtual tape from the virtual tape shelf
        (VTS).
      operationId: deleteTapeArchive
      x-api-path-slug: actiondeletetapearchive-get
      parameters:
      - in: query
        name: TapeARN
        description: The Amazon Resource Name (ARN) of the virtual tape to delete
          from the virtual tape         shelf (VTS)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tapes
      - Archives
  /?Action=DeleteVolume:
    get:
      summary: Delete Volume
      description: Deletes the specified gateway volume that you previously created
        using the.
      operationId: deleteVolume
      x-api-path-slug: actiondeletevolume-get
      parameters:
      - in: query
        name: VolumeARN
        description: The Amazon Resource Name (ARN) of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volumes
  /?Action=DescribeBandwidthRateLimit:
    get:
      summary: Describe Bandwidth Rate Limit
      description: Returns the bandwidth rate limits of a gateway.
      operationId: describeBandwidthRateLimit
      x-api-path-slug: actiondescribebandwidthratelimit-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bandwidth Rate Limit
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