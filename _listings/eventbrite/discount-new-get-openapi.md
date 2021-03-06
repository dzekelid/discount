---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Discount New
  description: This method creates a new discount code for a specific event. It returns
    the ID of the newly created discount code.
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /discount_new:
    get:
      summary: Get Discount New
      description: This method creates a new discount code for a specific event. It
        returns the ID of the newly created discount code.
      operationId: Get_discount_new_
      x-api-path-slug: discount-new-get
      parameters:
      - in: query
        name: amount_off
        description: The fixed amount off the ticket price
      - in: query
        name: code
        description: The discount code
      - in: query
        name: data-type
        description: xml or json data-types are supported
      - in: query
        name: end_date
        description: The discount end date and time, in ISO 8601 format (e
      - in: query
        name: event_id
        description: The event ID
      - in: query
        name: percent_off
        description: The percentage off the ticket price
      - in: query
        name: quantity_available
        description: Maximum number of times this discount can be used
      - in: query
        name: start_date
        description: The discount start date and time, in ISO 8601 format (e
      - in: query
        name: tickets
        description: Comma-separated list of ticket IDs for which the discount applies
      responses:
        200:
          description: OK
      tags:
      - Discount
      - New
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