---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Detaches a description from a role
  version: 1.0.0
  description: Detaches a description from a role.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/amenitydescription/Save:
    post:
      summary: Save or update an Amenity Description
      description: Save or update an amenity description.
      operationId: AmenityDescription_SaveDescriptionByamenityDescriptionDataContract
      x-api-path-slug: apiamenitydescriptionsave-post
      parameters:
      - in: body
        name: amenityDescriptionDataContract
        description: The amenity description to save
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Update
      - Amenity
      - Description
  /api/amenitydescription/Delete:
    delete:
      summary: Delete an Amenity Description by its Id
      description: Delete an amenity description by its id.
      operationId: AmenityDescription_DeleteDescriptionByid
      x-api-path-slug: apiamenitydescriptiondelete-delete
      parameters:
      - in: query
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Amenity
      - Description
      - By
      - Its
      - Id
  /api/AmenityDescription/{id}:
    get:
      summary: Get an Amenity Description by its Id
      description: Get an amenity description by its id.
      operationId: AmenityDescription_GetByid
      x-api-path-slug: apiamenitydescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Amenity
      - Description
      - By
      - Its
      - Id
  /api/document/{id}/savedescription:
    put:
      summary: Save the document description. Used for the image caption for the portals.
      description: Save the document description. used for the image caption for the
        portals..
      operationId: Document_SaveDescriptionByidBydescription
      x-api-path-slug: apidocumentidsavedescription-put
      parameters:
      - in: query
        name: description
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Document
      - Description
      - ""
      - Usedthe
      - Image
      - Captionthe
      - Portals
  /api/documentgeneration/renamelettertemplate/{id}:
    post:
      summary: Rename a letter template and change the description
      description: Rename a letter template and change the description.
      operationId: DocumentGeneration_UpdateLetterTemplateByidByrenameDataContract
      x-api-path-slug: apidocumentgenerationrenamelettertemplateid-post
      parameters:
      - in: path
        name: id
        description: Document Id for the template
      - in: body
        name: renameDataContract
        description: The letter template
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Rename
      - Letter
      - Template
      - Change
      - Description
  /api/group/{id}/setdescription:
    put:
      summary: Sets the description of the specified group
      description: Sets the description of the specified group.
      operationId: Group_SetDescriptionByidBynewDescriptionCommand
      x-api-path-slug: apigroupidsetdescription-put
      parameters:
      - in: path
        name: id
        description: The id of the group
      - in: body
        name: newDescriptionCommand
        description: The set description data contract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Description
      - Of
      - Specified
      - Group
  /api/localauthoritydescription/Save:
    post:
      summary: Save or update an Local Authority Description
      description: Save or update an local authority description.
      operationId: LocalAuthorityDescription_SaveDescriptionBylocalAuthorityDescriptionDataContract
      x-api-path-slug: apilocalauthoritydescriptionsave-post
      parameters:
      - in: body
        name: localAuthorityDescriptionDataContract
        description: The local authority description to save
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Update
      - Local
      - Authority
      - Description
  /api/LocalAuthorityDescription/{id}:
    get:
      summary: Get an Local Authority Description by its Id
      description: Get an local authority description by its id.
      operationId: LocalAuthorityDescription_GetByid
      x-api-path-slug: apilocalauthoritydescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Local
      - Authority
      - Description
      - By
      - Its
      - Id
    delete:
      summary: Delete an Local Authority Description by its Id
      description: Delete an local authority description by its id.
      operationId: LocalAuthorityDescription_DeleteDescriptionByid
      x-api-path-slug: apilocalauthoritydescriptionid-delete
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Local
      - Authority
      - Description
      - By
      - Its
      - Id
  /api/role/{id}/detachdescription:
    put:
      summary: Detaches a description from a role
      description: Detaches a description from a role.
      operationId: Role_DetachDescriptionByidBydescriptionId
      x-api-path-slug: apiroleiddetachdescription-put
      parameters:
      - in: query
        name: descriptionId
        description: The id of the description to detach
      - in: path
        name: id
        description: The id of the role to detach the description from
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Detaches
      - Description
      - From
      - Role
  /api/roomdescription/{id}/attachexternaldocumenttoroom:
    put:
      summary: Attaches an externally hosted document to a room within a room description.
      description: Attaches an externally hosted document to a room within a room
        description..
      operationId: RoomDescription_AttachExternalDocumentToRoomByidByexternalDocumentByroomId
      x-api-path-slug: apiroomdescriptionidattachexternaldocumenttoroom-put
      parameters:
      - in: body
        name: externalDocument
        description: Details of the external document
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The RoomDescriptionId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roomId
        description: The room identifier
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Externally
      - Hosted
      - Document
      - To
      - Room
      - Within
      - Room
      - Description
  /api/roomdescription/{id}/uploadandattachdocumenttoroom:
    put:
      summary: Uploads and attaches a document to room description room - the new
        document is appended to the current list.
      description: Uploads and attaches a document to room description room - the
        new document is appended to the current list..
      operationId: RoomDescription_UploadAndAttachDocumentToRoomByidByroomIdBydocumentDetails
      x-api-path-slug: apiroomdescriptioniduploadandattachdocumenttoroom-put
      parameters:
      - in: body
        name: documentDetails
        description: Details about the document
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The room description Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roomId
        description: The roomId
      responses:
        200:
          description: OK
      tags:
      - Uploads
      - Attaches
      - Document
      - To
      - Room
      - Description
      - Room
      - '-'
      - New
      - Document
      - Is
      - Appended
      - To
      - Current
      - List
  /api/roomdescription/{id}/detachdocumentfromroom:
    put:
      summary: Detaches a document from a room description room.
      description: Detaches a document from a room description room..
      operationId: RoomDescription_DetachDocumentFromRoomByidBydocumentIdByroomId
      x-api-path-slug: apiroomdescriptioniddetachdocumentfromroom-put
      parameters:
      - in: query
        name: documentId
        description: The document Id
      - in: path
        name: id
        description: The room description Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roomId
        description: The room Id
      responses:
        200:
          description: OK
      tags:
      - Detaches
      - Document
      - From
      - Room
      - Description
      - Room
  /api/customtextdescription/distinctcustompropertydescriptions:
    get:
      summary: Returns a list of the distinct defined custom descriptions for a property
      description: Returns a list of the distinct defined custom descriptions for
        a property.
      operationId: CustomTextDescription_DistinctCustomPropertyDescriptions
      x-api-path-slug: apicustomtextdescriptiondistinctcustompropertydescriptions-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - Distinct
      - Defined
      - Custom
      - Descriptionsa
      - Property
  /api/property/{id}/descriptions:
    get:
      summary: Get the descriptions for a property by property id
      description: Get the descriptions for a property by property id.
      operationId: Property_DescriptionsByidBypageSizeBypageNumberBytypes
      x-api-path-slug: apipropertyiddescriptions-get
      parameters:
      - in: path
        name: id
        description: The id of the property to get the descriptions for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: types
      responses:
        200:
          description: OK
      tags:
      - Descriptionsa
      - Property
      - By
      - Property
      - Id
  /api/role/{id}/descriptions:
    get:
      summary: Get the descriptions for a role by role id
      description: Get the descriptions for a role by role id.
      operationId: Role_DescriptionsByidBypageSizeBypageNumberBytypes
      x-api-path-slug: apiroleiddescriptions-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get the descriptions for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: types
      responses:
        200:
          description: OK
      tags:
      - Descriptionsa
      - Role
      - By
      - Role
      - Id
  /api/roomdescription/setimages:
    post:
      summary: Allows you to specify a list of documentIds for a roomDescriptions
        room - this list will overwrite any existing list of documents on that room,
        and order will be honoured.
      description: Allows you to specify a list of documentids for a roomdescriptions
        room - this list will overwrite any existing list of documents on that room,
        and order will be honoured..
      operationId: RoomDescription_SetImagesByroomImageOrder
      x-api-path-slug: apiroomdescriptionsetimages-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: roomImageOrder
        description: The room image order
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Specify
      - List
      - Of
      - DocumentIdsa
      - RoomDescriptions
      - Room
      - '-'
      - This
      - List
      - Will
      - Overwrite
      - Any
      - Existing
      - List
      - Of
      - Documents
      - "On"
      - That
      - Room
      - ""
      - Order
      - Will
      - Be
      - Honoured
  /api/ChargesDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: ChargesDescription_GetByid
      x-api-path-slug: apichargesdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/CostDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: CostDescription_GetByid
      x-api-path-slug: apicostdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/FeatureDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: FeatureDescription_GetByid
      x-api-path-slug: apifeaturedescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/FurnishingDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: FurnishingDescription_GetByid
      x-api-path-slug: apifurnishingdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/OccupierAllowanceDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: OccupierAllowanceDescription_GetByid
      x-api-path-slug: apioccupierallowancedescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/RoomCountDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: RoomCountDescription_GetByid
      x-api-path-slug: apiroomcountdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/RoomDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: RoomDescription_GetByid
      x-api-path-slug: apiroomdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/roomdescription/{id}/attachtorole:
    put:
      summary: Attach a RoomDescription to a PropertyMarketingRole
      description: Attach a roomdescription to a propertymarketingrole.
      operationId: RoomDescription_AttachToRoleByidByroleId
      x-api-path-slug: apiroomdescriptionidattachtorole-put
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - Attach
      - RoomDescription
      - To
      - PropertyMarketingRole
  /api/StyleAgeDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: StyleAgeDescription_GetByid
      x-api-path-slug: apistyleagedescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/TagDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: TagDescription_GetByid
      x-api-path-slug: apitagdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/TextDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: TextDescription_GetByid
      x-api-path-slug: apitextdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
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