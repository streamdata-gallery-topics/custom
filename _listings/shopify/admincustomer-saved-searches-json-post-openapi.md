---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Create a new Customer Saved Search
  description: Create a new customer saved search.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/custom_collections.json:
    get:
      summary: Get a list of all custom collections
      description: Get a list of all custom collections.
      operationId: getAdminCustomCollections.json
      x-api-path-slug: admincustom-collections-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Custom
      - Collections
    post:
      summary: Create a new custom collection
      description: Create a new custom collection.
      operationId: postAdminCustomCollections.json
      x-api-path-slug: admincustom-collections-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Custom
      - Collection
  /admin/custom_collections/246409795.json:
    get:
      summary: Get a single custom collections
      description: Get a single custom collections.
      operationId: getAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Custom
      - Collections
    put:
      summary: update a custom collection
      description: Update a custom collection.
      operationId: putAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Custom
      - Collection
    delete:
      summary: delete a custom collection
      description: Delete a custom collection.
      operationId: deleteAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Delete
      - Custom
      - Collection
  /admin/custom_collections/count.json:
    get:
      summary: Get a count of all custom collections
      description: Get a count of all custom collections.
      operationId: getAdminCustomCollectionsCount.json
      x-api-path-slug: admincustom-collectionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Custom
      - Collections
  /admin/customer_saved_searches.json:
    post:
      summary: Create a new Customer Saved Search
      description: Create a new customer saved search.
      operationId: postAdminCustomerSavedSearches.json
      x-api-path-slug: admincustomer-saved-searches-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Customer
      - Saved
      - Search
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