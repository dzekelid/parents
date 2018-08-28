---
swagger: "2.0"
x-collection-name: moltin
x-complete: 0
info:
  title: Moltin API Update Parent Category Parent
  description: Update parent category parent.
  version: 1.0.0
host: api.moltin.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/brands/{brandID}/relationships/parent:
    put:
      summary: Update Parent Brand Relationship
      description: Update parent brand relationship.
      operationId: V2BrandsRelationshipsParentByBrandIDPut
      x-api-path-slug: v2brandsbrandidrelationshipsparent-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: brandID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Parent
      - Brands
      - Relationship
    post:
      summary: Create Parent Brand Relationship
      description: Create parent brand relationship.
      operationId: V2BrandsRelationshipsParentByBrandIDPost
      x-api-path-slug: v2brandsbrandidrelationshipsparent-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: brandID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Parent
      - Brands
      - Relationship
    delete:
      summary: Delete Parent Brand Relationship
      description: Delete parent brand relationship.
      operationId: V2BrandsRelationshipsParentByBrandIDDelete
      x-api-path-slug: v2brandsbrandidrelationshipsparent-delete
      parameters:
      - in: path
        name: brandID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Parent
      - Brands
      - Relationship
  /v2/collections/{collectionID}/relationships/parent:
    put:
      summary: Update Parent Collection Relationship
      description: Update parent collection relationship.
      operationId: V2CollectionsRelationshipsParentByCollectionIDPut
      x-api-path-slug: v2collectionscollectionidrelationshipsparent-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: collectionID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Parent
      - Collection
      - Relationship
    post:
      summary: Create Parent Collection Relationship
      description: Create parent collection relationship.
      operationId: V2CollectionsRelationshipsParentByCollectionIDPost
      x-api-path-slug: v2collectionscollectionidrelationshipsparent-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: collectionID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Parent
      - Collection
      - Relationship
    delete:
      summary: Delete Parent Collection Relationship
      description: Delete parent collection relationship.
      operationId: V2CollectionsRelationshipsParentByCollectionIDDelete
      x-api-path-slug: v2collectionscollectionidrelationshipsparent-delete
      parameters:
      - in: header
        name: Accept
      - in: path
        name: collectionID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Parent
      - Collection
      - Relationship
  /v2/categories/{parentCatID}/relationships/parent:
    put:
      summary: Update Parent Category Parent
      description: Update parent category parent.
      operationId: V2CategoriesRelationshipsParentByParentCatIDPut
      x-api-path-slug: v2categoriesparentcatidrelationshipsparent-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: parentCatID
      responses:
        200:
          description: Successful response
      tags:
      - Parent
      - Category
      - Parent
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