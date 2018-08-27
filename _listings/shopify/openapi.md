---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
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
  /admin/discounts/2951196163.json:
    get:
      summary: Retrieve a discount
      description: Retrieve a discount.
      operationId: getAdminDiscounts2951196163.json
      x-api-path-slug: admindiscounts2951196163-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Discount
    delete:
      summary: Delete a discount
      description: Delete a discount.
      operationId: deleteAdminDiscounts2951196163.json
      x-api-path-slug: admindiscounts2951196163-json-delete
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
      - Discount
  /admin/discounts.json:
    post:
      summary: Create a discount
      description: Create a discount.
      operationId: postAdminDiscounts.json
      x-api-path-slug: admindiscounts-json-post
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
      - Discount
  /admin/discounts/2951196163/disable.json:
    post:
      summary: Disable a discount
      description: Disable a discount.
      operationId: postAdminDiscounts2951196163Disable.json
      x-api-path-slug: admindiscounts2951196163disable-json-post
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
      - Disable
      - Discount
  /admin/discounts/2951196163/enable.json:
    post:
      summary: Enable a discount
      description: Enable a discount.
      operationId: postAdminDiscounts2951196163Enable.json
      x-api-path-slug: admindiscounts2951196163enable-json-post
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
      - Enable
      - Discount
---